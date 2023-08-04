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

[JavaScript error messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

What is a ‘reference error’?

A reference error is when use a variable that is not yet declared and this error occurs.

What is a ‘syntax error’?

A syntax error occurs when you have something that cannot be parsed in terms of syntax.

What is a ‘range error’?

A range error occurs when you try to manipulate an object with some kind of length and give it an invalid length.

What is a ‘type error’?
What is a breakpoint?
What does the word ‘debugger’ do in your code?
