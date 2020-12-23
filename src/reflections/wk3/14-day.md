# Day 14
__12/17/20__

## What problems does the Observer Pattern seek to solve?
The Observer Pattern attempts to solve the problem of synchronization between elements with similar data. The Pattern also helps with creating reusable code to solve problems that may occur later on down the road.
## What are the 3 mechanisms of the observer pattern?
The 3 mechanisms are the Subscribe Method, the Unsubscribe Method and the Broadcast Method. The Subscribe Method adds new observable events, the Unsubscribe Method removes observable events, and the Broadcast Method iterates through ALL events and executes them.
## Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With the knowledge, explain how the "magic" of the bcw-template uses these two concepts to manage and update the DOM.
The proxy objects in the bcw-template allow for privacy of certain aspect of our code. This being used in the template helps because it manages the accessibility of the object. The bcw-template utilizes the observer pattern by synchronizing multiple elements within the code to update the DOM and the proxy state works to prevent tampering with any code not intended to be changed.