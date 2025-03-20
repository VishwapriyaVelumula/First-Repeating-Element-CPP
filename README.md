# First-Repeating-Element-CPP <br>
Find the first repeating element in the given array?<br>
** Problem Statement ** <br>
Given an array arr[], find the first repeating element. The element should occur more than once and the index of its first occurrence should be the smallest.<br>

Note:- The position you return should be according to 1-based indexing.<br>

Input Format<br>

The first line contains an integer n (size of the array).<br>
The second line contains n space-separated integers representing the elements of the array.<br>
Constraints<br>
1 <= n <= 10^5<br>
0<= array elements <= 10^6<br>
Output Format
<br>
Print the 1-based position of the first repeating element. If no element repeats, print -1.
<br>
Sample Input 0
<br>
7<br>
1 5 3 4 3 5 6
Sample Output 0
<br>
2
Explanation 0
<br<
5 appears twice and its first appearance is at index 2 which is less than 3 whose first the occurring index is 3.
<br>
#SOLUTION#
Here we are using a set data type ---> which doesn't take any duplicate values!
We are traversing array from left to right, and at the same time inserting the unique elements in to the set
If we find any repeated element we are updating the index variable which has been created and assaigned as -2 for storing the result by the current index(i).
