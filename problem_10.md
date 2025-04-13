# Problem 10

**Problem Statement:**

Write a Java program to swap two numbers using a temporary variable.

**Solution:**

```java
public class SwapTemp {
    public static void main(String[] args) {
        int a = 5, b = 10, temp;
        temp = a;
        a = b;
        b = temp;
        System.out.println("a = " + a + ", b = " + b);
    }
}
```