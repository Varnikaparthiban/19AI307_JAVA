# Ex.No:4(D) FINAL & STATIC IN JAVA

## AIM:
    Create a final class 'Company' with Company Name,Company Id and Address as its member, make Company_Id as final variable with value "ED12G45" and write print() to display its member in the Output.Create a Main class and access print() of Company class.
   
## ALGORITHM :

1.Start the program

2.Define the Company class as final:

3.Declare the member variables:

       *String Company_Id = "ED12G45"; (final variable to store the company ID)
       
       *String name = "ABC Foods"; (to store the company name)
       
       *String addr = "Chennai"; (to store the company address)
       
4.Define a method print() to display the company details:

5.Print Company_Id, name, and addr.

6.Define the Main class:

       In the main method:  Create an instance of the Company class (obj).
       
       Call the print() method of the Company class using the obj instance to display the company details.
       
7.End

## PROGRAM:
 ```
/*
Program to implement a final & Static using Java
Developed by: VARNIKA.P
RegisterNumber:  212223240170
*/
```

## Sourcecode.java:

```java
final class Company
{
    String Company_Id="ED12G45";
    String name="ABC Foods";
    String addr="Chennai";
    
    void print()
    {
        System.out.println("Company Details are,"+"\nId is "+Company_Id+"\nName is "+name+"\nAddress is "+addr);
    }
}
public class Main{
public static void main(String[] args)
{
    Company obj=new Company();
    obj.print();
}
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/a6e20852-5a7a-47cf-bb26-728edfac0d97)



## RESULT:
Thus, the java program to perform final & static keyword was executed successfully.
