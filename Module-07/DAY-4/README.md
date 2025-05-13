# Ex.No:7(D) SYNCHRONIZATION
## AIM:
 To Develop a Java Program to perform cube value using static synchronization  concept  for the below Scenario
 In a Class Table create a static synchronized void cube method in that perform cube operation
 Note :Assume Sleep as 400 ms  i.e Thread.Sleep(400)


 
## ALGORITHM :

1.Start

2.Define a class Table.

3.Inside the class, define a method cube(int n) to:

      Lock the current object using synchronized(this) to prevent thread interference (used for multithreading safety).Initialize a variable temp = 1 (unused but can be removed).Loop from i = 1 to i <= n:Set j = i ,Calculate cube: j * j * j

4.Print the cube with a message showing current i and cube value,Pause the thread for 400 milliseconds using Thread.sleep(400).

5.Catch and display any exceptions that may occur during sleep.

6.End




## PROGRAM:
 ```
/*
Program to implement a Packages using Java
Developed by: VARNIKA.P
RegisterNumber:  21223240170
*/
```

## Sourcecode.java:


```JAVA
class Table
 {
     void cube(int n)
     {
         synchronized(this)
         {
             int temp=1;
             for(int i=1;i<=n;i++)
             {
                 int j=i;
                 System.out.println("cube for range value "+n+" "+i+":"+(j*j*j));
                 try
                 {
                     Thread.sleep(400);
                 }
                 catch(Exception e)
                 {
                     System.out.println(e);
                 }
             }
         }
     }
 }
```




## OUTPUT:

![image](https://github.com/user-attachments/assets/b2b06a25-9dc5-461f-aa5e-3f5bfc242609)


## RESULT:
Thus the java program for synchronization was executed successfully.

