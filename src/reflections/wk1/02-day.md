# Day 2
__12/1/2020__

## Psuedo-Class. What is it and what common ones might we use?
    Psuedo-Class is used to define an elements special state in CSS.
    Psuedo-classes are commonly used to style an element for when a user moves their mouse over that element. We can also use psuedo-classes to style visited and unvisited links differently, as well as bring an element to focus.
    ":Hover" is a very common psuedoclass we will use often.
## Specificity. What is it and how might it benefit you?
    Specificity is something that is built into CSS to help in determining the relevent property values to apply when coding. 
    In some cases we may target the same element and property of this element but wish to assign different values to each. 
    Specificity helps this by determining which rules should be applied in the event that you do this.
## What problems might we run into if over-utilizing the !important feature?
    !important is a declaration that overrides other declarations.
    When we write in CSS it reads from top to bottom. Therefore, writing !important at the bottom would override the above code.
    If !important is used too often in it could override all of our style declarations, showing up where it may not be intended.