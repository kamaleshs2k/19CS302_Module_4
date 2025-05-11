# EX 17 C Program to compare two strings without using strcmp().
## DATE: 11/05/2025
## AIM:
To write a C Program to compare two strings without using strcmp().

## Algorithm
1.Start the program and declare two character arrays for the strings.

2.Read both strings from the user.

3.Use a loop to compare characters at each position of both strings.

4.If all characters match and both end together, they are equal.

5.Display whether the strings are equal or not.
## Program:
```
/*
 C Program to compare two strings without using strcmp().
Developed by: Kamalesh S
RegisterNumber:  212223060108
*/
#include <stdio.h>

int main()
{
    char str1[100], str2[100];
    int i = 0, isEqual = 1;

    printf("Enter first string: ");
    scanf("%s", str1);

    printf("Enter second string: ");
    scanf("%s", str2);

    while(str1[i] != '\0' || str2[i] != '\0')
    {
        if(str1[i] != str2[i])
        {
            isEqual = 0;
            break;
        }
        i++;
    }

    if(isEqual)
    {
        printf("Strings are equal.\n");
    }
    else
    {
        printf("Strings are not equal.\n");
    }

    return 0;
}


```

## Output:

![image](https://github.com/user-attachments/assets/343ed2b6-d84a-4f63-83cb-e5682f69efa2)


## Result:
Thus the program was executed and the output was verified successfully.
