Given a 2D array, find the maximum sum submatrix in it. For example, in the following 2D array, the maximum sum submatrix is highlighted with blue rectangle and sum of all elements in this submatrix is 29.

![image](https://github.com/230Souvik/Maximum_sum_rectangle_in_2D_matrix/assets/135532224/9ba9227b-326c-4513-9ab2-38ab3f082cb5)



This problem is mainly an extension of Largest Sum Contiguous Subarray for 1D array.  

The Naive Solution for this problem is to check every possible rectangle in the given 2D array. This solution requires 6 nested loops –  


4 for start and end coordinate of the 2 axis O(n4)
and 2 for the summation of the sub-matrix O(n2).
