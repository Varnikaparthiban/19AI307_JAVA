# Ex.No:9(C)             STRING READER
## AIM:
 To Create a Java Program to display and skip 5 characters using the predefined Method Skip in StringReader


## ALGORITHM :
1.  The user enters a string (data) and skip 5 characters.
2.	The original string is displayed for reference.
3.	A StringReader object, input, is created to read from data.
4.	The program skips the specified number of characters (5) in the string.
5.	It reads and displays the remaining characters one by one until the end of the string.
6.	Any exceptions are caught, and stack trace information is generated if an error occurs.


## PROGRAM:
 ```
/*
Program to implement a String Reader using Java
Developed by: VARNIKA.P
RegisterNumber: 212223240170 
*/
```

## Sourcecode.java:

```JAVA

import java.io.*;
import java.util.*;
public class main
{
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        String data=sc.nextLine();
        System.out.println("Original data: "+data);
        try
        {
            int k=0;
            StringReader in=new StringReader(data);
            in.skip(5);
            System.out.println("Data after skipping");
            while((k=in.read())!=-1)
            {
                System.out.print((char)k);
            }
            in.close();
        }
        catch(Exception e)
        {
            System.out.print(e);
        }
    }
}
```





## OUTPUT:

![image](https://github.com/user-attachments/assets/bdeceef6-fd6f-4d6b-aae3-12ef9b7913b6)



## RESULT:
Thus the Java Program to display and skip the specified number of characters using the predefined Method Skip in StringReader was executed and verified successfully.











