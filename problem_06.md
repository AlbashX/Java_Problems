# Problem 6

**Problem Statement:**

Write a Java program to print the Fibonacci series up to n terms.

**Solution:**

```java
public class FibonacciSeries {
    public static void main(String[] args) {
        int n = 10, a = 0, b = 1;
        System.out.print("Fibonacci Series: ");
        for (int i = 1; i <= n; i++) {
            System.out.print(a + " ");
            int next = a + b;
            a = b;
            b = next;
        }
    }
}
```