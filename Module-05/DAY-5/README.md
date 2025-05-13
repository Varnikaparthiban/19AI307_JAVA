# Ex.No:5(E) HAS-A RELATIONSHIP
## AIM:
To implement a  Java Program to check given string is palindrome or not use recursion and has-a relationship concepts.

## ALGORITHM :
1.Start the program

2.Input a string s from the user.

3.Define a recursive function pal(s) that:

4.If the length of s is 0 or 1 → Return true (base case).

5.If the first and last characters of s are the same:

6.Call pal() recursively on the substring from index 1 to length - 2.

7.Else → Return false.

8.Call the pal() function with the input string.

9.If the function returns true → Print "s is a palindrome",Else → Print "s is not a palindrome".

10.End the program



## PROGRAM:
 ```
/*
Program to implement a HAS-A RelationShip
Developed by: VARNIKA.P
RegisterNumber:  212223240170
*/
```

## Sourcecode.java:

```java
import java.util.*;
class fun
{
    public static boolean pal(String s)
    {
        if(s.length()==0 || s.length()==1)
        return true;
        if(s.charAt(0)==s.charAt(s.length()-1))
        return pal(s.substring(1,s.length()-1));
        return false;
    }
}
public class Array
{
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        String s1=sc.nextLine();
        fun o=new fun();
        if(o.pal(s1))
        System.out.println(s1+" is a palindrome");
        else
        System.out.print(s1+" is not a palindrome");
    }
}
```





## OUTPUT:

![image](https://github.com/user-attachments/assets/fa8cf0b3-d208-4e76-ae1c-256ed6de3728)


## RESULT:
Thus the java program to check given string is palindrome or not use recursion and has-a relationship concepts.  was executed successfully. 

