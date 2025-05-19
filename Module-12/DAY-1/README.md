# Ex.No:12(A)         JAVA TREE MAP
## AIM:
 To implement a Java program to associate the specified value with the specified key in a Tree Map.

## ALGORITHM :

1.Start the program

2.Create a TreeMap<Integer, String>

3.Read n (number of entries)

4.Loop n times:
 a. Read key a (Integer)
 b. Read value b (String)
 c. Insert (a, b) into TreeMap

5.For each entry in TreeMap:
 a. Print key => value

6.End

## PROGRAM:
 ```
/*
Program to implement a JAVA TREE MAP using Java
Developed by: VARNIKA.P
RegisterNumber:  212223240170
*/
```

## Sourcecode.java:

```JAVA
import java.util.*;
public class java
{
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        TreeMap<Integer,String> tm=new TreeMap<Integer,String>();   
        int n=sc.nextInt();
        for(int i=0;i<n;i++)
        {
            Integer a=sc.nextInt();
            String b=sc.next();
            tm.put(a,b);
        }
        for(Map.Entry m:tm.entrySet())
        {
            System.out.println(m.getKey()+"=>"+m.getValue());
        }

    }
}
```





## OUTPUT:

![image](https://github.com/user-attachments/assets/afd14ab5-ad1f-481e-bd26-086dafeef264)


## RESULT:
Thus the Java program to associate the specified value with the specified key in a Tree Map was executed successfully.
