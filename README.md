# sum-and-product-of-a-given-number
import java.util.Scanner;
public class Sumpro {
    public static void main(String args[]) {
        System.out.println("enter your two numbers");
        int num1, num2;
        int num3;
        for (int i = 0; i < 10; i++) {
            Scanner obj = new Scanner(System.in);
            num1 = obj.nextInt();
            num2 = obj.nextInt();
            num3 = num1 + num2;
            int num4;
            num4 = num1 * num2;
            System.out.println(" the sum and product of two numbers are" + num3 + "  " + num4);
        }
    }
}
