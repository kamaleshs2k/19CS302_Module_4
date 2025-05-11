# EX 19 C program to perform basic left and right shift operations on a given integer and display the result.
## DATE: 11/05/2025
## AIM:
To write a C program to perform basic left and right shift operations on a given integer and display the result.

## Algorithm
1.Start the program and declare variables for the number and shift count.

2.Read an integer and number of shift positions from the user.

3.Perform left shift (num << shift) and right shift (num >> shift).

4.Store and display the results of both shift operations.

5.Show how the bits are moved during the operation.

## Program:
```
/*
C program to perform basic left and right shift operations on a given integer and display the result.
Developed by: Kamalesh S
RegisterNumber:  212223060108
*/
#include <stdio.h>

int main()
{
    int num, shift, leftResult, rightResult;

    printf("Enter an integer: ");
    scanf("%d", &num);

    printf("Enter number of positions to shift: ");
    scanf("%d", &shift);

    leftResult = num << shift;
    rightResult = num >> shift;

    printf("Left Shift (%d << %d) = %d\n", num, shift, leftResult);
    printf("Right Shift (%d >> %d) = %d\n", num, shift, rightResult);

    return 0;
}


```

## Output:

![image](https://github.com/user-attachments/assets/7e1f8167-cf1b-4924-b1d2-7027ad836b93)


## Result:
Thus the program was executed and the output was verified successfully.
