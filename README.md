# JAVA_FULL_STACK.
Java full stack assignment 1 - Ashmi.S

# Write a Java program to print the sum, multiply, subtract, divide and remainder of two numbers.

## Program:
```
import java.util.Scanner;
public class MathOperation{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the numbers:");
int num1 =sc.nextInt();
int num2= sc.nextInt();
int sum=num1+num2;
System.out.println("Sum of two numbers: "+sum);
int sub=num1-num2;
System.out.println("Subtraction of two numbers: "+sub);
int mul=num1*num2;
System.out.println("Product of two numbers: "+mul);
float divi=num1/num2;
System.out.println("Division of two numbers: "+divi);
int rem=num1%num2;
System.out.println("Remainder of two numbers: "+rem);
    }
}
```

## Output:
![MathOperations](https://user-images.githubusercontent.com/103128410/224521300-02c6b64f-ab4a-4346-bf47-2ba22238fad2.png)



# Write a Java program to compare two numbers.

## Program:
```
import java.util.Scanner;
public class Comparison{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the numbers:");
int num1 =sc.nextInt();
int num2= sc.nextInt();
if(num1==num2)
{
    System.out.println("Both the numbers are equal.");
}
else if(num1>num2)
{
     System.out.println(num1+" is greater than"+num2);
}
else
{
     System.out.println(num2+" is greater than "+num1);
}
    }
}
```

## Output:
