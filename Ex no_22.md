# EX 22 C program to count total number of even elements in an array using calloc().

## AIM:
To write a C program to count total number of even elements in an array using calloc().

## Algorithm
Start. Define a variables. Write program to count total number of even elements in an array using calloc(). Read the value using scanf. Ask the user to make an input. Print out the answer. End.

## Program:
```
/*
C program to count total number of even elements in an array using calloc().
Developed by:DUDEKULA HASEENA 
RegisterNumber: 212222063004
#include<stdio.h> 
#include<stdlib.h> 
int main()
{
int *arr,n,i,count=0; 
scanf("%d",&n); 
arr=(int*)calloc(1,sizeof(int)); 
for(i=0;i<n;i++)
{
scanf("%d",&arr[i]);
}
for(i=0;i<n;i++)
if(arr[i]%2==0) 
count++;
printf("Total even elements: %d",count);
}
*/
```

## Output:

<img width="899" height="268" alt="image" src="https://github.com/user-attachments/assets/296b131e-a40e-4235-b72c-b292d466600f" />


## Result:
Thus the program was executed and the output was verified successfully.
