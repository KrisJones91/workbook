# Day 21
__1/12/21__

## What are the three types of relationships?
The three relationships are One-to-One, One-to-Many, and Many-to-Many. They describe relationships between entities.
## What are the benefits of the traditional "linking" of relationships instead of "embedding"?
When utilizing linking with One-to-Many, it is easier to return paginated comments and less likely to reach the maximum document size of 16MB. This is opposed to embedding where the array could grow larger than the 16MB size.
## What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it?
A factor in decision-making would be the management of the amount of items in a category of both N and M. You have to take into account the amount of relationships there are between items before building.