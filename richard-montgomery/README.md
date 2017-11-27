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

As far as my understanding goes, let and const have block scope which means it's only scoped to the block it's in. Mm... let and const variables can only be declared once... although, let variables can be updated and const variables cannot... Mm... you can add to const variables though like an array and const variables are eternal. So uh... variables in for loop iterations, I changed to let so it can be updated... basically any time the variable needed to be updated, I changed the variables to let.

---

##### How did it go with making the adaptation from concatenations to template literal notation? Do you think you'll mostly use template literal notation from now on?

So... when I was reading about the literal notation, they were saying it's a more elegant way to concatenate... I don't know if dollar signs and brackets are really more elegant, but... I think I'll use it moving forward simply because using "+" does make the concatenated strings look choppy.
