# 🔢 Largest Finder

A simple Java application that compares three predefined integer variables and determines which one is the largest using conditional logic (`if-else`).

---

## 📌 Features

* Compares three integer variables (`a`, `b`, and `c`).
* Uses conditional statements (`if-else if-else`) to identify the maximum value.
* Outputs the largest number cleanly to the console.

---

## 💡 Code Overview

```java
public class LargestFinder {
    public static void main(String[] args) {

        int a = 45, b = 78, c = 23;
        int largest;

        if (a > b && a > c) {
            largest = a;
        } else if (b > a && b > c) {
            largest = b;
        } else {
            largest = c;
        }

        System.out.println("The largest number is: " + largest);
    }
}