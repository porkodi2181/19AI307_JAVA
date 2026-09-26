# Ex.No:5(D) IS-A RELATIONSHIP AND HAS-A RELATIONSHIP
## AIM:
   To Create a java program to find factorial of number using class and object concepts and apply the has-a relationship.
 
## ALGORITHM :
1.	Start the Program
2.	Define class `A`:
-	a) Declare integer `n` and initialize `fact` to 1
-	b) Define method `factorial(int n)`:
-	i) Set `this.n = n`
-	ii) Use a loop from 1 to `n` to calculate `fact = fact * i`
-	iii) Print "Factorial is:" followed by `fact`
3.	In `main` class `main` method:
-	a) Use `Scanner` to read integer `n`
-	b) Create an `A` object and call `factorial(n)`
4.	End

## PROGRAM:
 ```
Program to implement a IS-A RELATIONSHIP AND HAS-A RELATIONSHIP using Java
Developed by:  PORKODI B
RegisterNumber:  212224240114
```

## Sourcecode.java:

```
import java.util.*;
import java.util.Scanner;
class s1{
    void Oddsum(int number)
    {
	int i = 1, sum = 0;
	while(i <= number) 
        {
            sum += i;
            i++;
        }
 
    System.out.println("Sum = " + sum);
    } 

 
}

public class Odd_sum{
	public static void main(String args[])
	{
	   int number;  
      
      Scanner sc = new Scanner(System.in);
      number=sc.nextInt();
      s1 obj=new s1();
      obj.Oddsum(number);
	}
}
```

## OUTPUT:

<img width="402" height="250" alt="442042078-d2bdb78c-2179-410d-bafb-bc39849f3944" src="https://github.com/user-attachments/assets/d5770061-7e17-4754-ac47-c797b15a0b56" />

## RESULT:
Thus the java program to find factorial of number using class and object concepts and apply the has-a relationship was executed successfully.


