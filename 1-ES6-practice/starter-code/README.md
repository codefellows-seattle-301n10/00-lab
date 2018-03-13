# 1-ES6-practice

## Feature Tasks

Follow these instructions carefully and in order.

1. Open the HTML file in the browser to ensure that it works.
2. Turn all `var` variable declarations into `let`.
3. After you do, there will be one error. Find that line in the code, delete that line and respond to the adjacent TODO item.
4. Return to the browser to ensure that the code works again.
5. **Save the code, and do a Git "add" and "commit".**
6. Now, in the code, convert all `let` variable declarations into `const`.
7. Bugs will erupt everywhere. Debug by using the error messages in the browser console, turning `const` declarations back into `let` where necessary. Expect there to be some back-and-forth between your code editor and your browser.
8. When you think you have things working, clear local storage and reload the page to ensure that the code still works when starting from a totally clean state.
9. **Save the code, and do a Git "add" and "commit".**
10. Now find all concatenations in the code and convert them into template literal notation.
11. Reload the browser to ensure that the code works as expected.
12. **Save the code, and do a Git "add" and "commit".**
13. Answer the following questions:

---

##### Investigate how `let` and `const` are now used in the code. Where did you need to convert `const` into `let` to make the code work? Can you identify any patterns/similarities?

(Put your answer here)

let is only available for use if it is in the same block of code as where it is asking to be used. let's 'bucket' contents can be changed and accessed and manipulated as well as its binding. const's binding connot be changed and only if its an object can the contents of its 'bucket' be changed. IE it connot be used in for loops or arrays, whereas let can, but only if it is being used inside that specific block of code, OR it is being declared 'globally'.

---

##### How did it go with making the adaptation from concatenations to template literal notation? Do you think you'll mostly use template literal notation from now on?

(Put your answer here)

we'll see. it is easier to read in the code, but the amount of keystrokes is about the same, so we will see. but it is easier to find and read concatination in the code when the new way is used.