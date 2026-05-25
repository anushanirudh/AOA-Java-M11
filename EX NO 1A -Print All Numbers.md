
# EX 1A Print All Numbers 
## DATE: 25.05.26
## AIM:
To Write a Java program that takes an integer input N from the user and prints all the numbers from 1 to N, separated by spaces, on a single line..

## Algorithm
1. Start
2. Input an integer N from the user.
3. Initialize a counter variable i = 1.
4. Repeat while i ≤ N:
5. Print i followed by a space.
6. Increment i by 1.  

## Program:
```
/*
Program to implement Reverse a String
Developed by: R Anirudh
Register Number:  212223230016
*/

import java.util.*;
public class Main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        for(int i=1;i<=n;i++){
            System.out.print(i+" ");
        }
    }
}
```

## Output:
<img width="529" height="166" alt="image" src="https://github.com/user-attachments/assets/d17559a8-6418-4f8d-8921-185e3d7a2176" />



## Result:
The program successfully print all the numbers from 1 to N. 
