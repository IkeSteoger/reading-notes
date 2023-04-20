# 301 Reading 10

## In memory storage

### JavaScript Call Stack

>What is a ‘call’?
>>Function Invocation

>How many ‘calls’ can happen at once?
>>Call stacks only do one call at a time but can make multiple calls

>What does LIFO mean?
>>Last In, First Out

>Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
>>`function firstFunc(){}`
>>`function secondFunc(){ firstFunction(); }`
>>`secondFunc();`

>What causes a Stack Overflow?
>>It occurs when there is a recursive function (a function calling itself with no endpoint)

### JavaScript error messages

>What is a ‘reference error’?
>>This is using a variable that is not yet declared or is declared improperly.

>What is a ‘syntax error’?
>>Occurs when you have something that cannot be parsed in terms of syntax, like parsing an invalid object with `JSON.parse` (codeburst.io)

>What is a ‘range error’?
>>Manipulating an object with some kind of length and giving it an invalid length

>What is a ‘type error’?
>>This is when you have incorrect type (string, number, etc) and the function is incompatible.

>What is a breakpoint?
>>It stops the code from running until code is continued, often by using `debugger`

>What does the word ‘debugger’ do in your code?
>>Creates breakpoints for you to test your code properly
