# Day 13
__12/16/20__

## What are the two common operations that we will set in the handler?
The two basic operations are "get" and "set". Using "get" on an object to get a value. Using "set" to set a new key to an object.
## What do you have to make sure you are doing with every "Get" to insure the value does not become "undefined"?
You have to make sure you are passing in two parameters to the "get" operation. The parameters are the object itself and the property within the object in which you want to access.
## What are some of the benefits of the proxy object that we are using in our structure for applications?
One benefit of creating a proxy of an object is that we can make properties in that object private. In doing this, we can set traps to prevent accessibility to those specific properties. All of this is highly beneficial in security of your code.