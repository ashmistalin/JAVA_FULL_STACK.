# JAVA_FULL_STACK.
Java full stack assignment 1 - Ashmi.S

# 1)Write a Java program to print the sum, multiply, subtract, divide and remainder of two numbers.

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



# 2)Write a Java program to compare two numbers.

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

![comparison](https://user-images.githubusercontent.com/103128410/224521491-127f4db7-62b8-48ef-873e-b1a55e7a547d.png)



#  3)Write a Java program to convert a string to an integer.

## Program:
```
)import java.util.Scanner;
public class StringToInteger{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the string:");
        String str= sc.nextLine();
        int num= Integer.parseInt(str);
        System.out.println("The integer value of the string is: "+num);
    }
}
```

## Output:

![stringtoint](https://user-images.githubusercontent.com/103128410/224521631-f19a6d36-a336-4c61-8aad-c086623b5784.png)


# 4) Java Program to find area of rhombus.

## Program:
```
import java.util.Scanner;
public class AreaOfRhombus{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the first diagonal length(d1):");
        float d1= sc.nextFloat();
        System.out.println("Enter the second diagonal length(d2):");
        float d2= sc.nextFloat();
        float area=d1*d2/2;
        System.out.println("The area of the rhombus in sq. units: "+area);
    }
}
```

## Output:

![areaofrhombus](https://user-images.githubusercontent.com/103128410/224521814-ed8e1bd2-ac1a-4ee0-8b22-2881db766b3e.png)


# 5)Write a Java program to find the number of days in a month.

## Program:
```
import java.util.Scanner;
public class DaysInMonth{
    public static void main(String[] args){
        Scanner sc= new Scanner(System.in);
        System.out.print("Enter the month in number:");
        int month=sc.nextInt();
        System.out.print("Enter the year:");
        int year=sc.nextInt();
        switch(month)
        {
            case 1:
            case 3:
            case 5:
            case 7:
            case 8:
            case 10:
            case 12:
                System.out.print("\nThis month has 31 days.");
            break;
            case 4:
            case 6:
            case 9:
            case 11:
                System.out.print("\nThis month has 30 days.");
            break;
            case 2:
                if(year%4==0)
                {
                    System.out.print("\nThis month has 29 days.");
                }
                else
                {
                    System.out.print("\nThis month has 28 days.");
                }
            break;
            default:
                System.out.print("Enter a valid number of the month.");
        }
    }
}
```

## Output:

![daysinmonth](https://user-images.githubusercontent.com/103128410/224521944-4f40e3f5-50c6-4802-84b0-5ef8dfca70e2.png)
