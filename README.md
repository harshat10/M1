
# EX-01-Datatypes-Operators
## AIM:
Write a C program to read 3 characters one by one and print the characters in a reverse order.

## ALGORITHM:
1.	Declare three character variables to store the input characters.
2.	Use the scanf function to read the characters one by one from the user.
3.	Print the characters in reverse order using the printf function.
4.	End the program.

## PROGRAM:
```
#include <stdio.h>
int main()
{
    char a;
    scanf("%c",&a);
    printf("%c",a);
    return 0;
}
```
## OUTPUT:
![Screenshot 2025-05-11 192337](https://github.com/user-attachments/assets/7c4d7a17-082e-47bb-b476-6f3bced5b2c3)
## RESULT:
Thus the program to read 3 characters one by one and print the characters in a reverse order has been executed successfully.


# EX-02- Conditional-Statements
## AIM:
Write a C program to read A values and check whether A is positive number or not.

# ALGORITHM:
1.	Declare a variable to store the input value A.
2.	Use the scanf function to read the value of A from the user.
3.	Check if the value of A is greater than zero.
4.	If A is greater than zero, print a message indicating that it's a positive number. 
5.	Otherwise, print a message indicating that it's not a positive number.
6.End the program.

# PROGRAM:
```
#include <stdio.h>
int main()
{
    int F;
    scanf("%d",&F);
    if (F>100){
    printf("Has Fever");}
    else{
    printf(" ");}
    return 0;
}
```
# OUTPUT:
![Screenshot 2025-05-11 192556](https://github.com/user-attachments/assets/b0b375df-f884-4eac-9c76-00ab6f1cdf3b)
# RESULT:
Thus the program to read A values and check whether A is positive number or not has been executed successfully.
 
 
 


# EX-03- Operators-Expressions
## AIM:
Write a program to find minimum between two fraction numbers using conditional operator or ternary operator.

## ALGORITHM:
1.	Declare variables to store the two fraction numbers and the result.
2.	Use the printf function to prompt the user to enter the first fraction number (numerator and denominator separately).
3.	Use the scanf function to read the numerator and denominator of the first fraction.
4.	Repeat steps 2 and 3 to get the second fraction from the user.
5.	Calculate the decimal values of both fractions by dividing the numerators by the denominators.
6.	Use the conditional (ternary) operator to compare the decimal values and store the minimum value in the result variable.
7.	Print the minimum value.

## PROGRAM:
```
#include <stdio.h>
int main()
{
    float p,r,t,Simple_Interest;
    scanf("%f %f %f",&p,&r,&t);
    Simple_Interest=(p*r*t)/100;
    printf("Simple Interest = %.2f ",Simple_Interest);
    return 0;
}
```
## OUTPUT:
![Screenshot 2025-05-11 192648](https://github.com/user-attachments/assets/1f367615-692a-4e2a-8157-b5fbdcb46c07)
## RESULT:
Thus the program to find minimum between two fraction numbers using conditional operator or ternary operator has been executed successfully.




# EX-04- Using Conditional Statements

## AIM:
Write a C program to check whether the input value is equal to 1 using simple if statement

## ALGORITHM:
1.	Declare a variable to store the input value.
2.	Use the scanf function to read the input value from the user.
3.	Use an if statement to check if the input value is equal to 1.
4.	If the condition in the if statement is true, print a message indicating that the input value is equal to 1.
5.	Otherwise, print a message indicating that it's not equal to 1.
6.	End the program.

## PROGRAM:
```
#include <stdio.h>
int main()
{
    int a;
    scanf("%d",&a);
    if (a%2==0){
        printf("Number is Even.");
    }
    else{
        printf("Number is Odd.");
    }
    return 0;
}
```
## OUTPUT:
![Screenshot 2025-05-11 192824](https://github.com/user-attachments/assets/38db4e35-5aad-4959-9b7c-d457d46e8aa3)
## RESULT:
Thus the program to check whether the input value is equal to 1 using simple if statement has been executed successfully



# EX-05- Calculating Total, Percentage, And Division Using Conditional Statements 
## AIM:
To write a C program that reads marks of three subjects, calculates the total and percentage, and then determines the division (First, Second, Pass, or Fail) based on the percentage and minimum marks criteria.
## ALGORITHM:
1.	Start
2.	Declare integer variables m1, m2, m3 for marks, and float variables tot, per.
3.	Input the marks for three subjects.
4.	Calculate total marks: tot = m1 + m2 + m3
5.	Calculate percentage: per = tot / 3
6.	Display total and percentage.
7.	Check if all marks are greater than or equal to 40:
8.	If yes:
a.	If percentage >= 60: Print “Division = First”
b.	Else if percentage >= 48: Print “Division = Second”
c.	Else if percentage >= 36: Print “Division = Pass”
9.	Else: Print “Division = Fail”
10.	End
## PROGRAM:
```
#include <stdio.h>
int main()  
{
    int a;
    scanf("%d",&a);
    if (a>=70){
        printf("A+ GRADE");
    }
    else if (a>=60 && a<70){
        printf("A GRADE");
    }
    else if (a>=50 && a<60){
        printf("B GRADE");
    }
    else if (a>=40 && a<50){
        printf("C GRADE");
    }
    else{
        printf("F GRADE");
    }
    return 0;
}
```
## OUTPUT:
![Screenshot 2025-05-11 192938](https://github.com/user-attachments/assets/05655a85-259a-4cf8-9daa-405bfc421132)

## RESULT:
The program successfully takes three subject marks, calculates the total and percentage, and correctly determines the division based on predefined grading logic.

