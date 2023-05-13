# Experiment-3---JAVA
## AIM
To create a Java program to find the number of days in a month
## PROCEDURE
1. Import the Scanner class from the java.util package.
2. Define a public class named "Main".
3. Declare the main method with the signature "public static void main(String[] args)".
4. Inside the main method, create an instance of the Scanner class using "Scanner sc = new Scanner(System.in)" to read input from the user.
5. Declare an integer variable "month" to store the user's input.
6. Use conditional statements (if-else) to determine the number of days in the entered month
7. End the program
## PROGRAM
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        int month;
        System.out.println("Enter month number from 1(-Jan) to 12(-Dec): ");
        month=sc.nextInt();
        if(month==1||month==3||month==5||month==7||month==8||month==10||month==12){
            System.out.println("31 Days in this Month");
        }
        else if(month==4||month==6||month==7||month==11){
            System.out.println("30 Days in this Month");
        }
        else if(month==2){
            System.out.println("28 Days in this Month");
        }
        else{
            System.out.println("Enter a valid number from 1 to 12");
        }
    }
}
```
## OUTPUT
<img width="396" alt="image" src="https://github.com/Shavedha/Experiment-3---JAVA/assets/93427376/456fdaa0-c77b-4a37-aa7f-af69730f5948">

## RESULT
Hence the number of days in a month are determined using Java Programming language.
