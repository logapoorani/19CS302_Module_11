# EX 55 C program to find a square of number using function with arguments without return type.
## DATE:
## AIM:
To write a C program to find a square of number using function with arguments without return type.

## Algorithm
1. Start
2. Define a function findSquare(num) that takes an integer argument.
3. Inside the function, compute num * num and display the result.
4. In the main() function:
5. Accept an integer input from the user.
6. Call findSquare(number) with the input value.
7. End  

## Program:
```
#include <stdio.h>

void findSquare(int num) {
    printf("Square of %d is: %d\n", num, num * num);
}

int main() {
    int number;
    printf("Enter a number: ");
    scanf("%d", &number);
    
    findSquare(number);
    
    return 0;
}
```

## Output:

<img width="259" height="47" alt="image" src="https://github.com/user-attachments/assets/a0fb7afc-b07a-42ce-9d67-6c11c2510017" />



## Result:
Thus the program was executed and the output was verified successfully.
