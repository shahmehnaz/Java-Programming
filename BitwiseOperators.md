public class BitwiseOperators {
        public static void main(String[] args) {

            int a = 7;   // 0111
            int b = 8;   // 1000

            System.out.println("a = " + a);
            System.out.println("b = " + b);

            System.out.println("a & b  : " + (a & b));   // Bitwise AND
            System.out.println("a | b  : " + (a | b));   // Bitwise OR
            System.out.println("a ^ b  : " + (a ^ b));   // Bitwise XOR
            System.out.println("~a     : " + (~a));      // Bitwise NOT
            System.out.println("a << 1 : " + (a << 1));  // Left shift
            System.out.println("a >> 1 : " + (a >> 1));  // Right shift
        }
    }

