# Ex.No:8(D) BUFFER INPUT/OUTPUT STREAM

## AIM:
 To create a java program file for displaying the data from the file after skip method using FileInputStream & BufferedInputStream.

## ALGORITHM :
1.	Import java.io.* and java.util.* for file handling and user input.
2.	Create a file named sample.txt and write "This is a line of text inside the file." using FileWriter.
3.	Close the FileWriter to save the content to sample.txt.
4.	Open sample.txt with a FileInputStream wrapped in a BufferedInputStream for efficient reading.
5.	Prompt the user to enter the number of bytes to skip using Scanner.
6.	Skip the specified number of bytes in the file and print the remaining content.
7.	Close the BufferedInputStream and FileInputStream to release system resources.




## PROGRAM:
 ```
/*
Program to implement a Buffer Input/Output Stream using Java
Developed by: VARNIKA.P
RegisterNumber: 212223240170 
*/
```

## Sourcecode.java:

```JAVA


 FileInputStream f=new FileInputStream("sample.txt");
       BufferedInputStream b=new BufferedInputStream(f);
       Scanner sc=new Scanner(System.in);
       int s=sc.nextInt();
       b.skip(s);
    
    System.out.println("Contents after skipping"+" "+s+" "+"bytes:");
    int a=0;
    while((a=b.read())!= -1)
    System.out.print((char)a);
    b.close();
    f.close();
 ```



## OUTPUT:

![image](https://github.com/user-attachments/assets/a47b79b7-3d47-4e59-a8f3-7d5285599add)


## RESULT:
Thus, the java program file for displaying the data from the file after skip method using FileInputStream & BufferedInputStream was executed and done successfully.


