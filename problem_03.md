# Problem 3

**Problem Statement:**

Write a Java program to check if a number is even or odd.

**Solution:**

```java
public class EvenOdd {
    public static void main(String[] args) {
        int num = 7;
        if (num % 2 == 0)
            System.out.println(num + " is even.");
        else
            System.out.println(num + " is odd.");
    }
}
```