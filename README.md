# Grumpy Bookstore Owner

LeetCode Q # 1052.

There is a bookstore owner that has a store open for n minutes. Every minute, some number of customers enter the store. You are given an integer array customers of length n where customers[i] is the number of the customer that enters the store at the start of the ith minute and all those customers leave after the end of that minute.

On some minutes, the bookstore owner is grumpy. You are given a binary array grumpy where grumpy[i] is 1 if the bookstore owner is grumpy during the ith minute, and is 0 otherwise.
When the bookstore owner is grumpy, the customers of that minute are not satisfied, otherwise, they are satisfied.
The bookstore owner knows a secret technique to keep themselves not grumpy for minutes consecutive minutes, but can only use it once.
Return the maximum number of customers that can be satisfied throughout the day.

Example 1:

>Input: customers = [1,0,1,2,1,1,7,5], grumpy = [0,1,0,1,0,1,0,1], minutes = 3</br>
>Output: 16</br>
>Explanation: The bookstore owner keeps themselves not grumpy for the last 3 minutes. </br>
>The maximum number of customers that can be satisfied = 1 + 1 + 1 + 1 + 7 + 5 = 16.

Example 2:

>Input: customers = [1], grumpy = [0], minutes = 1</br>
>Output: 1

My Solution Analysis:

<div align = "center">

  ![image](https://github.com/xo-azeem/Grumpy-Bookstore-Owner-LeetCode/assets/171427226/87015880-d9c6-4b5f-9bb8-aa9d9956d480)

  Time complexity: O(n).</br>Space complexity: O(1).
</div>
