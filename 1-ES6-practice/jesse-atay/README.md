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

I needed to convert const to let in all places where the value of the variable was changed directly. For example, clickCount, because the value changed directly with each new assignment. Also, allProducts had to be converted to let, because even though it works as const when holding values, it throws an error when being pulled out of local storage because of the need to be reassigned using JSON.parse. The pattern that seems to be present is that variables that are not changed are constant, which is probably why const is used to declare them as an easier syntax read. Const can be an array, with items added, but cannot be assigned a new array. Let on the other hand was used more in block scope, local to specific functions or within conditionals, or values that needed to be reassigned.

---

##### How did it go with making the adaptation from concatenations to template literal notation? Do you think you'll mostly use template literal notation from now on?

The adaptation went fine. Actually, I was using template literals in 201 as well. That's because during the prework I was doing other tutorials and ran into the Code Academy instruction for template literals. I found them to be a much easier way to read and concatenate strings. When I try to to it the older way I'm constantly getting lost or missing spaces in the strings. Template literals just make life easier. 
