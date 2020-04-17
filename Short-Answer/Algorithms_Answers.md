#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) The run time is O(n), and this is because:
    initially in the while loop, it can be seen as n^3
    then n is increased by n^2 in the next line meaning that eachtime the loop runs, a is also increased by n^2 --> f(n) = (n^3) / a + (n^2). if we remove a from the equation, the formula can be simplified to become f(n) = n, meaning the loop that takes in n has the biggest impact on runtime.
b) The run time is O(n^2), and this is because:
    The for loop is conducted over range(n) and then there is a while look which checks for "while j is less than n", so the formula becomes f(n) = n*n or n^2. Basically a loop would account for O(n) and since this is a nested loop, it becomes O(n^2).
c) The run time for this is O(log n) since this is a recursive function in which bunnies = n is used and its value decreases in each recursion.


## Exercise II


