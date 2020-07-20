#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) The answer to this question is O(1). I came up with this because no matter how big the input is the runtime will remain the same.


b) I believe the answer to this question is polynomial. Because the bigger the input the opertions grow at a much faster rate.


c) The answer to this question is O(n). The run time increases at the same rate as the input grows.

## Exercise II

Since we don't know what floor the eggs are breaking I would use a binary search to solve this problem. We could take the number of floors(n) and divide it by 2. Once we have the mid point we could drop the egg off the midpoint and see if it breaks. If it does break we could find the midpoint of the bottom half and repeat till we find the correct floor(recursion). If the egg didn't break we would just go to the upper part of the building and do the same thing. The runtime of this algorithm would be O(log n).
