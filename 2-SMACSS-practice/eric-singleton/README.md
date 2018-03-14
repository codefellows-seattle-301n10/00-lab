##### How did you determine which rules should be placed in each new CSS file?

I took the simple, overall rules such as body and the hmtl5 tags settings and put those as the base since that essentially is the foundation of the containers. From there, I took the theme rules and put them in the layout as they are determining the appearance of the site so they should be grouped together and then for modules I put things such as the recipe styling and the date in the modules.css since those are more specific and if, for example, an overall form change is needed for the input style but nothing needs to be changed theme-wise, it could be easily accessible without affecting the greater theme

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

For this, I did not refactor any of the pre-existing code as so I could solidify my understanding of placing things in the correct css files. If I was to refactor, I would change the ids and classes to fit a more SMACSS style of semantics just to make it more reader-friendly to ensure that changes in the css or html would make sense in the future.