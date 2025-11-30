Q123: Read a text file and count the total number of characters, words, and lines. A word is defined as a sequence of non-space characters separated by spaces or newlines.

/*
Sample Test Cases:
Input 1:
File: sample.txt (Content: Hello world\nThis is C programming)
Output 1:
Characters: 31
Words: 5
Lines: 2

*/

//Solution:

#include <stdio.h>
#include <ctype.h>

int main() {
    FILE *fp = fopen("sample.txt", "r");
    if(fp == NULL) return 0;

    int ch, chars = 0, words = 0, lines = 0;
    int inword = 0;

    while((ch = fgetc(fp)) != EOF) {
        chars++;

        if(ch == '\n')
            lines++;

        if(!isspace(ch) && inword == 0) {
            inword = 1;
            words++;
        } else if(isspace(ch)) {
            inword = 0;
        }
    }

    fclose(fp);

    printf("Characters: %d\n", chars);
    printf("Words: %d\n", words);
    printf("Lines: %d\n", lines);

    return 0;
}
