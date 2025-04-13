# Problem 9

**Problem Statement:**

Write a Java program to find the factorial of a number.

**Solution:**

```java
public class Factorial {
    public static void main(String[] args) {
        int num = 5, fact = 1;
        for (int i = 1; i <= num; i++) {
            fact *= i;
        }
        System.out.println("Factorial: " + fact);
    }
}
```