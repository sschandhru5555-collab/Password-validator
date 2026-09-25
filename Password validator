import java.util.Scanner;

public class PasswordValidator {
    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        System.out.print("Enter your password: ");
        String password = sc.nextLine();

        boolean upper = password.matches(".*[A-Z].*");
        boolean lower = password.matches(".*[a-z].*");
        boolean number = password.matches(".*[0-9].*");
        boolean special = password.matches(".*[@#$%!].*");

        if (password.length() >= 8 && upper && lower && number && special) {
            System.out.println("Strong Password - Valid");
        } else {
            System.out.println("Weak Password - Invalid");
        }

        sc.close();
    }
}
