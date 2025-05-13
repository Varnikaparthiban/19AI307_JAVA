# Ex.No:7(A)           EXCEPTION HANDLING-RUN TIME EXCEPTION
## AIM:
  To Develop a Java Program for handling Arithmetic Exception (division by zero exception) using Exception Handling Mechanism.

## ALGORITHM :
1.  Start the Program
2.	Import `java.util.*` for input handling
3.	Define class `java`:
-	a) In `main` method, create `Scanner` object `sc` for input
4.	Use `try` block to:
-	a) Read integers `num1` and `num2` from user input
-	b) Calculate `result = num1 / num2` and print "Result: " followed by `result`
5.	Use `catch` block to handle `ArithmeticException`:
-	a) If division by zero occurs, print "You Shouldn't divide a number by zero"
6.	End







## PROGRAM:
 ```
/*
Program to implement a Exception Handling-Run Time Exception using Java
Developed by: VARNIKA.P
RegisterNumber:  212223240170
*/
```

## Sourcecode.java:

```java
import java.util.*;
public class java
{
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        try
        {
            int num1=sc.nextInt();
            int num2=sc.nextInt();
            int result=num1/num2;
            System.out.print("Result: "+result);
            
        }
        catch(ArithmeticException e)
        {
            System.out.print("Arithmetic Exception: Number should not divide by zero");
        }
    }
}
```





## OUTPUT:

![image](https://github.com/user-attachments/assets/bdda6bea-4ae7-46a5-9f73-b18ae52885fb)



## RESULT:
Thus the Java Program for handling Arithmetic Exception (division by zero exception) using Exception Handling Mechanism was executed successfully.

