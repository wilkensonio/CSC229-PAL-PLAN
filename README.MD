# PAL Session Plan 2/15 and 2/16

## Introduction to For Loops:

- Explain the concept of iteration and its importance in programming.
- Introduce the for loop syntax in Java.
- Discuss the three components of a for loop: initialization, condition, and iteration.

## Basic For Loop:

- Show how to use a for loop to iterate a fixed number of times.
- Emphasize the syntax and the role of each component.
- Discuss how to declare and use loop variables within the loop body.

### Examples for Basic For Loop:

1. Print numbers from 1 to 5

   ```java
   for (int i = 1; i <= 5; i++) {
       System.out.println(i);
   }
   ```

2. Calculate the sum of numbers from 1 to 10

   ```java
   int sum = 0;
   for (int i = 1; i <= 10; i++) {
       sum += i;
   }
   System.out.println("Sum: " + sum);
   ```

3. Print characters of a string

   ```java
   String text = "Hello";
   for (int i = 0; i < text.length(); i++) {
       System.out.println(text.charAt(i));
   }
   ```

4. Calculate the factorial of a number

   ```java
   int n = 5;
   int factorial = 1;
   for (int i = 1; i <= n; i++) {
       factorial *= i;
   }
   System.out.println("Factorial of " + n + ": " + factorial);
   ```

## Enhance (For-Each) Loops:

1. Number of occurrences of targetChar

   ```java
   String text = "Hello, world!";
   char targetChar = 'l';

   int count = 0;
   for (char ch : text.toCharArray()) {
       if (ch == targetChar) {
           count++;
       }
   }
   ```
