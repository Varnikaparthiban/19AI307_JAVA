# Ex.No:12(C)             JAVA STACK & VECTOR
 ## AIM :

To Write a java program to read and get the enumeration of the values present in the Vector and print the  elements using vector in java collection.(Use elements() method)


## ALGORITHM :

1.Start

2.Create a Vector of strings

3.Read n (number of iterations)

4.Loop n times:
 a. Read two strings and add both to the vector

5.Display the vector

6.Create an Enumeration for the vector

7.While the enumeration has more elements:
 a. Print the next element

8.End



## PROGRAM:
 ```
/*
Program to implement a JAVA STACK & VECTOR  using Java
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
        Vector<String> v=new Vector<>();
        int n=sc.nextInt();
        for(int i=0;i<n;i++)
        {
            v.add(sc.next());
            v.add(sc.next());

        }
        System.out.println("The vector is: "+v);
        Enumeration e=v.elements();
        System.out.println("The enumeration of values are:");
        while(e.hasMoreElements())
        {
            System.out.println(e.nextElement());
        }
       
    }
    
}
```




## OUTPUT:

![image](https://github.com/user-attachments/assets/b7397e34-d17a-4b49-a9ed-8fb019a825c5)


## RESULT:

Thus the java program to Write a java program to read and get the enumeration of the values present in the Vector and print the  elements using vector in java collection.(Use elements() method) was executed successfully.








