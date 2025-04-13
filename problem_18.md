# Problem 18

**Problem Statement:**

Write a Java program to check if two strings are anagrams.

**Solution:**

```java
import java.util.Arrays;

public class AnagramCheck {
    public static void main(String[] args) {
        String str1 = "listen", str2 = "silent";
        char[] arr1 = str1.toCharArray();
        char[] arr2 = str2.toCharArray();
        Arrays.sort(arr1);
        Arrays.sort(arr2);
        if (Arrays.equals(arr1, arr2))
            System.out.println("Anagrams");
        else
            System.out.println("Not Anagrams");
    }
}
```