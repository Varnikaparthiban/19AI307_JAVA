# Ex.No:9(E) STRING WRITER

## AIM:
To Write a Java Program to append the String with user defined String  using StringWriter
Note:Read the String value and Append String value from the user.Display the Output in the output Screen


## ALGORITHM :

1.Start the program

2.Read two strings: data and append

3.Create StringWriter object

4.Write data to it

5.Append append to it

6.Print original and appended strings

7.Close writer

8.Handle exceptions (if any)

9.End


## PROGRAM:
 ```
/*
Program to implement a STRING WRITER
Developed by: VARNIKA.P
RegisterNumber:  212223240170
*/
```

## Sourcecode.java:

```JAVA

import java.io.*;
import java.util.*;


public class Main {
  public static void main(String[] args) {
    Scanner sc=new Scanner(System.in);
    
    String data = sc.nextLine();
    String append=sc.nextLine();

    try {
      // Create a StringWriter with default string buffer capacity
      
      StringWriter out=new StringWriter();
      out.write(data);
      out.append(append);
      System.out.println("Input Value: " + data);
      System.out.println("After Append: "+out);
      out.close();
      
      
      
      
    }

    catch(Exception e) {
      e.getStackTrace();
    }
  }
}
```




## OUTPUT:

![image](https://github.com/user-attachments/assets/b8aae13b-b070-45fc-a0a5-baee22dbca55)


## RESULT:
Thus, implementation of  a Java program was  successfully append the String with user defined String  using StringWriter

