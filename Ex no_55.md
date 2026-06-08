# EX 55 C The five letters A, E, I, O and U are called vowels. All other alphabets except these 5 vowels are called consonants.

## DATE:
## AIM:
The five letters A, E, I, O and U are called vowels. All other alphabets except these 5 vowels are called consonants.

## Algorithm
1. Start the program.
2. Read a character from the user.
3. Check whether the character is one of the vowels:
   A, E, I, O, U
   a, e, i, o, u
4. If the character matches any vowel, print "Vowel".
5. Otherwise, print "Consonant".
6. Stop the program.

## Program:
```
#include<stdio.h>
int main()
{
    char ch;
    scanf("%c",&ch);
    if(ch=='a'||ch=='e'||ch=='i'||ch=='o'||ch=='u'||ch=='A'||ch=='E'||ch=='I'||ch=='O'||ch=='U')
    {
        printf("%c is a vowel.",ch);
    }
    else
    {
        printf("%c is a consonant.",ch);
    }
}
```

## Output:

<img width="1631" height="376" alt="Screenshot (55)(1)_31269" src="https://github.com/user-attachments/assets/6d549c7b-946e-468f-8619-05930c32d617" />




## Result:
Thus the program was executed and the output was verified successfully.
