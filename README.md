# Experiment 2: Comparing Two Numbers

## AIM:
To write a Java program to compare two numbers.

## ALGORITHM:

### Step 1:
Declare two variables to hold the numbers you want to compare.

### Step 2:
Use an if-else statement to compare the numbers.

### Step 3:
If the first number is greater than the second number, print a message indicating that the first number is greater.

### Step 4:
If the second number is greater than the first number, print a message indicating that the second number is greater.

### Step 5:
If the numbers are equal, print a message indicating that the numbers are equal.

## PROGRAM:
```java
import java.util.Scanner;
public class compare_num
{
    public static void main(String args[])
    {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter first number: ");
        int a = sc.nextInt();
        System.out.print("Enter second number: ");
        int b = sc.nextInt();
        compare(a,b);
    }
    public static void compare(int n1,int n2)
    {
        if(n1 > n2)
        {
            System.out.println(n1+" greater than "+n2);
        }
        else if(n2 > n1)
        {
            System.out.println(n2+" greater than "+n1);
        }
        else
        {
            System.out.println("Both the numbers are equal");
        }
    }
}

```

## OUTPUT:
![image](https://github.com/Aashima02/Comparing-Two-Numbers/assets/93427086/7c0fe578-6476-4a47-9365-4cce04aa2091)

## RESULT:
Thus, a Java program is written to compare two numbers.
