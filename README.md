# Aim
To study and implement while loop control structures in Python by solving different problems such as number printing, factorial, Fibonacci series, palindrome checking, digit counting, list searching, and conditional iteration.

# Theory
A while loop is a control structure in Python that repeatedly executes a block of statements as long as a given condition remains true.
In a while loop, the condition is checked before executing the loop body. If the condition is true, the statements inside the loop are executed. After execution, the condition is checked again. This process continues until the condition becomes false.
The while loop is mainly used when the number of repetitions is not known in advance and execution depends on a condition.
Python provides loop control statements to modify execution:
Break statement terminates the loop immediately.
Continue statement skips the remaining part of the current iteration.
Else block executes when the loop finishes normally without break.
While loops are commonly used in counting operations, mathematical calculations, searching, validation, and repetitive processing tasks.

ALGORITHMS
# Program 1
Print values while condition is true

Step 1 Start

Step 2 Initialize variable i with value 1

Step 3 Check whether i is less than 5

Step 4 If condition is true print value of i

Step 5 Increase i by 1

Step 6 Repeat steps 3 to 5 until condition becomes false

Step 7 Stop

# Program 2
Print numbers from 1 to N
Step 1 Start
Step 2 Read value of n from user
Step 3 Initialize variable i with value 1
Step 4 Check whether i is less than or equal to n
Step 5 If true print value of i
Step 6 Increase i by 1
Step 7 Repeat steps 4 to 6 until condition becomes false
Step 8 Stop

# Program 3
Find factorial of a number
Step 1 Start
Step 2 Read number n from user
Step 3 Initialize fact with value 1
Step 4 Check whether n is greater than 0
Step 5 Multiply fact by n and store result in fact
Step 6 Decrease value of n by 1
Step 7 Repeat steps 4 to 6 until n becomes 0
Step 8 Display factorial value
Step 9 Stop

# Program 4
Generate Fibonacci series for N terms

Step 1 Start

Step 2 Read number of terms n

Step 3 Initialize first number a as 0

Step 4 Initialize second number b as 1

Step 5 Initialize counter i as 1

Step 6 Check whether i is less than or equal to n

Step 7 Print value of a

Step 8 Compute next term by adding a and b

Step 9 Assign value of b to a

Step 10 Assign result to b

Step 11 Increase counter i by 1

Step 12 Repeat steps 6 to 11 until condition becomes false

Step 13 Stop

# Program 5
Generate Fibonacci series up to a limit
Step 1 Start

Step 2 Read limit value from user

Step 3 Initialize a as 0

Step 4 Initialize b as 1

Step 5 Check whether a is less than or equal to limit

Step 6 Print value of a

Step 7 Compute next term by adding a and b

Step 8 Assign value of b to a

Step 9 Assign result to b

Step 10 Repeat steps 5 to 9 until condition becomes false

Step 11 Stop

# Program 6
Reverse a number
Step 1 Start

Step 2 Read number from user

Step 3 Initialize reverse value as 0

Step 4 Check whether number is greater than 0

Step 5 Find last digit using remainder operation

Step 6 Multiply reverse by 10 and add digit

Step 7 Remove last digit from number

Step 8 Repeat steps 4 to 7 until number becomes 0

Step 9 Display reversed number

Step 10 Stop

# Program 7
Check palindrome number
Step 1 Start

Step 2 Read number from user

Step 3 Store number in temporary variable

Step 4 Initialize reverse value as 0

Step 5 Check whether number is greater than 0

Step 6 Extract last digit

Step 7 Update reverse value

Step 8 Remove last digit from number

Step 9 Repeat steps 5 to 8 until number becomes 0

Step 10 Compare original number with reversed number

Step 11 If both are equal display palindrome

Step 12 Otherwise display not palindrome

Step 13 Stop

# Program 8
Check palindrome string using loop

Step 1 Start

Step 2 Read string from user

Step 3 Initialize start index as 0

Step 4 Initialize end index as length of string minus 1

Step 5 Assume string is palindrome

Step 6 Compare characters at start and end positions

Step 7 If characters are not equal mark not palindrome and stop checking

Step 8 Increase start index by 1

Step 9 Decrease end index by 1

Step 10 Repeat steps 6 to 9 while start index is less than end index

Step 11 Display result

Step 12 Stop

# Program 9
Count digits in a number

Step 1 Start

Step 2 Read number from user

Step 3 Initialize count as 0

Step 4 Check whether number is greater than 0

Step 5 Remove last digit from number

Step 6 Increase count by 1

Step 7 Repeat steps 4 to 6 until number becomes 0

Step 8 Display number of digits

Step 9 Stop
# Program 10
Search an element in a list

Step 1 Start

Step 2 Define list of elements

Step 3 Read search key from user

Step 4 Initialize index variable as 0

Step 5 Assume element is not found

Step 6 Check whether index is less than length of list

Step 7 Compare element at index with search key

Step 8 If equal display index and mark found

Step 9 If not equal increase index by 1

Step 10 Repeat steps 6 to 9 until element is found or list ends

Step 11 If element not found display message

Step 12 Stop

# Program 11
Print odd numbers from 1 to 10

Step 1 Start

Step 2 Initialize i as 0

Step 3 Check whether i is less than 10

Step 4 Increase i by 1

Step 5 Check whether i is divisible by 2

Step 6 If divisible skip printing

Step 7 Otherwise print i

Step 8 Repeat steps 3 to 7 until condition becomes false

Step 9 Stop

# CONCLUSION
The while loop provides a powerful method for performing repeated execution based on a condition. It is especially useful when the number of iterations is not predetermined. Through these programs, different applications of while loops such as counting, mathematical computation, sequence generation, searching, and logical comparison were implemented successfully. This experiment improves understanding of loop control and strengthens problem solving skills in Python programming.

