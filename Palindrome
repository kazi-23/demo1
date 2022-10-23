import java.util.Scanner;

public class Palindrome {
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        System.out.print("Enter a number: ");
        int num = scan.nextInt();
        scan.close();
        int soln = reverse(num);
        if (num == soln) {
            System.out.println(num + " is a palindrome number");
        } else {
            System.out.println(num + " is not a palindrome number");
        }
    }

    static int reverse(int n) {
        int ans = 0;
        while (n > 0) {
            int rem = n % 10;
            ans = (ans * 10) + rem;
            n = n / 10;
        }
        return ans;
    }
}
