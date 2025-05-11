# EX 18 C program to find frequency of a character in the given input.
## DATE: 11/05/2025
## AIM:
To write a C program to find frequency of a character in the given input.

## Algorithm
1.Start the program and declare a string and a character variable.

2.Read the string and the character from the user.

3.Traverse the string using a loop.

4.Count how many times the given character appears.

5.Display the frequency of the character.
## Program:
```
/*
C program to find frequency of a character in the given input.
Developed by: Kamalesh S
RegisterNumber:  212223060108
*/

#include <stdio.h>

int main()
{
    char str[100], ch;
    int i, count = 0;

    printf("Enter a string: ");
    scanf("%s", str);

    printf("Enter a character to find frequency: ");
    scanf(" %c", &ch);  // space before %c handles newline

    for(i = 0; str[i] != '\0'; i++)
    {
        if(str[i] == ch)
        {
            count++;
        }
    }

    printf("Frequency of '%c' = %d\n", ch, count);

    return 0;
}


```

## Output:

![image](https://github.com/user-attachments/assets/cac82c2e-4700-4dce-ba29-a5edb5e4d38a)


## Result:
Thus the program was executed and the output was verified successfully.
