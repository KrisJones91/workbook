# Day 23
__1/14/21__

## What is a virtual property?
They are document properties that behaviors can be overridden. They can be accessed by get and set.
## When might you use a virtual property?
We might use virtual properties when we want two properties to exist together as one. In the text the example is using the full name of a person opposed to just a first name or last name as they are originally separate properties.
## How do you search by a virtual properties value?
You can't because virtual properties only exist in the document that you created the virtual property in. MongoDb doesn't store or save your virtual properties, it stores your origanl properties only.
