# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```C
#include <stdio.h>
#include <stdlib.h>  
#include <time.h>   

int main() {
   
    srand(time(0));

    int n;
    printf("Enter the number of random numbers to generate: ");
    scanf("%d", &n);

    printf("Generated random numbers:\n");
    for (int i = 0; i < n; i++) {
        int random_number = rand();
        printf("%d\n", random_number);
    }

    return 0; 
}

```
# OUTPUT:
<img width="556" height="350" alt="image" src="https://github.com/user-attachments/assets/3f2f1e45-f5bd-4349-a4dc-df6ec7ddead7" />

# RESULT:
Thus , thePseudo-Random-Number is implemented successfully.
