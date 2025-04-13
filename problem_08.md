# Problem 8

**Problem Statement:**

Write a Java program to check if a string is a palindrome.

**Solution:**

```java
public class PalindromeCheck {
    public static void main(String[] args) {
        String str = "madam";
        String reversed = new StringBuilder(str).reverse().toString();
        if (str.equals(reversed))
            System.out.println(str + " is a palindrome.");
        else
            System.out.println(str + " is not a palindrome.");
    }
}
```