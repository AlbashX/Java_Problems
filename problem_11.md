# Problem 11

**Problem Statement:**

Write a Java program to swap two numbers without using a temporary variable.

**Solution:**

```java
public class SwapNoTemp {
    public static void main(String[] args) {
        int a = 5, b = 10;
        a = a + b;
        b = a - b;
        a = a - b;
        System.out.println("a = " + a + ", b = " + b);
    }
}
```