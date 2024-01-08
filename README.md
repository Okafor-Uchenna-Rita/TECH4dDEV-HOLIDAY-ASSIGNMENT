This is an assignment on python covering different areas like methods, list, loop,if statement, function . 
QUESTIONS
Software Development – List, Tuple
Python programming exercises
1. Write a program that finds the maximum value of the given list, assuming that the list
contains at least one element.
Try your program with the following array
2 4 7 4 23 5 1 4 8 9
2. Write a program that calculates the average value of the given list.
Try your program with the following list
4 7 1 5 11 53 12 46 84 23
3. Write a program that prints the given list of integers in reverse order.
Try your program with the following list
2 6 7 45 23 53 14 45 89 5
4. Write a program that accepts two lists of integers and prints true if each element in the first
list is less than the element at the same index in the second list. Your program should print
false if the lists are not the same length.
5. Write a program that accepts a list of integers and two indexes and swaps the elements at
those indexes
6. Write a program that accepts two lists of integers and prints a new list containing all
elements of the first list followed by all elements of the second.
7. Write a program that accepts a list of integers and an integer value as its parameters and
prints the last index at which the value occurs in the list. The program should print –1 if the
value is not found. For example, in the list [74, 85, 102, 99, 101, 85, 56], the last index of the
value 85 is 5.
8. Write a program that prints the range of values in a list of integers. The range is defined as 1
more than the difference between the maximum and minimum values in the list. For
example, if a list contains the values [36, 12, 25, 19, 46, 31, 22], the program should return
35. You may assume that the list has at least one element.
9. Write a program that accepts a list of integers, a minimum value, and a maximum value and
prints the count of how many elements from the list fall between the minimum and
maximum (inclusive). For example, in the list [14, 1, 22, 17, 36, 7, -43, 5], for minimum value
4 and maximum value 17, there are four elements whose values fall between 4 and 17.
10. Write a program that accepts a list of real numbers and prints true if the list is in sorted
(nondecreasing) order and false otherwise. For example, if lists named list1 and list2 store
[16.1, 12.3, 22.2, 14.4] and [1.5, 4.3, 7.0, 19.5, 25.1, 46.2] respectively, the program should
print false for list1 and true for list2 respectively. Assume the list has at least one element. A
one-element list is sorted.
     
          Python programming exercises
1. Write a program to produce the following output using for loop
+----+
\ /
/ \
\ /
/ \
\ /
/ \
+----+
2. Write a program to produce the following output using for loop
**********
**********
**********
**********
**********
3. Complete the code for the following for loop:
for in range(1,7):
 //your code here
so that it prints the following numbers, one per line:
a) 1 b) 2 c) 4 d) 30 e) -7 f) 97 g) -4
2 4 19 20 -3 94 14
3 6 34 10 1 91 32
4 8 49 0 5 88 50
5 10 64 -10 9 85 68
6 12 79 -20 13 82 86
4. Write a program to produce the following output using for loops. Then
use a class constant to make it possible to change the number of lines in
the figure.
1
22
333
4444
55555
666666
7777777
5. Write a method named pay that accepts two parameters: a real number
for a TA's salary, and an integer for the number of hours the TA worked
this week. The method should return how much money to pay the TA.
For example, the call
pay(5.50, 6)
should return
33.0.
The TA should receive "overtime" pay of 1 ½ normal salary for any hours
above 8. For example, the call pay(4.00, 11) should return (4.00 *
8) + (6.00 * 3) or 50.0.
6. Consider the following method for converting milliseconds into days:
// converts milliseconds to days
def toDays(millis):
 return millis / 1000.0 / 60.0 / 60.0 / 24.0
Write a similar method named area that takes as a parameter the radius of
a circle and that returns the area of the circle. For example, the call
area(2.0);
should return
12.566370614359172.
Recall that area can be computed as π times the radius squared and that
Python has a constant called math.pi
7. Copy and paste the following code into pythons IDLE script
environment.
 low = 1
 high = 1001
 sum = 0
 for i in range(low,high):
 sum += i

 print("sum = " , sum)

Modify the code to use a input to prompt the user for the values of low
and high. Below is a sample execution in which the user asks for the same
values as in the original program (1 through 1000):
low? 1
high? 1001
sum = 500500
Below is an execution with different values for low and high:
low? 300
high? 5298
sum = 13986903
You should exactly reproduce this format.
8. Write a program using while loop that prompts the user for numbers until
the user types 0, then outputs their sum.
9. Write a program using while loop that prompts the user for numbers until
the user types -1, then outputs their sum.
10.Write a method named repl that accepts a String and a number of
repetitions as parameters and returns the String concatenated that many
times. For example, the call repl("hello", 3) returns "hellohellohello".
If the number of repetitions is 0 or less, an empty string is returned.
11.Write a method called printRange that accepts two integers as arguments and
prints the sequence of numbers between the two arguments, separated by
spaces. Print an increasing sequence if the first argument is smaller than
the second; otherwise, print a decreasing sequence. If the two numbers
are the same, that number should be printed by itself. Here are some
sample calls to printRange:
printRange(2, 7)
printRange(19, 11)
printRange(5, 5)
The output produced should be the following:
2 3 4 5 6 7
19 18 17 16 15 14 13 12 11
5
12.Write a method named smallestLargest that asks the user to enter numbers,
then prints the smallest and largest of all the numbers typed in by the
user. You may assume the user enters a valid number greater than 0 for
the number of numbers to read. Here is an example dialogue:
How many numbers do you want to enter? 4
Number 1: 5
Number 2: 11
Number 3: -2
Number 4: 3
Smallest = -2
Largest = 11
13.Write a method called printAverage that uses a sentinel loop to
repeatedly prompt the user for numbers. Once the user types any number
less than zero, the method should display the average of all nonnegative
numbers typed. Display the average as a double. Here is a sample
dialogue with the user:
Type a number: 7
Type a number: 4
Type a number: 16
Type a number: –4
Average was 9.0
If the first number that the user types is negative, do not print an average:
Type a number: –2
14.Write a method named numUnique that takes three integers as parameters
and returns the number of unique integers among the three. For example,
the call numUnique(18, 3, 4) should return 3 because the parameters
have three different values. By contrast, the call numUnique(6, 7, 6)
should return 2 because there are only two unique numbers among the
three parameters: 6 and 7.
15.A Random object generates pseudo-random numbers. Find out how to
use the Random class and write a program that simulates rolling of two 6-
sided dice until their combined result comes up as 7. One possible output
can be seen as below:
 2 + 4 = 6
3 + 5 = 8
5 + 6 = 11
1 + 1 = 2
4 + 3 = 7
You won after 5 tries!
