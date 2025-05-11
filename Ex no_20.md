# EX 20 C program to convert the given string to lowercase without using string functions.
## DATE: 11/05/2025
## AIM:
To write a C program to convert the given string to lowercase without using string functions.

## Algorithm
1.Start the program and declare a character array for the string.

2.Read the string input from the user.

3.Traverse each character of the string using a loop.

4.If a character is uppercase (A–Z), convert it to lowercase by adding 32.

5.Display the modified lowercase string.  

## Program:
```
/*
C program to convert the given string to lowercase without using string functions.
Developed by: Kamalesh S
RegisterNumber:  212223060108
*/
#include <stdio.h>

int main()
{
    char str[100];
    int i;

    printf("Enter a string: ");
    scanf("%s", str);

    for(i = 0; str[i] != '\0'; i++)
    {
        if(str[i] >= 'A' && str[i] <= 'Z')
        {
            str[i] = str[i] + 32;
        }
    }

    printf("Lowercase string: %s\n", str);

    return 0;
}


```

## Output:

![image](https://github.com/user-attachments/assets/13426c74-c70c-4390-8bce-0d04b96ebca9)


## Result:
Thus the program was executed and the output was verified successfully.
