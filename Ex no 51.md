# EX 51 C program to reverse a string.
## DATE:
## AIM:
To write a C program to reverse a string.

## Algorithm
1. Start
2. Accept a string from the user.
3. Determine the length of the string.
4. Initialize two pointers:- One at the beginning (i = 0).
5. One at the end (j = length - 1).
6. Swap the characters at positions i and j.
7. Increment i and decrement j.
8. Repeat steps 5 and 6 until i is greater than or equal to j.

## Program:
```
#include <stdio.h>
#include <string.h>

int main() {
    char str[100], reversed[100];
    int length, i;

    printf("Enter a string: ");
    scanf("%s", str);  

    length = strlen(str);

    for (i = 0; i < length; i++) {
        reversed[i] = str[length - i - 1];
    }
    reversed[length] = '\0'; 

    printf("Reversed string: %s\n", reversed);
    
    return 0;
}
```

## Output:

<img width="772" height="334" alt="image" src="https://github.com/user-attachments/assets/32d29f3b-4d72-4f28-ae20-a30a564b4815" />



## Result:
Thus the program was executed and the output was verified successfully.
