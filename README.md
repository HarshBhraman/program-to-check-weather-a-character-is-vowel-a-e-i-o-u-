//Write a program to check whether a character is a vowel (a, e, i, o, u).

#include <stdio.h>

int main() {
    char c;

    printf("Enter any character: ");
    scanf(" %c", &c);  // Note the space before %c to consume any leftover newline

    // Check for lowercase and uppercase vowels
    if (c == 'a' || c == 'e' || c == 'i' || c == 'o' || c == 'u' ||
        c == 'A' || c == 'E' || c == 'I' || c == 'O' || c == 'U') {
        printf("Given input is a vowel.\n");
    } else {
        printf("Given input is not a vowel.\n");
    }

    return 0;
}
