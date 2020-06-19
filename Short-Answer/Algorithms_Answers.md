#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)O(n) The run time increases at the same rate as n. 


b)O(n^2) Each value needs to be compared to all other values.


c)O(n) Runs recursively with one call each time, until it reaches 0.

## Exercise II

I would begin by dividing the building in half and test the top floor of the lower half. If the eggs do break, I would divide the upper half in half again, and repeat. Once the eggs stop breaking, I would divide the lower half of the most recent split in half, and continue until the "f" floor is identified.

This would be recursive O(n).
