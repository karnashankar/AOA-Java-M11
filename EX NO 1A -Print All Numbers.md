
# EX 1A Print All Numbers 

## AIM:
To Write a Java program that takes an integer input N from the user and prints all the numbers from 1 to N, separated by spaces, on a single line..

## Algorithm
1. Start the program and import the `Scanner` class to take user input.
2. Create a `Scanner` object to read an integer input `N` from the user.
3. Check if `N` is greater than 0; if not, display `"Invalid input. N must be greater than 0."`
4. Use a `for` loop to iterate from 1 to `N`.
5. Print each number separated by a space on the same line.
1. Start

2. Input an integer N from the user.

3. Initialize a counter variable i = 1.

4. Repeat while i ≤ N:

5. Print i followed by a space.

6. Increment i by 1.

#### Developed By: Ponguru Aasrith Sairam
#### Register Number: 212223240116

## Program:
```
/*
Developed by: PONGURU AASRITH SAIRAM
Register Number: 212223240
*/

import java.util.*;
public class PrintNum{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        for(int i=1;i<=n;i++){
            System.out.print(i+" ");
```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        System.out.print("Enter an integer N: ");
        int N = scanner.nextInt();
        
        for (int i = 1; i <= N; i++) {
            System.out.print(i);
            if (i < N) System.out.print(" ");
}
        
        scanner.close();
}
}

```

## Output:
<img width="491" height="159" alt="image" src="https://github.com/user-attachments/assets/ef5e3fdf-c4da-46c2-b207-43343d9ccad8" />

<img width="476" height="162" alt="image" src="https://github.com/user-attachments/assets/c9c3584a-9184-4582-831d-ac0aee8f119d" />


## Result:
The program successfully print all the numbers from 1 to N. 

