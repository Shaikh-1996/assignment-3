# assignment-3
# Write a program in c that uses a 
# for loop to print out the multiplication table 
# of a given number entered by the user 

#include <stdio.h>

int main() {
    int num;

    printf("Enter a number: ");
    scanf("%d", &num);

    printf("Multiplication table of %d:\n", num);
    for (int i = 1; i <= 10; i++) {
        printf("%d x %d = %d\n", num, i, num*i);
    }

    return 0;
}
