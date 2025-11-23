
import java.util.Scanner;

    public class RelationalOperatorsTakeInputFromUser {
        public static void main(String[] args) {

            Scanner sc = new Scanner(System.in);

            System.out.print("Enter first number: ");
            int a = sc.nextInt();

            System.out.print("Enter second number: ");
            int b = sc.nextInt();

            System.out.println("a == b = " + (a == b));  // Equal to
            System.out.println("a != b = " + (a != b));  // Not equal to
            System.out.println("a > b  = " + (a > b));   // Greater than
            System.out.println("a < b  = " + (a < b));   // Less than
            System.out.println("a >= b = " + (a >= b));  // Greater than or equal to
            System.out.println("a <= b = " + (a <= b));  // Less than or equal to
        }
    }

