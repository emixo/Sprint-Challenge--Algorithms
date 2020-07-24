#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)Run time complexity is O(n) Linear, There's a single while loop that iterates N number of times and it increases depending on the value of N.


b)Run time complexity is O(n ^ 2) Quadratic, There's 2 loops(nested loops) that increases the runtime complexity 


c)Run time complexity is O(n) Linear, In this function, it is calling itself using recursion which will cause the function to loop  itself N number of times which increases depending on the value of N

## Exercise II


To solve this problem we need to use a simply binary search algorithm. First, we need to find out where the mid point is. If we drop the egg at middle point of the building and it breaks, we go lower. However, if it doesnt break then we ignore the other levels and begin to look at the top levels. Since this is a binary search algorithm, the runtime complexity will be O(log n)