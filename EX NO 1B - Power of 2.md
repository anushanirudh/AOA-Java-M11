
# EX 1B Power of 2
## DATE: 25.05.26
## AIM:
To write a Java program to for given constraints.Given an integer n, return true if it is a power of two. Otherwise, return false.

An integer n is a power of two, if there exists an integer x such that n == 2x.

## Algorithm
1. Start the program and import the Scanner class to take input from the user.
2. Read an integer n using the Scanner object.
3. Check if n is less than or equal to 0 — if true, return false.
4. Use the bitwise operation (n & (n - 1)) == 0 to check if n is a power of two.
5. Print true if the condition holds, otherwise print false.
 

## Program:
```java
/*
Program to implement Reverse a String
Developed by: R Anirudh
Register Number: 212223230016
*/

import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        if (n > 0 && ((n & (n - 1)) == 0)) {
            System.out.println("true");
        } else {
            System.out.println("false");
        }
    }
}
```

## Output:
<img width="519" height="211" alt="image" src="https://github.com/user-attachments/assets/d5d50ca2-e2e4-4d34-b7cd-e78e0348bec0" />



## Result:
The program successfully implemented and the expected output is verified.
