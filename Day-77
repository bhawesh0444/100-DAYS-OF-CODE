Q127: Write a program that reads text from input.txt, converts all lowercase letters to uppercase, and writes the result to output.txt.

/*
Sample Test Cases:
Input 1:
Input File (input.txt): Hello World\nC programming
Output 1:
Output File (output.txt): HELLO WORLD\nC PROGRAMMING

*/

//Solution:

#include <stdio.h>
#include <ctype.h>

int main() {
    FILE *fp1 = fopen("input.txt", "r");
    if(fp1 == NULL) return 0;

    FILE *fp2 = fopen("output.txt", "w");
    if(fp2 == NULL) return 0;

    int ch;
    while((ch = fgetc(fp1)) != EOF) {
        if(ch >= 'a' && ch <= 'z')
            ch = ch - 'a' + 'A';
        fputc(ch, fp2);
    }

    fclose(fp1);
    fclose(fp2);

    return 0;
}
