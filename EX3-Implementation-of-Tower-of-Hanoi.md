# EX3 Implementation of Tower of Hanoi
## AIM:
To write a C program to implement Tower of Hanoi

## Algorithm
1. Start the program.
2. Define the priority() function to return the priority of operators.
3. Initialize the string containing operators and operands.
4. Loop through each character in the string.
6. For each operator, call the priority() function to determine its priority.
7. Print the operator and its corresponding priority level.  

## Program:
```
/*
Program to implement Tower of Hanoi
Developed by: T. Gayathri
RegisterNumber:  212223100007

#include <stdio.h>

void TOH(int n, char source, char dest, char aux) {
    if (n == 1) {
        printf("%c to %c\n", source, dest);
        return;
    }
    TOH(n - 1, source, aux, dest);
    printf("%c to %c\n", source, dest);
    TOH(n - 1, aux, dest, source);
}
*/
```

## Output:
![image](https://github.com/user-attachments/assets/cf59e47a-61a2-4b6e-97e6-2a68a54c9e90)



## Result:
Thus, the C program to implement Tower of Hanoi using recursion is implemented successfully.
