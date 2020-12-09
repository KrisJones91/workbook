# Day 7
__12/8/2020__

## What are 3 ways to syntactically write a function? What are the differences in how the function acts(if any)?
Three ways to write a function are Function Declaration, Function Expression, and Arrow Functions.
Function Declarations are hoisted, allowing them to be used before they are defined, whereas, Function Expressions are NOT hoisted and unable to be used before they are defined. Arrow Functions don't require you to write "function()" and also don't require you to write "return" but act the same as Function Expressions (just shorter). 

## What is the difference between Parameters and Arguments?
Parameters are the names used to define a function. Arguments are values used when invoking a function.

## What are higher order functions? Plus examples...
Higher Order Functions are functions that accept other functions as parameters. They are also capable of returning a function.
Example 1: function as parameter...
function dog(pet){
pet(); 
}
Example 2; function to return...
function barkTimes(){
const bark = Math.floor(Math.random() * 3) + 1
}
dog(bark);