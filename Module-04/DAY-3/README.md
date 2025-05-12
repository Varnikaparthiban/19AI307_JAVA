# Ex.No:4(C)    CONSTRUCTOR CHAINING(SUPER KEYWORD)

## AIM:
To Create a Java program to implement super keyword in constructor.

## ALGORITHM :
1.  Start the Program.
2.	Define class `College`:
-	a) Define method `display()` that prints "I am a Vehicle"
3.	Define class `Student` that extends `College`:
-	a) Override method `display()` to print "I am a Car"
-	b) Define method `print()`:
-	i) Call `super.display()` to invoke `display()` from `College` class
-	ii) Call `this.display()` to invoke `display()` from `Student` class
4.	Define `Main` class with `main` method:
-	a) Create a `Student` object `sc`
-	b) Call `sc.print()` to execute the `print()` method
5.	End







## PROGRAM:
 ```
/*
Program to implement a Constructor Chaining using Java
Developed by: VARNIKA.P
RegisterNumber:  212223240170
*/
```

## Sourcecode.java:


```java
class Vehicle
{
    Vehicle()
    {
        System.out.println("I am a Vehicle");
        
    }
    
}
class Car extends Vehicle
{
    Car()
    {
        super();
        System.out.print("I am a Car");
    }
}
public class Main
{
    public static void main(String args[])
    {
        Car s=new Car();
        
    }
}

```


## OUTPUT:

![image](https://github.com/user-attachments/assets/fc6a6ed5-529c-422e-9031-e43e40bbd4f9)


## RESULT:
Thus the java program for constructor chaining was executed successfully.




