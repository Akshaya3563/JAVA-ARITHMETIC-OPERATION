# JAVA-ARITHMETIC-OPERATION
Java program to perform basic arithmetic operations such as addition, subtraction, multiplication and division

# Java Arithmetic Operations

## AIM
To write a Java program to perform basic arithmetic operations such as addition, subtraction, multiplication and division using user input.

## PROGRAM
```
import java.util.Scanner;

public class ArithmeticOperations {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter first number: ");
        int a = sc.nextInt();

        System.out.print("Enter second number: ");
        int b = sc.nextInt();

        System.out.println("Addition: " + (a + b));
        System.out.println("Subtraction: " + (a - b));
        System.out.println("Multiplication: " + (a * b));
        System.out.println("Division: " + (a / b));

        sc.close();
    }
}
```
## INPUT
```
Enter first number: 20
Enter second number: 10
```
## OUTPUT
```
Addition: 30
Subtraction: 10
Multiplication: 200
Division: 2
```
## RESULT
Thus, the Java program was successfully executed to perform basic arithmetic operations.
