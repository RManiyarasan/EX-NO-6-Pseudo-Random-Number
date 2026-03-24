# EX-NO-6-Pseudo-Random-Number
## NAME : MANIYARASAN R
## REG.NO : 212224040185
## DATE : 14-02-2026

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:

```
#include <stdio.h> 
#include <stdlib.h> 
#include <time.h> 
int main() { 
int i, n; 
srand(time(0)); 
printf("Enter how many pseudorandom numbers you want to generate: "); 
scanf("%d", &n); 
printf("Generating %d pseudorandom numbers between 0 and 99:\n", n); 
for (i = 0; i < n; i++) { 
int randomNumber = rand() % 100; 
printf("%d ", randomNumber); 
} 
printf("\n"); 
return 0; 
} 
```

# OUTPUT:
![WhatsApp Image 2026-02-14 at 11 23 58 AM](https://github.com/user-attachments/assets/4f676cc8-4582-45ce-9bb2-172645003b38)


# RESULT:
Thus the implementation of Pseudo Random Number Generation is Successfull.
