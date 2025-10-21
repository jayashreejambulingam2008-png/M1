
# EX-01-Datatypes-Operators
## AIM:
Write a C program to read 3 characters one by one and print the characters in a reverse order.

## ALGORITHM:
1. Declare three character variables to store the input characters.
2. Use the scanf function to read the characters one by one from the user.
3. Print the characters in reverse order using the printf function.
4. End the program.
## PROGRAM:
```
#include <stdio.h>

int main() {
    char ch1,ch2,ch3;
    scanf("%c %c %c",&ch1,&ch2,&ch3);
    printf("%c %c %c",ch3,ch2,ch1);

    return 0;
}
```
## OUTPUT:
<img width="1569" height="618" alt="image" src="https://github.com/user-attachments/assets/ff9e5859-8cde-41ef-a5bd-27f7773e8757" />


















## RESULT:
Thus the program to read 3 characters one by one and print the characters in a reverse order has been executed successfully.




# EX-02- Conditional-Statements
## AIM:
Write a C program to read A values and check whether A is positive number or not.

# ALGORITHM:
1. Declare a variable to store the input value A.
2. Use the scanf function to read the value of A from the user.
3. Check if the value of A is greater than zero.
4. If A is greater than zero, print a message indicating that it's a positive number.
5. Otherwise, print a message indicating that it's not a positive number.
6. End the program.

# PROGRAM:
```
#include <stdio.h>

int main() {
    int num;
    scanf("%d",&num);
    (num>0)?printf("It is a positive number"):printf("It is a negative number");

    return 0;
}
```
# OUTPUT:
<img width="1361" height="486" alt="image" src="https://github.com/user-attachments/assets/c2a60c29-606e-4ea6-a93c-4cc3826f3d76" />

<img width="1364" height="426" alt="image" src="https://github.com/user-attachments/assets/cda7a527-ac7b-4b1b-890e-d26c6e6f1754" />











# RESULT:
Thus the program to read A values and check whether A is positive number or not has been executed successfully.
 
 
 


# EX-03- Operators-Expressions
## AIM:
Write a program to find minimum between two fraction numbers using conditional operator or ternary operator.

## ALGORITHM:
1. Declare variables to store the two fraction numbers and the result.
2. Use the printf function to prompt the user to enter the first fraction number (numerator and denominator separately).
3. Use the scanf function to read the numerator and denominator of the first fraction.
4. Repeat steps 2 and 3 to get the second fraction from the user.
5. Calculate the decimal values of both fractions by dividing the numerators by the denominators.
6. Use the conditional (ternary) operator to compare the decimal values and store the minimum value in the result variable.
7. Print the minimum value.

## PROGRAM:
```
#include <stdio.h>

int main() {
    float num1,den1,num2,den2,res1,res2;
    printf("Enter first Numerator and Denominator:\n");
    scanf("%f %f",&num1,&den1);
    printf("\n");
    printf("Enter second Numerator and Denominator:\n");
    scanf("%f %f",&num2,&den2);
    res1=(float)num1/den1;
    res2=(float)num2/den2;
    float main_res=(res1>res2)?res2:res1;
    printf("\nMinimum value after division is: %.2f",main_res);
    return 0;
}

```
## OUTPUT:

<img width="1454" height="555" alt="image" src="https://github.com/user-attachments/assets/a67692c8-780f-4bc6-a7db-65d24a13df26" />










## RESULT:
Thus the program to find minimum between two fraction numbers using conditional operator or ternary operator has been executed successfully.




# EX-04- Using Conditional Statements

## AIM:
Write a C program to check whether the input value is equal to 1 using simple if statement

## ALGORITHM:
1. Declare a variable to store the input value.
2. Use the scanf function to read the input value from the user.
3. Use an if statement to check if the input value is equal to 1.
4. If the condition in the if statement is true, print a message indicating that the input value is equal to 1.
5. Otherwise, print a message indicating that it's not equal to 1.
6. End the program.

## PROGRAM:
```
#include <stdio.h>

int main() {
    int num;
    printf("Enter a number:\n");
    scanf("%d",&num);
    if(num==1){
        printf("The entered value is equal to \'1\'");
    }else{
        printf("The entered value is not equal to \'1\'.");
    }
    return 0;
}
```
## OUTPUT:

<img width="1409" height="495" alt="image" src="https://github.com/user-attachments/assets/f3d9eb39-7643-4d92-aac5-3e993cbf348c" />


<img width="1384" height="554" alt="image" src="https://github.com/user-attachments/assets/1cff43ce-6361-4ef2-b7c0-bde0fd5241ff" />








	

## RESULT:
Thus the program to check whether the input value is equal to 1 using simple if statement has been executed successfully


# EX-05- Calculating Total, Percentage, Average 
## AIM:
To write a C program that reads marks of three subjects, calculates the total and percentage, and then determines the division (First, Second, Pass, or Fail) based on the percentage and minimum marks criteria.

## ALGORITHM:
1. Start
2. Declare integer variables m1, m2, m3 for marks, and float variables tot, per.
3. Input the marks for three subjects.
4. Calculate total marks: tot = m1 + m2 + m3
5. Calculate percentage: per = tot / 3
6. Display total and percentage.
7. Check if all marks are greater than or equal to 40:
If yes: a. If percentage >= 60: Print “Division = First” b. Else if percentage >= 48: Print “Division = Second” c. Else if percentage >= 36: Print “Division = Pass”
Else: Print “Division = Fail”
8. End
## PROGRAM:
```
#include <stdio.h>

int main() {
    int m1,m2,m3;
    float tot,per;
    printf("Enter marks for Three(3) subjects:\n");
    scanf("%d %d %d",&m1,&m2,&m3);
    tot=(float)m1+m2+m3;
    per=(float)tot/3;
    printf("The total marks is: %.2f, and the Percetnage is: %.2f\n",tot,per);
    if(m1>=40 && m2>=40 && m3>=40){
        if(per>=60){
            printf("Division = First");
        }
        else if(per>=48){
            printf("Division = Second");
        }
        else if(per>=36){
            printf("Division = Pass");
        }
        else{
            printf("Division = Fail");
        }
    }else{
        printf("Marks are not sufficient");
    }

    return 0;
}
```
## OUTPUT:

<img width="1605" height="611" alt="image" src="https://github.com/user-attachments/assets/46c3ec95-3180-41f4-b59c-245c4419fbd0" />

## RESULT:
The program successfully takes three subject marks, calculates the total and percentage, and correctly determines the division based on predefined grading logic.

