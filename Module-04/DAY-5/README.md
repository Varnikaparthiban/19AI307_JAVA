# Ex.No:4(E)  PARAMETERIZED CONSTRUCTOR
## AIM:
To write a parameterized constructor in the Laptop class that initializes the brand , price class field with the string "Apple" and 42500.75 using getter and setter methods.

## ALGORITHM :


1. Define a class `Laptop` with instance variables `brand` (String) and `price` (double).
2. Create a constructor `Laptop(String b, double p)` to initialize `brand` and `price` using `this` keyword.
3. Define a method `getBrand()` to return the `brand` value.
4. Define a method `getPrice()` to return the `price` value.
5. Define a `Sample` class with the `main` method as the entry point.
6. Inside `main`, create a `Laptop` object `lap` using the constructor with values `"Apple"` and `42500.75`.
7. Print the brand using `lap.getBrand()`.
8. Print the price using `lap.getPrice()`.



## PROGRAM:
 ```
/*
Program to implement a Parameterized Constructor Using Java
Developed by: VARNIKA.P
RegisterNumber: 212223240170
*/
```

## Sourcecode.java:
```java
class Laptop {

	String brand;
	double price;
	
	Laptop(String b , double p)
	{
	    this.brand = b;
	    this.price = p;
	}
	
	
	public String getBrand() {
	    
	    return brand;
	}
	public double getPrice() {
	    
	    return price;
	}
}

public class Sample {
	
	public static void main(String[] args) {
	    
	    Laptop lap = new Laptop("Apple",42500.75);
	    System.out.println(lap.getBrand());
	    System.out.println(lap.getPrice());
	}
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/34cd8d41-5232-44fb-abe0-90ecbb5511e7)


## RESULT:
Thus, the  java program was successfully demonstrates the use of a parameterized constructor to initialize class fields.


 


