# Ex.No:4(C)    CONSTRUCTOR CHAINING(SUPER KEYWORD)

## AIM:
To Create a Java program to implement super keyword in constructor.

## ALGORITHM :
1.  Start the Program.
2.	Define class `College`:
-	a) Define method `display()` that prints "I am a Vehicle"
3.	Define class `Student` that extends `College`:
-	a) Override method `display()` to print "I am a Car"
-	b) Define method `print()`:
-	i) Call `super.display()` to invoke `display()` from `College` class
-	ii) Call `this.display()` to invoke `display()` from `Student` class
4.	Define `Main` class with `main` method:
-	a) Create a `Student` object `sc`
-	b) Call `sc.print()` to execute the `print()` method
5.	End


## PROGRAM:
 ```
Program to implement a Constructor Chaining using Java
Developed by:  PORKODI B
RegisterNumber:  212224240114

```

## Sourcecode.java:

```
class Vehicle {
    Vehicle() {
        System.out.println("I am a Vehicle");
    }
}

// Derived class Car that extends Vehicle
class Car extends Vehicle {
    Car() {
        super();
        System.out.println("I am a Car");
    }
}

public class Main {
    public static void main(String[] args) {
        Car car = new Car();
    }
}
```

## OUTPUT:

<img width="450" height="176" alt="439312939-403dac3b-99d9-4d93-afc2-070ee490f80b" src="https://github.com/user-attachments/assets/dc4a3d19-ea4a-4e38-9fd8-e22806479cc9" />



## RESULT:
Thus the java program for constructor chaining was executed successfully.

