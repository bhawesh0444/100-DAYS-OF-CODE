Q142: Store details of 5 students in an array of structures and print all.

/*
Sample Test Cases:
Input 1:
Details of 5 students (Name, Roll, Marks)
Output 1:
Tabular list of all 5 students with their details

*/

//Solution:

#include <stdio.h>

struct Student {
    char name[100];
    int roll;
    int marks;
};

int main() {
    struct Student s[5];

    for(int i = 0; i < 5; i++)
        scanf("%s %d %d", s[i].name, &s[i].roll, &s[i].marks);

    for(int i = 0; i < 5; i++)
        printf("%s %d %d\n", s[i].name, s[i].roll, s[i].marks);

    return 0;
}
