# Ex.No:9(B) BYTE ARRAY I/O
## AIM:
To create a java program to write data using ByteArrayOutputStream.


## ALGORITHM :

1.Start

2.Create a Scanner object to read user input from the console.

3.Read a line of text from the user and store it in a string variable data.

4.Create a ByteArrayOutputStream object named out.

5.Convert the string data to a byte array using getBytes() method.

6.Write the byte array to the ByteArrayOutputStream using out.write(array).

7.Convert the output stream data back to a string using out.toString().

8.Store the result in streamData.

9.Print the string from the output stream to the console.

10.Close the ByteArrayOutputStream using out.close().

11.If an exception occurs, catch it and handle using getStackTrace().

12.End


## PROGRAM:
 ```
/*
Program to implement a BYTE ARRAY I/O using Java
Developed by: VARNIKA.P
RegisterNumber: 212223240170 
*/
```

## Sourcecode.java:

```java 

import java.io.*;
import java.util.*;
public class Main {
    public static void main(String[] args) {

    
     Scanner sc=new Scanner(System.in);
     String data =sc.nextLine();
     ByteArrayOutputStream  out = new ByteArrayOutputStream();

    try {
     
      byte[] array = data.getBytes();

      out.write(array);

      String streamData = out.toString();
      System.out.println("Output stream: " + streamData);

      out.close();
    }

    catch(Exception e) {
      e.getStackTrace();
    }
  }
}
```




## OUTPUT:

![images](https://github.com/Varnikaparthiban/19AI307_JAVA/blob/6a65d650ba697dc5e6052cd285eeb7111c91296b/Module-09/DAY-2/Screenshot%202025-05-17%20111919.png)

## RESULT:
Thus, java program to write data using ByteArrayOutputStream was executed and verified successfully.





