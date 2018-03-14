##### How did you determine which rules should be placed in each new CSS file?

I basically used a combination of either the readings or the instructions in the class repo. There were several items that could logically have gone into multiple files, so to keep things simple I essentially tried to think of it big to small. Big sections, overall styles, etc, went into the base. More specified elements into the layout. The most-specified elements went into the modules. I noticed in the class repo there was mention of a state.css file. I ended up only using it for one item, because I didn't notice anything else requiring user input.

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

The only real refactoring I did was the pathing for background images. After moving files, I had to change the navigation by going up one directory then back down into the image file. On that note, there still throws an error for one image which actually doesn't exist in the image directory we were given. However, it does not seem to effect anything on the displayed page so it was probably a leftover oversight from somewhere. On that note, I just commented it out in case that image was to be returned to the file. 

I could have changed some naming conventions, but since the SMACSS naming is symantic anyways, having the CSS existing in different files essentially filled that same symantic purpose. If it was one master file then maybe changing names would be better, but I find CSS easier if the names are simply the path to get to that element. For example, I like (body h1) because it points to where the element is located.
