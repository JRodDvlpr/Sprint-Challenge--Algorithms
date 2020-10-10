#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) 0(n), because inside the while loop we are adding the iterator by n times, it should be 0(n) since it is being mutiplied in each iteration.


b) 0(n^2). This is a nested while loop and the runtime does curve as the numbers are getting larger. It can be 0(n log n) if we consider the fact the loop is being run n times.


c)0(n). This recursive function is calling itself n times. We start at n and then subtract every recursive call to 0 

## Exercise II

d) If we want to minimize the amount of dropped eggs to be broken. We can start from the lowest floor and we would iterate through each nth floor until 1 egg breaks. Which is the runtime complexity of 0(n).

If we are are trying to limit the amount of eggs dropped and the amount of eggs that get broken as well. Then a binary search would be best. 

If the eggs does not break, then we would discard the bottom and drop from the middle and top half of the building. Repeat the process until we get the results (egg broken)

If the egg does indeed break, then we can discard the the top and start from that middle and bottom half of the building. Repeat the process until we get the results (egg broken)

This is a runtime complexity of 0(log n) its the quickest and best solution for this problem.



