# console.log runs out of thread

console.log runs out of thread, meaning that if there is a value change somewhere in the stack, it could print out the value that changed.

e.g. 

x = 1
console.log(x)
x += 1

Simple example, but this could log 2 instead of 1. 
