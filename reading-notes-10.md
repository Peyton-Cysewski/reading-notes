# Reading Notes 10

## Understanding JavaScript

When JavaScript code is read, it creates a 'stack' of the code that needs to be processed. If a function is called, then that function code is referenced and placed at the top of the stack. Beacause code is always read from top down, this ensures that it all works out. Understanding this 'order of operations' and the scope of variables will make writing executable code much easier.

## Errors

If code generates an error, then JavaScript will throw an exception and then check if there is any exception-handling code. The error objects that JavaScript spits out help diagnose what the problem is as well as in what line of code the error happened at.

## Debugging

The first order of debugging is identifying WHERE the problem is. The next step is identifying WHAT the problem is. The browser dev tools are very helpful for this situation. The console is where the error objects can be found. Using the console.log() method can be used to look at data at any checkpoints you specify.
- console.info() shares info object
- console.warn() share warning object
- console.error() shares an error object
- console.group() and console.groupEnd() groups all the console functions together.
Console data can also be written in tables if desired with console.table(). It an also check assertions and if a specific condition is met with console.assert.

Using breakpoints allows code to be executed up to a certain point. This can be done by in the console and loooking at the js source and placing a breakpoint at a specific line number. If multiple breakpoints exist, you can step through them or even one line at a time to help identify problems. Conditional breakpoints also exist. Alternately, writing 'debugger' into code will make a manual breakpoint. Only use these for debugging and take them out before a live page is produced.

## Exceptions

To handle errors, use the try, catch, and finally method. This will try a code block, run a different code block if there is an exception, and if that still doesn't work, then finally will execute a code block no matter the instance.

## Throwing Errors

You can manually throw your own errors if you are expecting a situation that could potentially break the code.




#### [Home](README.md)