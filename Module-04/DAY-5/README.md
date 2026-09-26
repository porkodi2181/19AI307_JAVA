# Ex.No:4(E)  PARAMETERIZED CONSTRUCTOR
## AIM:
To write a parameterized constructor in the Employee class that initializes name and designation, and then call getter methods in the main() method of another class (Sample) to display the values.

## ALGORITHM :

1.	Start the program.
2.	Define a class Employee:
    a.	  Declare two private string variables: name and designation.
3.	Create a parameterized constructor in Employee:
4.	Accept two parameters: name and designation.
5.	Assign the parameters to the class fields.
6.	Define two getter methods in the Employee class:
     a.	getName() – returns the value of name.
     b.	getDesg() – returns the value of designation.
7.	Create another class Sample with the main method.
8.	Inside the main method:
     a.	Create an object of Employee using the constructor and pass "John" and "Asst.Manager" as arguments.
     b.	Call getName() and store the result in a variable empName.
     c.	Call getDesg() and store the result in a variable empDesg.
9.	Print the values of empName and empDesg.
10.	End the program


## PROGRAM:
 ```
Program to implement a Parameterized Constructor Using Java
Developed by:   PORKODI B
RegisterNumber:  212224240114

```

## Sourcecode.java:

```
public class Employee {
    
    private String name;
    private int age;
    private String designation;

    public Employee() {
        
        this.name = "Robert";
        this.age = 35;
        this.designation = "Senior Developer";
}
    public void displayDetails() {
        System.out.println("Name is:" + name);
        System.out.println("Age is:" + age);
        System.out.println("Designation is:" + designation);
    }

    public static void main(String[] args) {
        Employee employee = new Employee();
        employee.displayDetails();
    }
}
```

## OUTPUT:

<img width="715" height="197" alt="439321305-2095eda4-14fe-4297-8b96-d87ce4e6cde1" src="https://github.com/user-attachments/assets/d7cf1ca2-a51b-4d9d-999a-d885c4f12458" />


## RESULT:
Thus, the  java program was successfully demonstrates the use of a parameterized constructor to initialize class fields.
