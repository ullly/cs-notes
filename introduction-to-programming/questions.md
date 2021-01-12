---
title: Introduction to Programming Questions
author: by Ultan
---

 

Introduction
------------

 

Some questions from, or relevant to, the course.

 

Questions
---------

 

**Prime Mirrors**

 

Write a program to find all the integers that satisfy the following conditions:

-   Number x is the nth prime number (e.g. 37 is the 12th prime number). Use the
    sieve of Eratosthenes algorithm

-   The mirror of x is the (mirror of n)th prime number (e.g. 73 is the 21st
    prime number)

 

Your program should provide and use at least the following functions/methods:

-   isPrime() which determines if a passed number is prime or not

-   nthPrime() which takes a number n, returns the nth prime number. (2

    is the 1st prime number, 3 is the 2nd prime number, 5 is the 3rd prime

    number, etc.)

-   findNextPrime() which takes a prime number and returns the next

    greatest prime number

-   mirror() which returns the mirror number of a passed number (e.g. if

    given 23456 then it will return 65432)

     

**Matrices**

 

Write a Java class Matrix whose instances represent 2D matrices of doubles. Your
class should provide the following methods:

 

-   A constructor method which takes a 2D array of doubles and initialises the
    matrix from this

-   An averageValue method which returns the average value of the cells in the
    matrix

-   A normalise method which returns a new matrix where the sum of the elements
    in the matrix is 1.0

-   An add method which takes two matrix objects and returns a new matrix object
    whose cells are the sum of the corresponding cells in the passed matrix
    objects

 

**Short Questions**

 

Note that questions may contain errors. If they do contain errors. State the
error as your answer

 

*What is the value of result?*

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
int m = 4; int n = 6; int p = 7; int result = 10; result += m * n – p; 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

 

*What is the value of result?*

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
int result = 11; 
if (result < 0) 
    result -= 2 * result; 
else if (result % 2 == 1) 
    result += 1;
else result *= result; 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

 

*What is the value of result?*

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
int value = 8; int result = 0; 
switch (value) {
    case 1: 
        result += value / 2; 
        break; 
    case 4: 
        result -= value; 
        break; 
    case 8: 
        result *= value; 
        break; 
    default: 
        result /= value % 2; 
        break; 
} 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

 

*What is the value of result?*

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
int result = 0;
for (int count = 0; (count < 5); count++) 
    result += count; 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

 

*What is the value of result?*

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
int result = 0; int x = 23; int y = 3; int z = 0; 
while (z < x) { 
    z += y; 
    result++; 
} 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

 

*What is the value of result?*

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
int result = 0; int x = 5; int y = 3; 
do { 
    result = result + y; 
} while (x-- > 0); 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

 

*What is the value of result?*

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
int function(int number) { 
    if (number <= 1) 
        return 1; 
    else return (number * function(number - 1)); 
} 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

 

*What is the value of result?*

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
final int[] numbers = { 1, 45, 23, 19, 20 }; 
int result = numbers[1] + numbers[4]; 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

 

*Given the following function definitions, what will be stored in myNumbers if
we execute: int[] myNumbers = {1, 2, 3, 4, 5}; function(myNumbers);?*

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
void function(int[] numbers){ 
    for (int index = 0; index < numbers.length / 2; index++) 
    {
        int temp = numbers[numbers.length - index - 1]; 
        numbers[numbers.length - index - 1] = numbers[index] = temp; 
    } 
} 
numbers[index]; 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

 

*Which one of the following member data declarations (as part of a class
definition) could be public?*

1.  `static final int DAYS_IN_THE_YEAR = 365;`

2.  `int mAccountNumber;`

3.  `double mAccountBalance;`

4.  `String mAccountName;`

5.  `static int mLastAccountNumberUsed = 0;`

 

*Which of the following pieces of member data should be declared as*

*static (and be initialised in the class definition)?*

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
class Time { 
    int HOURS_PER_DAY;
    int MINUTES_PER_HOUR;
    int mNumberOfTimeObjectsCreatedToDate; 
    int mHours;
    int mMinutes; 
}
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

 

1.  `HOURS_PER_DAY` and `MINUTES_PER_HOUR` should be static

2.  `mNumberOfTimeObjectsCreatedToDate`, `HOURS_PER_DAY` and `MINUTES_PER_HOUR`
    should be static

3.  `mHours` and `mMinutes` should be static

4.  `mHour`, `mMinutes`, `HOURS_PER_DAY` and `MINUTES_PER_HOUR` should be static

5.  `mNumberOfTimeObjectsCreatedToDate`, `mHours` and `mMinutes` should be
    static

 

*Which of the following method definitions (as part of the Number class) would
be invoked by this code*?

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Number myNumber = new Number(59,23);
Number resultNumber = Number.add(myNumber,40); 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

1.  `public static Number add(Number num1, Number num2)`

2.  `public static Number add(Number num1, int num2)`

3.  `public void add(Number num)`

4.  `public void add(int num)`

5.  `public static Number add( int num1, int num2)`

 

*Given the following method definition, what will be stored in result if we
execute int result = fun(1234);?*

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
int fun(int n) {
    if (n <= 9) return n;
    return function(n / 10) + (n % 10); 
} // end method fun 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

 

*Given the following code segment. You may assume that list is an array of
integers. What will be store in sum?*

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
int i = 0; int sum = 0; 
while (i <= list.length) { 
    sum += list[i]; 
    i++;
} // end while loop 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

 

*The following program segment is intended to find the index of the last
negative integer in the integer array list. Will the segment work as intended?
Elaborate*

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
int i = list.length; 
while (list[--i] >= 0){}
location = i; 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

 

*Consider the following class definition. In some other class, to call the
method fun from C class, what you would write?*

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public class C {
    public static void fun() { 
        System.out.println(“I am fun in C”); } // end method fun 
} // end class C 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

 

*What is m.length in the following code segment?*

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Object[][] m = new Object[2][]; 
m[0] = new Object[3];
m[1] = new Object[4]; 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

 

*Consider the following method. Is the method correct? If so, what does the
method return?*

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public int fun(int a, int b, int c) { 
    if (a < b && a < c) return a;
    if (b < a && b < c) return b;
    if (c < a && c < b) return c; 
} // end method fun 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

 

*What is the value of fun(2,3)?*

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public int fun(int a, int b){
    if (b == 1) return a;
    else return a + fun(a, b – 1); 
} // end method fun 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

 

**Other Questions**

 

-   Write a hello world program

-   Implement the fizz buzz game

-   Implement a program that checks if a year is a leap year

-   Implement a program that compute the factorial of a number

-   Write a program that simulates a coin toss

-   Write a program to reverse the order of digits of some number

-   Write a program which, given two integers, will compute the GCD

-   Write a program to compute a particular term in the Fibonacci sequence

 

**Theory​​ Questions**

 

-   What is the precedence of the math operators: add, subtract, multiply,
    divide, modulo?

-   What is the syntax for if statements, for loops, while loops, do while
    loops, exception handling, switch statements, functions, 1D arrays, 2D
    arrays and ArrayList?

-   What are the primitive data types?

-   What is the range on an int?

-   How many possible doubles are there?

-   Show the skeleton code for creating a class and creating an object of that
    class

-   Referring to Java classes, what is an instance variable, method and
    constructor?

-   What is an access modifier? Give examples

-   Give an example of an enum

-   What is a static subroutine?

-   What is a static variable?

-   What is inheritance?

-   What is polymorphism?

-   What is an abstract class?

-   What is an abstract method?

-   What is an interface? Give example code

-   What is a default method?

-   Can you construct an object from an interface?
