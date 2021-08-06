## What is a ‘call’?
is primarily used for function invocation (call). Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous.

## How many ‘calls’ can happen at once?
one at a time, from top to bottom

## What does LIFO mean?
It means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

## Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
When a function is invoked (called), the function, its parameters, and variables are pushed into the call stack to form a stack frame. This stack frame is a memory location in the stack. The memory is cleared when the function returns as it is pop out of the stack.

![](https://cdn-media-1.freecodecamp.org/images/QgR2uIk7tW0YNz0Xm8g0jAPeRFI0e4sCejsv)


## What causes a Stack Overflow?
A stack overflow occurs when there is a recursive function

## Reference errors
This is as simple as when you try to use a variable that is not yet declared you get this type os errors.


## Syntax errors
I know it’s in the name of the errors, but like it says itself, this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

## Range errors
Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.

## Type errors
Like the name indicates, this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.
## breakpoint
The breakpoint can be achieved by putting a debugger statement in your code in the line you want to break.

## debugger means
The breakpoint can be achieved by putting a debugger statement in the code in the line you want to break. 