# Ex.No:3(A)  STRING AND ITS OPERATIONS IN JAVA
## AIM:
To create a java program to replace the substring.

## ALGORITHM:

1. A class named `Main` is defined.
2. The `main()` method serves as the entry point of the program.
3. A `Scanner` object `sc` is created to read input from the user.
4. A string `str1` is read from the user using `nextLine()`.
5. The `replace("C++", "Java")` method is called on `str1` to replace all occurrences of `"C++"` with `"Java"`.
6. The modified string is printed to the console.

## PROGRAM:
 ```
/*
Program to implement a String and its Operations using Java
Developed by: VARNIKA.P
RegisterNumber: 212223240170
*/
```

## Sourcecode.java:

```
import java.util.*;
public class Main {
  public static void main(String[] args) {
    Scanner sc = new Scanner(System.in);  
    String str1 = sc.nextLine();
    System.out.println(str1.replace("C++","Java"));
  }
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/7b652196-ab71-4d10-8b7e-fbc218fa5594)


## RESULT:
Thus the java Program to replace the substring was executed successfully.

