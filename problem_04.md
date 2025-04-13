# Problem 4

**Problem Statement:**

Write a Java program to find the largest among three numbers.

**Solution:**

```java
public class LargestNumber {
    public static void main(String[] args) {
        int a = 10, b = 20, c = 15;
        if (a >= b && a >= c)
            System.out.println(a + " is the largest.");
        else if (b >= a && b >= c)
            System.out.println(b + " is the largest.");
        else
            System.out.println(c + " is the largest.");
    }
}
```