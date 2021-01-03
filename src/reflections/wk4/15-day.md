# Day 15
__12/21/20__

## What are some of the signs and causes of "Callback Hell"?
Some signs or causes include poor coding practices, such as not naming functions or having functions all over the place. Essentially code that is difficult to read can cause Callback Hell.
## What does asynchronous mean and how are callbacks involved?
"Asynchronous" means that it will happen in the future or that the code will take some time to accomplish. Callbacks come into play when working with input/output such as downloading a file.
## Summarize the 3 ways to avoid/fix "Callback Hell"
"Keeping code shallow" is the first way to avoid/fix Callback Hell. It's important to name functions opposed to having anonymous functions floating around. Also, we can rely on "function hoisting" so we're able to move defined functions to the bottom of the file to help organize the code.
"Modularize" is essentially the act of creating libraries for code that can be reused anywhere and doesn't require duplicating code everytime we want to use it. We can create the code in one file, export the file, and import it for use wherever we see fit.
"Handle every single error" is about always expecting an error because we never know when/where they will occur. It's about not ignoring our errors (because they will happen) but planning ahead as if we expect them to happen. 