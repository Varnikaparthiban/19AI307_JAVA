# Ex.No:11(E)  JAVA HASHMAP

## AIM:
To Create a java program to retrieve the value from hashmap .
## ALGORITHM :

1.Start the program

2.Read integer n

3.Create an empty HashMap map

4.Repeat n times:
  - Read key and value
  - Insert into map

5.Iterate over map entries and print key-value pairs

6.Get and print value for key 100

7.End


## PROGRAM:
 ```
/*
Program to implement a HASHMAP
Developed by: VARNIKA.P
RegisterNumber:212223240170  
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
        HashMap<Integer,String> map=new HashMap<Integer,String>();
        int n=sc.nextInt();
        for(int i=0;i<n;i++)
        {
            int a=sc.nextInt();
            String b=sc.next();
            map.put(a,b);
            
        }
        for(Map.Entry<Integer,String> entry :  map.entrySet())
        {
            System.out.println(entry.getKey()+" "+entry.getValue());
        }
        String result=map.get(100);
        System.out.println("value: "+result);
    }
}
```




## OUTPUT:

![image](https://github.com/user-attachments/assets/c6e4e238-6a38-4fd1-858f-d13046fa627b)


## RESULT:
Thus the java program to retrieve the value from hashmap was executed sucessfully




