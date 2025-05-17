# Ex.No:9(D) TRANSIENT ---SERILIZATION

## AIM:
 To implement a Java program to perform Transient in Employee details in Serializable interface to make its object serialized.

## ALGORITHM :
1.	Get employee name,designation and id from the user.
2.	Save the Employeeinfo object to emp.txt.
3.	Read the object back from emp.txt.
4.	Print employee name,designation and id(id is null due to transient).
5.	Delete File: Delete emp.txt and handle any exceptions while trying to read it.




## PROGRAM:
 ```
/*
Program to implement a Transient using Java
Developed by: VARNIKA.P
RegisterNumber: 212223240170 
*/
```

## Sourcecode.java:

```JAVA


class Employeeinfo implements Serializable
{
    String name;
    String desi;
    transient int id;
    Employeeinfo(String n, String r,int Id)
    {
    this.name = n;
    this.desi = r;
    this.id=Id;
   
    }
}
```



## OUTPUT:

![image](https://github.com/user-attachments/assets/0513146c-d804-43f3-9500-5d693b124700)

## RESULT:
Thus, implementation of a Java program to perform Transient in Employee details in Serializable interface to make its object serialized was executed and verified successfully.

