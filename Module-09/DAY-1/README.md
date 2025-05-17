# Ex.No:9(A)          DATA I/O STREAM
## AIM:
To create a Java Program For  displaying number of bytes & read the String and Double value data in the  file "OutputFile.txt" using DataInputStream
Note:Assume OutputFile.txt file created. In the DataInputStream use Output.txt file as arguments
Initialize DataInputStream object name as "di" 

## ALGORITHM :

1.Start the program

2.Open the file "OutputFile.txt" using FileInputStream.

3.Wrap the FileInputStream with a DataInputStream.

4.Check the number of bytes available to read from the file.

5.Print the available bytes.

6.Close the streams

7.End

## PROGRAM:
 ```
/*
Program to implement a DATA I/O STREAM using Java
Developed by: VARNIKA.P
RegisterNumber: 212223240170  
*/
```

## Sourcecode.java:

```JAVA
FileInputStream fi=new FileInputStream("OutputFile.txt");
DataInputStream di=new DataInputStream(fi);
System.out.println("Available number of bytes to read: "+di.available());
System.out.println("Read UFT: "+di.readUTF());
System.out.println("Read double: "+di.readDouble());
di.close();
fi.close();
```






## OUTPUT:

![image](https://github.com/user-attachments/assets/06a73c2e-f2d6-4b4e-9165-ee32fa32bed0)


## RESULT:
Thus the Java Program to store a String Value in a file "testout.txt" using DataOutputStream was executed and verified successfully.

