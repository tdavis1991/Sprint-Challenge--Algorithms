#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) The answer to this question is O(n). The opetions grow with the input.


b) I think the answer to this question is polynomial. This seemed like the correct runtime based on how the sum variable was growing in that function.


c) The answer to this question is O(n) like question a.

## Exercise II

Since we don't know what floor the eggs are breaking I would use a binary search to solve this problem. We could take the number of floors(n) and divide it by 2. Once we have the mid point we could drop the egg off the midpoint and see if it breaks. If it does break we could find the midpoint of the bottom half and repeat till we find the correct floor(recursion). If the egg didn't break we would just go to the upper part of the building and do the same thing. The runtime of this algorithm would be O(log n).

