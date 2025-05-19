# Ex.No:6(B) MULTI-LEVEL INHERITANCE

## AIM:
To Develop a Java program to perform Multilevel Inheritance to print student details.

## ALGORITHM :

1. Create a class `College` that prints the college name.

2. Create a class `Department` that:

   * Inherits from `College`.
   * Prints the department name.

3. Create a class `Student` that:

   * Inherits from `Department`.
   * Prints the student name.

4. In the `main` method:

   * Create an object of `Student`.
   * Call all three print methods to display:

     * College name
     * Department name
     * Student name

## PROGRAM:
 ```
/*
Program to implement a MultiLevel Inheritance using Java
Developed by: VARNIKA.P
RegisterNumber: 212223240170 
*/
```

## Sourcecode.java:
```java
class College
{
    void print_cgeName()
    {
        System.out.println("Saveetha Engineering College");
    }
}
class Department extends College
{
    void print_deptName()
    {
        System.out.println("Computer Science and Engineering");
    }
}
class Student extends Department
{
    void print_stuName()
    {
        System.out.println("John Britto");
    }
}
public class Main
{
    public static void main(String [] args)
    {
        Student st = new Student();
        st.print_cgeName();
        st.print_deptName();
        st.print_stuName();
    }
}
```

## OUTPUT:

![image](https://github.com/akshayaamanagal/19AI307_JAVA/blob/59fd48f55d3568c597171e1af4b0a70b262140d5/Module-06/DAY-2/Screenshot%202025-05-19%20113342.png)

## RESULT:
Thus the java program for multi-level inheritance was executed successfully.





