
import java.util.Scanner;

    public class ArithematicOperatorsTakingInputFromUser {
        public static void main(String[] args) {

            Scanner sc = new Scanner(System.in);

            System.out.print("Enter first number: ");
            int a = sc.nextInt();

            System.out.print("Enter second number: ");
            int b = sc.nextInt();//used to take integer input from user

            // Arithmetic operations
            int sum = a + b;          // Addition
            int difference = a - b;   // Subtraction
            int product = a * b;      // Multiplication
            int quotient = a / b;     // Division
            int remainder = a % b;    // Modulus (Remainder)

            // Output results
            System.out.println("----- Results -----");
            System.out.println("Addition = " + sum);
            System.out.println("Subtraction = " + difference);
            System.out.println("Multiplication = " + product);
            System.out.println("Division = " + quotient);
            System.out.println("Remainder = " + remainder);
        }
    }

