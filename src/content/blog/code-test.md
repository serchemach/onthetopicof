---
title: Code markup test
---

Hello! This is a test of how code blocks are rendered
```
document.onkeyup = (event) => {
    console.log(1)
    if (event.ctrlKey && event.key === "ArrowUp"){
        let talentPoints = 0;
        while (talentPoints < 6) {
            reroll();
            talentPoints = getTalentPoints();
        }
    }
}
```
I think it will be fine for now...

