##### How did you determine which rules should be placed in each new CSS file?

I basically followed these guidelines, along with some of the ones in our reading from yesterday.

base.css should contain any general styling on top of what is provided by a reset.css or normalize.css file (these files will be discussed in further detail in lecture)
Apply to elements such as body and main
Examples include styling of overall font and background color

layout.css should contain general positioning on the page
Apply to elements such as header, footer, nav, aside
Classes and IDs can be included here

modules.css should contain smaller components on the page
Apply to elements such as list items, individual images, specific paragraphs
Classes and descendant selectors should primarily be included here

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

I did not refactor any of the existing CSS, I thought about refactoring the aside and recipe because they could be broken down into a base, layout and module of those categories, but i decided to stick with the naming conventions that were given for easier readability.


