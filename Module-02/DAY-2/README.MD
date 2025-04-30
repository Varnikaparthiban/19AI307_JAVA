# Ex.No:2(B) ACCESS MODIFIERS

## AIM:
To develop a Java Program to display the addition number using private modifiers only.
Note:
Input1: 8
Input2: 9

## ALGORITHM :

1.Start the program.
2.Define a class A.
3.Inside the class, create a private method display():
4.Declare two integers a = 8 and b = 9.
5.Print the result of a + b.
6.In the main method:
       *Create an object obj of class A.
       *Call the private method display() using obj.
7.End the program.


## PROGRAM:
 ```
/*
Program to implement a access modifiers using Java
Developed by: VARNIKA.P
RegisterNumber:  212223240170
*/
```

## Sourcecode.java:

```
public class A
{ 
    private void display() 
    { 
        int a=8,b=9;
        System.out.println(a+b); 
    }
    public static void main(String args[])
    {
        A obj = new A();
        obj.display();
    }
}

```


## OUTPUT:

![image](https://github.com/23008344/19AI307_JAVA/blob/bbd1e840b5c86dcbc6948b0c14712e3e34a3db78/Module-02/DAY-2/Screenshot%202025-04-30%20113259.png)

## RESULT:
Thus the java program to display the addition number using private modifiers only was executed successfully.


