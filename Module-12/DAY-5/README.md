# Ex.No:12(E)  JAVA DEQUEUE

## AIM:
To demonstrate how  to display the added elements from the Dequeue using removelast method in java collection.(Use string)


## ALGORITHM :

1.Start the program

2.Create a Deque of strings

3.Read n (number of elements)

4.Loop n times:
 a. Read a string and add it to the deque

5.Display the deque

6.Remove the last element

7.Display the updated deque

8.End



## PROGRAM:
 ```
/*
Program to implement a JAVA DEQUEUE
Developed by: VARNIKA.P
RegisterNumber:  212223240170
*/
```

## Sourcecode.java:


```JAVA
import java.util.*;
public class main
{
    public static void main(String args[])
    {
        Deque<String> dq=new ArrayDeque<>();

       Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        for(int i=0;i<n;i++)
        {
            String a=sc.next();
            dq.add(a);
        }
        System.out.println("Display the element of Dequeue:");
        System.out.println(dq);
        dq.removeLast();
        System.out.println(dq);
     
        
    }
}

```


## OUTPUT:

![image](https://github.com/user-attachments/assets/45b59cbd-b919-47d6-9663-4df56632fdd3)



## RESULT:

Thus the java program  to display the added elements from the Dequeue using removelast method in java collection.(Use string) was executed sucessfully


