# code to print fibonacci series
Steps that happens in the browser:
A prompt pops up to ask the user to enter a number 
User enters a number(n) to print the number of terms in fibonacci series(sum of 2 previous numbers) and clicks ok/enter

Steps that happens in the compiler:
As per the code, I have declared an array variable, 'fs' and initialized 2 variables: n1=0 and n2=1 and an empty variable 'nextTerm'.
when it enters the for loop, it checks for 'n' value and it compares with the for loop variable i. It has been initialized to 1.
a. when i=1 and 1<=8, condition is satisfied(1<8) and it enters into the for loop 
   It pushes 'n1' value into the array variable 'fs'. Now, fs = 0
   Then it adds n1(0) and n2(1) and stores it in nextTerm variable. Now, nextTerm = 1
   Then it assigns value of n2 to n1. Now, n1 = 1
   Then it assigns value of nextTerm to n2. Now, n2 = 1
   
b. It then iterates the value of i as per the for loop and then checks if 2<=8, condition is satisfied(2<8) and it enters into the for loop 
   It pushes 'n1' value into the array variable 'fs'. Now, fs = 1
   Then it adds n1(1) and n2(1) and stores it in nextTerm variable. Now, nextTerm = 2
   Then it assigns value of n2 to n1. Now, n1 = 1
   Then it assigns value of nextTerm to n2. Now, n2 = 2

c. It then iterates the value of i as per the for loop and then checks if 3<=8, condition is satisfied(3<8) and it enters into the for loop 
   It pushes 'n1' value into the array variable 'fs'. Now, fs = 1
   Then it adds n1(1) and n2(2) and stores it in nextTerm variable. Now, nextTerm = 3
   Then it assigns value of n2 to n1. Now, n1 = 2
   Then it assigns value of nextTerm to n2. Now, n2 = 3
   
d. It then iterates the value of i as per the for loop and then checks if 4<=8, condition is satisfied(4<8) and it enters into the for loop 
   It pushes 'n1' value into the array variable 'fs'. Now, fs = 2
   Then it adds n1(2) and n2(3) and stores it in nextTerm variable. Now, nextTerm = 5
   Then it assigns value of n2 to n1. Now, n1 = 3
   Then it assigns value of nextTerm to n2. Now, n2 = 5
   
e. It then iterates the value of i as per the for loop and then checks if 5<=8, condition is satisfied(5<8) and it enters into the for loop 
   It pushes 'n1' value into the array variable 'fs'. Now, fs = 3
   Then it adds n1(3) and n2(5) and stores it in nextTerm variable. Now, nextTerm = 8
   Then it assigns value of n2 to n1. Now, n1 = 5
   Then it assigns value of nextTerm to n2. Now, n2 = 8
   
f. It then iterates the value of i as per the for loop and then checks if 6<=8, condition is satisfied(6<8) and it enters into the for loop 
   It pushes 'n1' value into the array variable 'fs'. Now, fs = 5
   Then it adds n(5) and n2(8) and stores it in nextTerm variable. Now, nextTerm = 13
   Then it assigns value of n2 to n1. Now, n1 = 8
   Then it assigns value of nextTerm to n2. Now, n2 = 13
   
   
f. It then iterates the value of i as per the for loop and then checks if 7<=8, condition is satisfied(7<8) and it enters into the for loop 
   It pushes 'n1' value into the array variable 'fs'. Now, fs = 8
   Then it adds n(8) and n2(13) and stores it in nextTerm variable. Now, nextTerm = 21
   Then it assigns value of n2 to n1. Now, n1 = 13
   Then it assigns value of nextTerm to n2. Now, n2 = 21
   
   
f. It then iterates the value of i as per the for loop and then checks if 8<=8, condition is satisfied(8=8) and it enters into the for loop 
   It pushes 'n1' value into the array variable 'fs'. Now, fs = 13
   Then it adds n(13) and n2(21) and stores it in nextTerm variable. Now, nextTerm = 34
   Then it assigns value of n2 to n1. Now, n1 = 21
   Then it assigns value of nextTerm to n2. Now, n2 = 34
   
   It then iterates the value of i as per the for loop and then checks if 9<=8, condition is not satisfied and it comes out of the for loop and prints the fibonacci series as 0,1,1,2,3,5,8,13.
