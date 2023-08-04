[Understanding the JavaScript Call Stack](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4)

What is a ‘call’?

The call stack is primarily used for function invocation (call)

How many ‘calls’ can happen at once?

A single, function(s) execution, is done, one at a time, from top to bottom

What does LIFO mean?

Lifo means: Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

function firstFunction(){
  throw new Error('Stack Trace Error');
}

What causes a Stack Overflow?

A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point.
