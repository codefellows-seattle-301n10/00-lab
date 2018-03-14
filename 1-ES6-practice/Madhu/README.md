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
let is being used where the life of the variable is required for block of scope like if, while, or function specific block. 'const' is useful where re-assignment is not necessary when the object contains fixed value or string. Const is certainly useful to lock the structure of the object and it can be accessed only through key-value relationships. I had to change 'const' to 'let' where value is being incremented throughout the block like for loops or for counter variables. 'Const' is being used where complete object is required to be assigned where you have different key value pairs and also you can assign different values of properties.  'let' is useful for working with blocks where it can be assigned with different values without distrubing the other parts of same variable.
---

##### How did it go with making the adaptation from concatenations to template literal notation? Do you think you'll mostly use template literal notation from now on?

(Put your answer here)
It is very useful since it eleminates lot of concatenations where lot of single quotes and + symbols were required. Definately worth using template literal notations.