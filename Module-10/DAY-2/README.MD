# Ex.No:10(B) JAVA LINKED LIST
## AIM :
To Create a java program to Apply the listiterator method concepts in program to returns an object of Iterator class that contains  the elements in proper sequence  starting from the specified position as mentioned in the argument , display the elements from the linkedlist.To Create a linkedlist, read size of the list , read the elements for the linkedlist  and display it.
Note:Index value consider as 1.


## ALGORITHM :

1.Start the program

2.Read size s

3.Initialize an empty LinkedList ll

4.Read s strings and add to ll

5.Create an iterator starting from index 1

6.While more elements exist, print each

7.End



## PROGRAM:
 ```
/*
Program to implement a JAVA LINKED LIST using Java
Developed by: VARNIKA.P
RegisterNumber:  212223240170-*
*/
```

## Sourcecode.java:

```java

import java.util.*;
public class main
{
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        LinkedList<String> ll=new LinkedList<>();
        int s=sc.nextInt();
        sc.nextLine();
        for(int i=1;i<=s;i++)
        {
            ll.add(sc.next());
            
        }
        Iterator i=ll.listIterator(1);
        while(i.hasNext())
        {
             System.out.println(i.next());
        }
       
           
        
    }
}
```




## OUTPUT:

![images](https://github.com/Varnikaparthiban/19AI307_JAVA/blob/0feaf632be601a6b5ed729fc16e650db2c0b49f2/Module-10/DAY-2/Screenshot%202025-05-18%20204400.png)

## RESULT:
Thus the Java program of the creation of a linkedlist was executed successfully.





