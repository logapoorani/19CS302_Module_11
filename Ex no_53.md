# EX 53 C program to input marks of five subjects of a student and calculate total, average and percentage of all subjects. How to calculate total, average and percentage in C programming. Logic to find total, average and percentage in C program. use float data type for all variable.
## DATE:
## AIM:
c program to input marks of five subjects of a student and calculate total, average and percentage of all subjects.
## Algorithm
1. Start
2. Declare five float variables for marks:
  sub1, sub2, sub3, sub4, sub5
3. Declare float variables:
  total, average, percentage
4. Input marks of the five subjects.
5. Calculate total marks:
  total = sub1 + sub2 + sub3 + sub4 + sub5
6. Calculate average marks:
  average = total / 5
7. Calculate percentage:
  percentage = (total / 500) * 100
  (Assuming each subject is out of 100 marks)
8. Display total, average, and percentage.  
9. stop.
## Program:
```
#include<stdio.h>
int main()
{
    int m1,m2,m3,m4,m5;
    scanf("%d%d%d%d%d",&m1,&m2,&m3,&m4,&m5);
    float total,avg,per;

    total=m1+m2+m3+m4+m5;
    avg=total/5;
    per=(avg*100)/100;
    printf("%.6f\n%.6f\n%.6f",total,avg,per);
}
```

## Output:

<img width="1101" height="584" alt="Screenshot (56)_25624" src="https://github.com/user-attachments/assets/da9d8bfd-19ff-43a8-b107-64acbb1e32c1" />




## Result:
Thus the program was executed and the output was verified successfully.
