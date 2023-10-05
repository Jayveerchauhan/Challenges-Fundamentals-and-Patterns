import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int n = scanner.nextInt();

        for (int i = 0; i < n / 2; i++) {
            
            for (int j = 1; j < n - 2 * i; j++)
                System.out.print("  ");

           
            for (int j = i + 1; j > 0; j--)
                System.out.print(j + " ");

            
            for (int j = 0; j < 2 * i - 1; j++)
                System.out.print("  ");

            
            for (int j = 1; i > 0 && j <= i + 1; j++)
                System.out.print(j + " ");

            System.out.println();
        }

        
        for (int i = n / 2; i >= 0; i--) {
            
            for (int j = 1; j < n - 2 * i; j++)
                System.out.print("  ");

            
            for (int j = i + 1; j > 0; j--)
                System.out.print(j + " ");

            
            for (int j = 0; j < 2 * i - 1; j++)
                System.out.print("  ");

            
            for (int j = 1; i > 0 && j <= i + 1; j++)
                System.out.print(j + " ");

            System.out.println();
        }
    }
}
