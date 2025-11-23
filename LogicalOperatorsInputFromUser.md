
import java.util.Scanner;

    public class LogicalOperatorsInputFromUser {
        public static void main(String[] args) {

            Scanner sc = new Scanner(System.in);

            System.out.print("Enter first boolean : ");
            boolean x = sc.nextBoolean();

            System.out.print("Enter second boolean : ");
            boolean y = sc.nextBoolean();

            System.out.println("----- Results -----");
            System.out.println("x && y : " + (x && y));   // AND
            System.out.println("x || y : " + (x || y));   // OR
            System.out.println("!x     : " + (!x));       // NOT
            System.out.println("!y     : " + (!y));       // NOT
        }
    }

