# Ex.No:1(A) INTRODUCTION TO JAVA PROGRAMMING, DATA TYPES, VARIABLES AND OPERATORS

## QUESTION:

Write a Java program to demonstrate the use of variables and different operators.

## AIM:

To write a Java program that uses different assignment, arithmetic, bitwise, and shift operators to modify a value step by step.

## ALGORITHM:

1.	Start the program.

2.Read an integer input from the user.

3.Display the initial value.

4.Apply various assignment operators (+=, -=, *=, /=, %=) directly inside print statements.

5.Apply bitwise operators (|=, &=, ^=) to modify the value.

6.Apply shift operators (<<= and >>=).

7.Display and print the result after each operation.

8.End the program.

## PROGRAM:
 ```
/*
Program to implement variables and Operators using Java
Developed by: DHARSHAN D
RegisterNumber: 212223230045 

import java.util.*;
public class Main{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        int p=sc.nextInt();
        System.out.println("Initial Power = "+p);
        System.out.println("After Door 1 (+= 5): "+(p+=5));
        System.out.println("After Door 2 (-= 3): "+(p-=3));
        System.out.println("After Door 3 (*= 2): "+(p*=2));
        System.out.println("After Door 4 (/= 4): "+(p/=4));
        System.out.println("After Door 5 (%= 3): "+(p%=3));
        System.out.println("After Door 6 (|= 2): "+(p|=2));
        System.out.println("After Door 7 (&= 7): "+(p&=7));
        System.out.println("After Door 8 (^= 4): "+(p^=4));
        System.out.println("After Door 9 (<<= 1): "+(p<<=1));
        System.out.println("After Door 10 (>>= 1): "+(p>>=1));
        System.out.println("Final Power = "+p);
        sc.close();
    }
}
*/
```

## OUTPUT:

<img width="782" height="770" alt="image" src="https://github.com/user-attachments/assets/59eec453-5d0a-4806-a1da-9c79d172bcea" />

## RESULT:

Thus, the Java program to demonstrate variables and different types of operators was executed successfully.





