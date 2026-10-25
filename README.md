# Simple Interest Calculator

## Description
The Simple Interest Calculator is a simple Java program that calculates the simple interest based on the principal amount, rate of interest, and time period.

## Formula
Simple Interest = (Principal × Rate × Time) / 100

## Input
- Principal amount: 100000
- Rate of interest: 10%
- Time period: 2 years

## Output
```text
Simple Interest = 20000
```

## Java Program
```java
import java.util.Scanner;

public class SimpleInterestCalculator {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        double principal = sc.nextDouble();
        double rate = sc.nextDouble();
        double time = sc.nextDouble();

        double simpleInterest = (principal * rate * time) / 100;

        System.out.println((int) simpleInterest);

        sc.close();
    }
}
```

## Example
Input:
```text
100000
2
10
```

Output:
```text
20000
```

## Technologies Used
- Java
- Scanner class

## Author
Student
