# Day 22
__1/13/21__

## In simple terms what is a sub-document?
They are documents nested in other documents. Subdocuments can also be called "embedded documents".
## When might you use a sub-document?
We might use subdocs when there are more than one important factor to the parent. In the text example of Ryu's moves, he has more than one special move, each special move being a subdocument. The same could be done with my phone; each app being a subdocument.
## How do you add to a collection of sub-documents? What about editing them?
With a single subdoc you would: use findOne, change the name and save. With an array subdoc: use findOne, get the array, update the array and then save it. 