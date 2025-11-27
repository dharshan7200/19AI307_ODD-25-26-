# Ex.No:1(B) CONDITIONAL STATEMENT

## QUESTION:

Write a java program to get the month from user and and display appropriate output for the given input.

## AIM:

To write a Java program that reads a month number (1–12) from the user and determines whether it belongs to the first, second, third, or fourth quarter of the year using if–else statements.

## ALGORITHM :

1.Start the program.

2.Import the necessary package 'java.util'
    
3.Read the month number as input from the user.
    
4.Check if the month lies between 1 and 3 → print "First Quarter"
   
5.Else check ranges 4–6, 7–9, and 10–12 to print the respective quarters.
   
6.If none of the conditions match, print "Invalid Month" and end the program.


## PROGRAM:
 ```
/*
Program to implement a conditional statement using Java
Developed by: DHARSHAN D
RegisterNumber: 212223230045 
*/
```

## Sourcecode.java:
```
import java.util.Scanner;
public class Main{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);
        int month = sc.nextInt();
        
        if(month >= 1 && month <= 3){
            System.out.println("First Quarter");
        }
        else if(month>=4&&month<=6)   { 
            System.out.println("Second Quarter");
        }
        else if(month>=7&&month<=9){
            System.out.println("Third Quarter");
        }
        else if(month>=10&&month<=12){
            System.out.println("Fourth Quarter");
        }
        else{
            System.out.println("Invalid Month");
        }
        sc.close();
    }
}

```


## OUTPUT:

<img width="580" height="248" alt="image" src="https://github.com/user-attachments/assets/b48fcc5f-7abf-4abc-ac38-b6135220ea06" />


## RESULT:

Thus, the Java program to determine the quarter of a given month using decision-making statements was executed successfully.



