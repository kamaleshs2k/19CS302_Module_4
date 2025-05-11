# EX 16 C program to find minimum between three fraction numbers using conditional operator.
## DATE: 11/05/2025
## AIM:
To write a C program to find minimum between three fraction numbers using conditional operator.

## Algorithm
1.Start the program and declare three float variables.

2.Read three fractional numbers from the user.

3.Use nested conditional (?:) operators to find the minimum.

4.Store the result in a separate variable.

5.Display the minimum number. 

## Program:
```
/*
C program to find minimum between three fraction numbers using conditional operator.
Developed by: Kamalesh S
RegisterNumber:  212223060108
*/
#include <stdio.h>

int main()
{
    float a, b, c, min;

    printf("Enter three fractional numbers: ");
    scanf("%f %f %f", &a, &b, &c);

    min = (a < b) ? ((a < c) ? a : c) : ((b < c) ? b : c);

    printf("Minimum = %.2f\n", min);

    return 0;
}


```

## Output:
![image](https://github.com/user-attachments/assets/fb9e7da4-e9fd-44c7-b9b3-45397142355d)



## Result:
Thus the program was executed and the output was verified successfully.
