# Problem 19

**Problem Statement:**

Write a Java program to convert a decimal number to binary.

**Solution:**

```java
public class DecimalToBinary {
    public static void main(String[] args) {
        int num = 10;
        String binary = Integer.toBinaryString(num);
        System.out.println("Binary: " + binary);
    }
}
```