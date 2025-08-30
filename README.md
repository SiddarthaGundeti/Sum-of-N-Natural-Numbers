# Sum-of-N-Natural-Numbers

Input: 6

Output: 21

Question: Sum of N Natural Numbers

Write a program that reads a number N and prints the sum of N Natural Numbers.

Input:
The input will be a single line containing an integer representing N.

Output:
The output should be a single line containing an integer that is the sum of N Natural Numbers.

Explanation:
For example, if the given number is N = 6,

The numbers from 1 to 6 are 1, 2, 3, 4, 5 and 6.
The sum of the numbers is 21. (1 + 2 + 3 + 4 + 5 + 6 = 21)
Approach
To find the sum of N natural numbers, we will follow these steps:

Read the input number N.

Initialize a counter variable and a sum variable.

Use a loop to add each number from 1 to N to the sum variable.

Print the sum variable.

Step-by-Step Explanation

Step 1: Read the input number

First, we need to read the input number N. We can use the input() function to read the input and int() to convert it into an integer.

Step 2: Initialize variables

Next, we need to initialize two variables:

counter: This variable will help us keep track of the current number in the loop.
sum_of_numbers: This variable will store the sum of the natural numbers.

Step 3: Calculate the sum of N natural numbers

Now, we will use a while loop to add each number from 1 to N to the sum_of_numbers variable. The loop will run until the counter is less than number.

Inside the loop, we will:

Increment the counter by 1.
Add the counter value to the sum_of_numbers.
