# Day 11
__12/14/20__

## What problem does using exports solve?
Exporting allows modules to be accessible to other parts of code. Otherwise the module is private/defaulted to strict mode.
## How does "export" differ from "export default"?
We can export each module individually, in otherwords, we can export multiple times. However, we can only default export once throughout a single document. 
## What is a benefit of using the Module System?
Debugging is easier in the Module System. Also, you can create aliases to help with issues of naming functions or classes. By using aliases, you could use the same name for a function for two different modules and essentially not have any conflicts between them.