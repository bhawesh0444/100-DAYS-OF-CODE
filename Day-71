Q121: Write a C program that creates a text file named info.txt in write mode. The program should take the user’s name and age as input, and write them to the file using fprintf(). After writing, display a message confirming that the data was successfully saved.

/*
Sample Test Cases:
Input 1:
Name: Rahul, Age: 23
Output 1:
File created successfully! Data written to info.txt

*/

//Solution:

#include <stdio.h>

int main() {
    char name[100];
    int age;

    scanf("%s", name);
    scanf("%d", &age);

    FILE *fp = fopen("info.txt", "w");
    if(fp == NULL) return 0;

    fprintf(fp, "Name: %s\nAge: %d\n", name, age);
    fclose(fp);

    printf("File created successfully! Data written to info.txt");
    return 0;
}
