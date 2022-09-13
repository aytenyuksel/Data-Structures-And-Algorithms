[22,27,16,2,18,9]

##Question 1 - Insertion Sort Steps

Step 1. Find the smallest number and swap the first number on array       = [2,27,16,22,18,9]
Step 2. Find the next smallest number and swap the second number on array = [2,9,16,22,18,27]
Step 3. Find the next smallest number, and don't touch                    = [2,9,16,22,18,27]
Step 4. Find the next smallest number and swap the fourth number on array = [2,9,16,18,22,27]
Step 5. Find the next smallest number and don't touch                     = [2,9,16,18,22,27]

##Question 2 - Big O Notation

We changed the location of one number at each step. Every time we swaped, there is one less number left. 

Rule is;
n + (n-1) + (n-2) + .... + 1
n*(n+1)/2
n^2+n/2

n^2 makes bigger changes more than n/2

Big O notation is O(n^2)

##Question 3 - 18 is example of avarage case. Because it is in the middle of array.

[7,3,5,8,2,9,4,15,6]

##Question 4 - First 4 steps/Insertion Sort

Step 1. Find the smallest number and swap the first number on array       = [2,3,5,8,7,9,4,15,6]
Step 2. Find the next smallest number, and don't touch                    = [2,3,4,8,7,9,5,15,6]
Step 3. Find the next smallest number and swap the third number on array  = [2,3,4,8,2,9,5,15,6]
Step 4. Find the next smallest number and swap the fourth number on array = [2,3,4,5,2,9,8,15,6]
