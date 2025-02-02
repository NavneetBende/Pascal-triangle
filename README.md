Pascal triangle
First we know about the pascal triangle what is this and how we design this triangle in general;

Pascal triangle is the set of numbers arranged in the form of triangle.

Each number in the row is the sum of the left number and right number on the above row. if a number is missing in the above row, it is assumed to be 0. the first row starts with number 1. 

pascal triangle
Write a program to print the following pattern
Enter the number of row 5
    1
   1 1
  1 2 1
 1 3 3 1
1 4 6 4 1
Working
Step1- Take number of rows to be printed.

Step2- Make outer iteration from 0 to row times to print row.

Step3- Make inner iteration from o to row-i times to print space in the row.

Step4- Print single black space ” “.

Step5- Close inner loop.

Step6-  Make inner iteration from o to i times to print number.

Step7- Apply condition if j or i is 0 so print 1, otherwise calculate c as c=c*(i-j+1)/j.

Step8- Print c.

Step9- Stop.
