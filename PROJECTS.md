# Java Class 2025 Projects

Welcome to the Java Class 2025 project hub! 🎉  
Here, every student can add their project ideas and be recognized as a contributor.

## How to Contribute

1. Fork this repository.
2. Clone your fork locally.
3. Create a new branch.
4. Add your entry under your name in the table below.
5. Commit and push your branch.
6. Open a Pull Request (PR)

> Tip: Keep your description short and clear. Example: "Build a simple calculator in Java."

---
import java.util.Scanner;

public class SimpleCalculator {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.println("=== Simple Calculator ===");
        System.out.print("Enter first number: ");
        double num1 = input.nextDouble();

        System.out.print("Enter an operator (+, -, *, /): ");
        char operator = input.next().charAt(0);

        System.out.print("Enter second number: ");
        double num2 = input.nextDouble();

        double result;

        switch (operator) {
            case '+':
                result = num1 + num2;
                break;
            case '-':
                result = num1 - num2;
                break;
            case '*':
                result = num1 * num2;
                break;
            case '/':
                if (num2 != 0)
                    result = num1 / num2;
                else {
                    System.out.println("Error: Division by zero is not allowed!");
                    input.close();
                    return;
                }
                break;
            default:
                System.out.println("Invalid operator!");
                input.close();
                return;
        }

        System.out.println("Result: " + result);
        input.close();
    }
}

## Contributors & Projects

| Student Name | Project Name | Description |
|--------------|-------------|-------------|

| kubanja elijah eldred| Student information system| It displays student's details
 |
