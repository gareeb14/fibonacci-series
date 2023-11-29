# fibonacci-series
Java program to generate the Fibonacci series up to a specified number of terms:
public class FibonacciSeries {
    public static void main(String[] args) {
        int n = 10; // Change 'n' to the number of terms you want in the series

        // First two terms of the Fibonacci series
        int a = 0, b = 1;

        System.out.println("Fibonacci Series up to " + n + " terms:");

        for (int i = 1; i <= n; ++i) {
            System.out.print(a + " ");

            int sum = a + b;
            a = b;
            b = sum;
        }
    }
}
