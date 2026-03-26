# EX 21 C program to calculate the area of a triangle using pointer.

## AIM:
To write a C program to calculate the area of a triangle using pointer.

## Algorithm
Start. Declare three variable value of type float. Prompt the user to enter values. Read the values using scanf. Find the area of triangle using formula End.
## Program:
```
/*
C program to calculate the area of a triangle using pointer.
Developed by: DUDEKULA HASEENA
RegisterNumber: 212222063004
#include <stdio.h>
int main() {
 float base, height, area;
 float *pBase = &base, *pHeight = &height;
 scanf("%f", pBase);
 scanf("%f", pHeight);
 area = 0.5 * (*pBase) * (*pHeight);
 printf("%.2f\n", area);
}
*/
```

## Output:

<img width="462" height="172" alt="image" src="https://github.com/user-attachments/assets/ca221a7e-64ad-4171-958e-989b441f4376" />


## Result:
Thus the program was executed and the output was verified successfully.
