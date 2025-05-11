# Ex.No:2(E)  LARGEST ELEMENT IN AN ARRAY

## AIM:
To write a Java program that reads an array size and elements from the user and then finds and prints the largest element in the array.

## ALGORITHM :
1.	Start the program.
2.	Read the size of the array from the user.
3.	Declare an array of the given size.
4.	Read the array elements from the user.
5.	Initialize a variable temp with the first element of the array.
6.	Traverse the array using a loop.
7.	Compare each element with temp. If an element is larger, update temp.
8.	After the loop ends, print the largest number.
9.	End the program.
	

## PROGRAM:
 ```
/*
Program to implement a Smallest Element in an Array
Developed by: AKSHAYAA M
RegisterNumber:  212222230009
*/
```

## Sourcecode.java:
```java
import java.util.Scanner;
public class lar
{
    public static void main(String [] args)
    {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int arr [] = new int[n];
        for(int i =0;i<n;i++)
        {
            arr[i] = sc.nextInt();
        }
        int temp = 0;
        for(int i=0;i<arr.length;i++)
        {
            for(int j=i+1;j<arr.length;j++)
            {
                if (arr[i]>arr[j])
                {
                    temp = arr[i];
                    arr[i] = arr[j];
                    arr[j] = temp;
                    temp++;
                }
                
            }
            
        }
        System.out.println("The largest element in the array is: "+arr[n-1]);
        
    }
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/78f4e24f-c492-4a2d-b855-3cb87022c44d)


## RESULT:
Thus the java program successfully reads the array size and elements from the user and correctly finds and prints the largest number in the array.




