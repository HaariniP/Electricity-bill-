# Electricity-bill-
import java.util.Scanner;
public class SimpleElectricityBill {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
              System.out.print("Enter the number of units consumed: ");
        double units = scanner.nextDouble();

        double billAmount = units * 1.0;  // Basic rate of 1.0 per unit
        double fixedCharges = 30;
        billAmount += fixedCharges;
        System.out.printf("Total electricity bill: Rs. %.2f%n", billAmount);
        scanner.close();
    }
}
