# Ex.No:1(C) LOOPING STATEMENT

## QUESTION:

Print Multiplication Table of a Number

## AIM:

To write a Java program that reads a number from the user and prints its multiplication table using a loop.

## ALGORITHM :

1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Initialize a loop counter from 1 to 10.
4. In each iteration, multiply the number with the counter and display the result.
5. End the loop and terminate the program.

## PROGRAM:
 ```
/*
Program to implement a Looping Statement using Java
Developed by: DHARSHAN D
RegisterNumber: 212223230045 
*/
```

## SOURCE CODE:

```
import java.util.*;
public class Table{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        for(int i=1;i<=10;i++)
        {
            System.out.println(n+" x "+i+" = "+(n*i));
        }
        sc.close();
    }
}
```

## OUTPUT:

<img width="604" height="705" alt="image" src="https://github.com/user-attachments/assets/72391de0-41d1-4d00-843c-6a3e9a96d5cd" />



## RESULT:

Thus, the Java program to print the multiplication table using a loop was executed successfully.


