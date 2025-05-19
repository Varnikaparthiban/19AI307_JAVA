# Ex.No:12(D) JAVA QUEUE
## AIM:
To Write a java program to display the added elements from the Priority Queue and to insert a particular element into the Priority Queue and then display the elements after clear the priority queue and then display it.(Use clear() method).




## ALGORITHM :

1.Start the program

2.Create a PriorityQueue of integers

3.Read n (number of elements)

4.Loop n times:
 a. Read an integer and add it to the queue

5.Display the queue

6.Clear the queue

7.Display the queue after clearing

8.End




## PROGRAM:
 ```
/*
Program to implement a JAVA QUEUE using Java
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
        Scanner sc=new Scanner(System.in);
        PriorityQueue <Integer> q=new PriorityQueue<>();
        int n=sc.nextInt();
        for(int i=0;i<n;i++)
        {
            q.add(sc.nextInt());
        }
        System.out.println("Display the element of Queue:");
        System.out.println(q);
        System.out.println("Display the element of Queue after clear method:");
        q.clear();
        System.out.println(q);
    }
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/0fa89ea1-3074-4bcb-8261-7ad3cccc1173)



## RESULT:
Thus the java program to create vector and read the elements for two vector in java collection.(Use equals method )was executed successfully.


