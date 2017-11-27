# 1-ES6-practice

## Feature Tasks

Follow these instructions carefully and in order.

1. Open the HTML file in the browser to ensure that it works. DONE
2. Turn all `var` variable declarations into `let`. DONE
3. After you do, there will be one error. Find that line in the code, delete that line and respond to the adjacent TODO item. DONE
4. Return to the browser to ensure that the code works again. DONE
5. **Save the code, and do a Git "add" and "commit".** DONE
6. Now, in the code, convert all `let` variable declarations into `const`. DONE
7. Bugs will erupt everywhere. Debug by using the error messages in the browser console, turning `const` declarations back into `let` where necessary. Expect there to be some back-and-forth between your code editor and your browser. DONE
8. When you think you have things working, clear local storage and reload the page to ensure that the code still works when starting from a totally clean state. DONE
9. **Save the code, and do a Git "add" and "commit".** DONE
10. Now find all concatenations in the code and convert them into template literal notation. DONE
11. Reload the browser to ensure that the code works as expected. DONE
12. **Save the code, and do a Git "add" and "commit".** DONE
13. Answer the following questions: DONE

---

##### Investigate how `let` and `const` are now used in the code. Where did you need to convert `const` into `let` to make the code work? Can you identify any patterns/similarities?

Const was fine and preferable anywhere that there did not need to be a reassignment. Let was needed in all the for loops, since i was being reassigned with every iteration of the for loop and const make. This also happened with a few declarations at the top of the code, where allProducts needed to be let since it was stringified for local storage, and where totalClicks needed to be let since it was being used as a counter that would be added to rather than staying constant throughout the entirety of the code. Use const everywhere possible to reduce accidental modification of a variable, and use let where const is not functional (which is for anything that will be reassigned/updated later in the code).

---

##### How did it go with making the adaptation from concatenations to template literal notation? Do you think you'll mostly use template literal notation from now on?

100%. I ran into plenty of problems with concatenations before and during the first week of 201 this caused me a lot of problems that were very easily remedied by one single character being added, so this visually feels much cleaner and less likely to create accidental bugs. It is also supported on every major browser so there's no real reason not to.
