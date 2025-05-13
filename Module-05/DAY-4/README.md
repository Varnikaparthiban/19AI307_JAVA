# Ex.No:5(D) IS-A RELATIONSHIP AND HAS-A RELATIONSHIP
## AIM:
   To Create a java program to find factorial of number using class and object concepts and apply the has-a relationship.
 
## ALGORITHM :
1.	Start the Program
2.	Define class `factorial`:
-	a) Declare integer `n` and initialize `fact` to 1
-	b) Define method `factorial(int n)`:
-	i) Set `this.n = n`
-	ii) Use a loop from 1 to `n` to calculate `fact = fact * i`
-	iii) Print "Factorial is:" followed by `fact`
3.	In `main` class `main` method:
-	a) Use `Scanner` to read integer `n`
-	b) Create an `factorial` object and call `factorial(n)`
4.	End

## PROGRAM:
 ```
/*
Program to implement a IS-A RELATIONSHIP AND HAS-A RELATIONSHIP using Java
Developed by: VARNIKA.P
RegisterNumber:  212223240170
*/
```

## Sourcecode.java:

```JAVA
import java.util.*;
class factorial{
   
    int fact(int a) {
        int i, f = 1;
        for (i = 1; i <= a; i++) {
            f = f * i;
        }
        return f;
    }
}
public class Main {
    public static void main(String args[]) {
        int a, f;
        Scanner sc = new Scanner(System.in);
        a = sc.nextInt();
        factorial ff = new factorial();
        f = ff.fact(a);
        System.out.println("Factorial is:" + f);
    }
}
```






## OUTPUT:

![image](https://github.com/user-attachments/assets/813255a6-7e8d-4741-a115-bce71108c508)



## RESULT:
Thus the java program to find factorial of number using class and object concepts and apply the has-a relationship was executed successfully.
