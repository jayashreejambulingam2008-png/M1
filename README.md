
# EX-01-Datatypes-Operators
## AIM:
Write a C program to initialize the character as z & display the same character.

## ALGORITHM:
1. Start the program.
2. Declare a variable ch of type char.
3. Initialize the variable ch with the character 'z'.
4. Use the printf function to display the value of ch.
5. End the program.

## PROGRAM:
```
#include<stdio.h>
int main(){
    char ch='z';
    printf("%c",ch);
    return 0;
}
```
## OUTPUT:
<img width="973" height="204" alt="image" src="https://github.com/user-attachments/assets/7d2c4d74-84ab-4aaf-82a6-ae48c4ec4f66" />

















## RESULT:
Thus the program to initialize the character as z & display the same character has been executed successfully.


# EX-02- Conditional-Statements
## AIM:
Write a C program to check whether the grade is A grade using simple if statement?

# ALGORITHM:
1. Start the program.
2. Declare a variable grade of type char.
3. Read the character input from the user and store it in grade.
4. Check if the value of grade is equal to 'A'.
5. If true, then display the message “Grade is A”.
   If false, do nothing (no output).
6. End the program.

# PROGRAM:
```
#include<stdio.h>
int main()
{
    char grade;
    scanf("%c",&grade);
    if(grade=='A'){
        printf(" Grade is A");
    }
    return 0;
}
```
# OUTPUT:
<img width="986" height="208" alt="image" src="https://github.com/user-attachments/assets/c3e62f36-0a48-42e3-b738-4ddfeddd149e" />











# RESULT:
Thus the program to check whether the grade is A grade using simple if statement has been executed successfully.
 
 
 


# EX-03- Operators-Expressions
## AIM:
Write a C program to find simple interest & compound interest. Note: Inputs are principle, year and rate of interest.

## ALGORITHM:
1. Start the program.
2. Declare variables p, t, r, si, and ci of type float.
p → Principal amount
t → Time in years
r → Rate of interest
si → Simple Interest
ci → Compound Interest
3. Read the values of p, t, and r from the user.
4. Calculate Simple Interest (SI) using the formula:
SI=(𝑝×𝑡×𝑟)/100
5. Calculate Compound Interest (CI) using the formula:
CI=𝑝×(pow((1+𝑟/100),t)
6. Display the calculated values of SI and CI.
7. End the program.

## PROGRAM:
```
#include <stdio.h>
#include<math.h>
int main(){
    float p,t,r,si,ci;
    scanf("%f %f %f",&p,&t,&r);
    si=(p*t*r)/100;
    ci=p*pow((1+(r/100)),t);
    printf("Simple Interest = %.2f\n",si);
    printf("Compound Interest = %.2f\n",ci);
    return 0;
}
```
## OUTPUT:
<img width="981" height="395" alt="image" src="https://github.com/user-attachments/assets/264def6f-bf21-490f-9804-b8e75336d9ab" />









## RESULT:
Thus the program to find simple interest & compound interest has been executed successfully.




# EX-04- Using Conditional Statements

## AIM:
Write a C program to read the age of a candidate and determine whether he/she is eligible for casting his/her own vote for election.

## ALGORITHM:
1. Start the program.
2. Declare a variable age of type int.
3. Read the value of age from the user.
4. Check if age is greater than or equal to 18.
If true, display “Eligible for casting your vote”.
If false, display “Not Eligible to caste your vote”.
5. End the program.

## PROGRAM:
```
#include <stdio.h>
int main()
{
    int age;
    scanf("%d",&age);
    if(age>=18){
        printf("Eligible for casting your vote");
    }else{
        printf("Not Eligible to caste your vote\n");
    }
    
 return 0;   
}
```
## OUTPUT:
<img width="979" height="317" alt="image" src="https://github.com/user-attachments/assets/21d91629-d46c-45b5-b23b-10eb596ee1ae" />









	

## RESULT:
Thus the program to read the age of a candidate and determine whether he/she is eligible for casting his/her own vote for election has been executed successfully



# EX-05- Calculating Total, Percentage, Average 
## AIM:
Write a C program to calculate total, average and percentage of three subjects for engineering admission.
## ALGORITHM:
1. Start the program.
2. Declare variables a, b, c, total, average, and percentage of type float.
3. Read the marks of three subjects (a, b, and c) from the user.
4. Calculate the total marks using the formula:
total=𝑎+𝑏+𝑐
5. Calculate the average marks using the formula:
average=(𝑎+𝑏+𝑐)/3
6. Calculate the percentage using the formula:
percentage=((𝑎+𝑏+𝑐)/300)×100
(Here, 300 is the maximum total marks for three subjects, each out of 100).
7. Display the total, average, and percentage.
8. End the program.
## PROGRAM:
```
#include <stdio.h>
int main(){
    float a,b,c,total,average,percentage;
    scanf("%f %f %f",&a,&b,&c);
    total=(a+b+c);
    average=(a+b+c)/3;
    percentage=((a+b+c)/300)*100;
    printf("Total marks = %.2f\n",total);
    printf("Average marks = %.2f\n",average);
    printf("Percentage = %.2f\n",percentage);
    return 0;
}
```
## OUTPUT:
<img width="975" height="475" alt="image" src="https://github.com/user-attachments/assets/cf164cb5-1837-46b8-9831-160a003e88a0" />

## RESULT:
The program to calculate total, average and percentage of three subjects for engineering admission has been executed succesfully.

