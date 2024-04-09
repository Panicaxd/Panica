# Panica
import java.util.Scanner;
public class Calcu {
    class Main {
        public static String calc(String input) {
            String exepition = "throws Exeption";
            String[] tt = input.split(" ");
            if (tt.length != 3) {
return exepition;
            }
            int num1, num2;
            try {
                num1 = Integer.parseInt(tt[0]);
                num2 = Integer.parseInt(tt[2]);
            } catch (NumberFormatException e) {
                return exepition;
            }
            if (num1 < 1 || num1 > 10 || num2 < 1 || num2 > 10) {
                return exepition;
            }
            String operator = tt[1];
            int result;
            switch (operator) {
                case "+": result = num1 + num2;
                    break;
                case "-": result = num1 - num2;
                    break;
                case "*": result = num1 * num2;
                    break;
                case "/": result = num1 / num2;
                    break;
                default:
                    return exepition;
            }
            return Integer.toString(result);
        }
    }
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.println("input:");
        String input = scanner.nextLine();
        System.out.println("Output: " + Main.calc(input));
    }
}
