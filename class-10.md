# Reading 10 summary

## JS CH. 10
JavaScript runs one line of code at a time and when it needs data from another function, it starts to stack the new functions with the current running function. Every type of error in the console will help lead you to the bug. For example, `Reference Error` occurs when the variable doesn't exist. Every browser shows errors differently. Always look in the developer console to see what is going on.

Handle your errors 'gracefully' by making `try`, `catch`, and `throw` statements. Or `console.log()` the heck out of your errors (always label your console logs so you know what you are looking at i.e efficiency).

`console.table()` is another way to show your errors if they are have to do with an object. Use debugger to be a pro and step through your code. Conditional breakpoints are cool, you can break the code if a variable doesn't meet a certain requirement.

Create `throw new error` messages on certain cases where your code could start using bad data. Make it meet certain requirements, or throw the error.
