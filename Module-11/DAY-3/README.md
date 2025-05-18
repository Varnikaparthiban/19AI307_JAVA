# Ex.No:11(C)             JAVA LINKED HASHMAP
 ## AIM :

To Create a java program to display the contains key of 104 and to retrieve the key and value using linked hash map.

## ALGORITHM :

1.	Start the Program
2.	Import `java.util.*`
3.	Define class `A` with `main` method:
-	a) Initialize `Scanner` and read integer `n`
-	b) Create a `LinkedHashMap` named `hash` to store integer keys and string values
4.	Use a loop to:
-	a) Read an integer and string from the user
-	b) Add the integer as the key and the string as the value in `hash`
5.	Use an enhanced `for` loop to iterate through `hash` and print each key-value pair
6.	Check if the `hash` contains the key `104` and print the result
7.	End


## PROGRAM:
 ```
/*
Program to implement a JAVA LINKED HASH MAP using Java
Developed by: VARNIKA.P
RegisterNumber:  212223240170
*/
```

## Sourcecode.java:


```JAVA
import java.util.*;

public class LinkedHashMapContainsKey {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        LinkedHashMap<Integer, String> map = new LinkedHashMap<>();
        int n = scanner.nextInt();
        for (int i = 0; i < n; i++) {
            int key = scanner.nextInt();
            scanner.nextLine(); 
            String value = scanner.nextLine();
            map.put(key, value);
        }
        for (Map.Entry<Integer, String> entry : map.entrySet()) {
            System.out.println("key: " + entry.getKey() + " value: " + entry.getValue());
        }
        boolean hasKey = map.containsKey(104);
        System.out.println("Does HashMap contains 104 as key: " + hasKey);
    }
}
```





## OUTPUT:

![image](https://github.com/user-attachments/assets/b96b2f6d-a42e-40ff-9616-1c2947ddcb32)


## RESULT:
Thus the  java program to display the contains key of 104 and to retrieve the key and value using linked hash map was executed successfully.








