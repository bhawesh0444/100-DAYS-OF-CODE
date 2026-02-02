Q147: Store employee data in a binary file using fwrite() and read using fread().

/*
Sample Test Cases:
Input 1:
Employee details entered and stored in file.
Output 1:
Displays employee data read from file.

*/

//Solution:

#include <stdio.h>

struct Employee {
    char name[100];
    int id;
    float salary;
};

int main() {
    struct Employee e, r;

    scanf("%s %d %f", e.name, &e.id, &e.salary);

    FILE *fp = fopen("emp.dat", "wb");
    if(fp == NULL) return 0;

    fwrite(&e, sizeof(e), 1, fp);
    fclose(fp);

    fp = fopen("emp.dat", "rb");
    if(fp == NULL) return 0;

    fread(&r, sizeof(r), 1, fp);
    fclose(fp);

    printf("Name: %s | ID: %d | Salary: %.
