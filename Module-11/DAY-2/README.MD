# Ex.No:11(B)   JAVA MAP & HASHMAP AND HASHTABLE
## AIM :
To Create a java program to retrieve the key and value from hashtable and display the size of the hashtable and clear the hashtable using clear method concepts.



## ALGORITHM :

1.Start the program

2.Create a Hashtable

3.Read size n

4Loop n times:
  - Read key and value
  - Add to hashtable

5.Iterate through keys and print key-value pairs

6.Print map size

7.Clear the map

8.Print map size again

9.End



## PROGRAM:
 ```
/*
Program to implement a JAVA MAP & HASHMAP AND HASHTABLE using Java
Developed by: VARNIKA.P
RegisterNumber: 212223240170 
*/
```

## Sourcecode.java:

```java

import java.util.*;  
public class Mapp{  
 public static void main(String args[]){ 
     
  Hashtable<Integer,String> map=new Hashtable<>(); 
  Scanner sc=new Scanner(System.in);
  
  int size=sc.nextInt();
  for(int i=0;i<size;i++)
  {
  Integer a=sc.nextInt();
  String b=sc.next();
  map.put(a,b);  
  } 
 
  
 Iterator<Integer> keySetIterator = map.keySet().iterator(); 
 while(keySetIterator.hasNext())
 { 
     Integer key = keySetIterator.next(); 
     System.out.println("key: " + key + " value: " + map.get(key)); 
     
 }
System.out.println("Size of Map: " + map.size()); 

map.clear();
System.out.println("Size of Map: " + map.size()); 

 }  
}  
```



## OUTPUT:

![images](https://github.com/Varnikaparthiban/19AI307_JAVA/blob/8eee1f8951840ae1d4561b5c7af688bdfd7302a5/Module-11/DAY-2/Screenshot%202025-05-18%20210421.png)

## RESULT:
Thus the java program to retrieve the key and value from hashtable for all input value was executed successfully.







