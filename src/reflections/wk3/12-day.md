# Day 12
__12/15/20__

## What is the purpose of Encapsulation?
The purpose of Encapsulation is to keep private data private. To keep that data private, we bundle data and methods that act on that data to prevent access from outside of that bundle.
## What were some of the problems with closures and the underscore prefix?
Some developers use the underscore prefix method instead of using closures to indicate a private property or method. This could create problems with new developers not fully understanding the purpose of the underscore prefix and using it anyway. Also, using only the underscore method leaves you prone to relying on others knowing what it means and that you intend on that specific thing being private.
## How do we create private variables in a ES6 Class? Why would you do this?
We create a Proxy Object to create private variables. These are used to limit the accessibility of the properties we choose.