Q125: Open an existing file in append mode and allow the user to enter a new line of text. Append the text at the end without overwriting existing content.

/*
Sample Test Cases:
Input 1:
Existing File: data.txt (Content before execution: Hello world)
User Input: This is appended text.
Output 1:
File updated successfully with appended text.

*/

//Solution:

#include <stdio.h>

int main() {
    char filename[100];
    char line[200];

    scanf("%s", filename);
    getchar();
    fgets(line, sizeof(line), stdin);

    FILE *fp = fopen(filename, "a");
    if(fp == NULL) return 0;

    fputs(line, fp);
    fclose(fp);

    printf("File updated successfully with appended text.");
    return 0;
}
