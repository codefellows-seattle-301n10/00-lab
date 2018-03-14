##### How did you determine which rules should be placed in each new CSS file?

For:
base.css - anything that pertained to core UI features were moved here.  This includes fonts, background colors, any styling of 'h' and 'hr' elements.  I put the button styling here because I think it's a base feature.

layout.css - anything that pertains to how the HTML body is layed out were moved here.  This includes anything done to the nav, aside, and sections.  The lab directions said classes and IDs can be moved here,so I moved them here.  Upon reading what those classes and IDs were, I thought they did have an impact on the layout.

modules.css - any styling of minor elements like ul, li, p were moved here.

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

None were made.  I tried to condense '.print' into the '.print, .date' selector, but that threw off the date alignment.  After separating the css code and undoing the refactoring attempt, index.html still displayed everything the way it should be, so I decided not to refactor the code.