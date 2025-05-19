# Ex.No:1(D) USER DEFINED METHOD.

## AIM:
To create a Java program  print area of square  by defining instance method and local variable.[Class Name is ‘Area’ function name is ‘calculateArea()’  and return type of function is ’void’]


## ALGORITHM :

1.Start the program.
2.Define a class named 'Area'.
3.Declare an instance variable 'side' to hold the side length of the square.
4.Define a public method 'calculateArea' with a void return type:
5.Declare a local variable area.
6.Calculate the area using the formula area = side * side.
7.Print the calculated area.
8.Define the 'main' method:
9.Create an instance of the Area class named square.
10.Assign a value to the side variable of the square object.
11.Call the 'calculateArea' method on the square object.
12.End the program.


## PROGRAM:
 ```
/*
Program to implement a User Defined Method using Java
Developed by: VARNIKA.P
RegisterNumber: 212223240170
*/
```

## Sourcecode.java:

```

import java.util.*;
public class Area {
    double side;
    void calculateArea()
    {
        double area=(double)side*side;
        System.out.println("Area of Square is "+area);
    }
    public static void main(String args[])
    {
        Scanner s=new Scanner(System.in);
        Area obj=new Area();
        obj.side=s.nextDouble();
        obj.calculateArea();
    }
    
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/4ae84d9c-b362-4c39-9e70-42b7b21b1583)


## RESULT:
Thus, the Java program to print area of square  by defining instance method and local variable was created successfully.

