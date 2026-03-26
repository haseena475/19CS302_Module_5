# EX 24 Create a structure program to read(empno,dept and basic pay) and store the data of 3 employees and calculate their Gross Salary(da =10% and HRA=30% from BP).

## AIM:
To Create a structure program to read(empno,dept and basic pay) and store the data of 3 employees and calculate their Gross Salary(da =10% and HRA=30% from BP).

## Algorithm
Start. Define a variables. Create a structure program to read(empno,dept and basic pay) and store the data of 3 employees and calculate their Gross Salary(da =10% and HRA=30% from BP). Read the value using scanf. Ask the user to make an input. Print out the answer. End
## Program:
```
/*
A structure program to read(empno,dept and basic pay) and store the data of 3 employees and calculate their Gross Salary(da =10% and HRA=30% from BP).
Developed by: DUDEKULA HASEENA
RegisterNumber: 212222063004
#include <stdio.h> 
struct Employee {
int empno; 
char dept[100];
float basic_pay; 
float gross_salary; 
float da;
float hra;
};
int main() {
struct Employee employees[3]; 
for (int i = 0; i < 3; ++i) {
scanf("%d", &employees[i].empno); 
scanf("%s", employees[i].dept); 
scanf("%f", &employees[i].basic_pay);
employees[i].da = 0.1 * employees[i].basic_pay; // DA is 10% of Basic Pay 
employees[i].hra = 0.3 * employees[i].basic_pay; // HRA is 30% of Basic Pay 
employees[i].gross_salary = employees[i].basic_pay + employees[i].da +
employees[i].hra;
}
printf("Details of the Employee:\n");
for (int i = 0; i < 3; ++i) {
printf("%d %s %.f %.f %.f %.2f\n", employees[i].empno, employees[i].dept, 
employees[i].basic_pay, employees[i].da, employees[i].hra, employees[i].gross_salary);
}
return 0;
}
*/
```

## Output:

<img width="1012" height="525" alt="image" src="https://github.com/user-attachments/assets/d04cf5f3-91bd-439c-9eeb-f93319b76c99" />



## Result:
Thus the program was executed and the output was verified successfully.
