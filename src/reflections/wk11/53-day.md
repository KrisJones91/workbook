# Day 53
__2/22/20__

## What does Inheritance accomplish for us in C#?
Inheritance allows us to reuse, extend and modify code from other classes. We do this with our Controllers when we inherate from ControllerBase which allows us to utilize the items within that Controller. We also do this from model to model. It allows us to reuse code.

## How does Member inheritance work in C#? Does a class inherit all members of the base class?
Member inheritance is when a child class inherits properties from it's parent class. Although a lot can be inherited from a base class, not all members of a class can be inherited. For example the constructor cannot be inherited.

## How does accessibility affect inheritance?
Visibiliy of members affects it's accessibility. For Private Members, inheritance can be difficult due to the level of protection. In this case they can only be inherited by the child when it is nested in the parent.

## Afternoon Challenge
https://krisjones91.github.io/vacay/