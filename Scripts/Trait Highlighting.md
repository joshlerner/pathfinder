```
const tagTraitMarks = () => {
	const marks = document.querySelectorAll(".markdown-preview-view mark");
	
	marks.forEach(m => {
		const text = m.textContent.trim().toLowerCase();
			
		if (text === "uncommon") {
			m.classList.add("rarity-uncommon");
		} else if (text === "rare") {
			m.classList.add("rarity-rare");
		} else if (text === "unique") {
			m.classList.add("rarity-unique");
		} else if (text === "tiny" ||
				   text === "small" ||
				   text === "medium" ||
				   text === "large" ||
				   text === "huge" ||
				   text === "gargantuan") {
			m.classList.add("size");
		} else {
			m.classList.remove(
				"rarity-uncommon",
				"rarity-rare",
				"rarity-unique",
				"size");
		}
	});
};

app.workspace.on("file-open", tagTraitMarks);

app.workspace.on("active-leaf-change", tagTraitMarks);

const statblockObserver = new MutationObserver((mutations) => {
    mutations.forEach(m => {
        m.addedNodes.forEach(node => {
            if(node.nodeType === 1 && node.matches && node.matches(".statblock")) {
                tagTraitMarks();
            }
        });
    });
});

statblockObserver.observe(document.body, { childList: true, subtree: true });
```