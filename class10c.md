
# The JavaScript Call Stack 

_________________________________________

![cd](https://cdn-media-1.freecodecamp.org/images/QgR2uIk7tW0YNz0Xm8g0jAPeRFI0e4sCejsv)

## What is a ‘call’?
 is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).

## How many ‘calls’ can happen at once?
once each time
## What does LIFO mean?
last in first in
## Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
function firstFunction(){
  throw new Error('Stack Trace Error');
}

function secondFunction(){
  firstFunction();
}

function thirdFunction(){
  secondFunction();
}

thirdFunction();
## What causes a Stack Overflow?

its happened when a dunction that calls itself without an exit point

___________________________________________________________

# JavaScript error messages

## What is a ‘refrence error’?
use variable not declared

## What is a ‘syntax error’?
sth cant be parsed in terms of syntax

## What is a ‘range error’?
manipulation an obj with some kind of lenght and give it an invalid length


## What is a ‘tyep error’?
when the types you are typing to use are not the same


## What is a breakpoint?
is to select a line so will be able to see what was happened before that point and can try the next lines


## What does the word ‘debugger’ do in your code?
the process of detecting and removing of existing and potential errors


