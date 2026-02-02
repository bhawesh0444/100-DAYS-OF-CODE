Q145: Return a structure containing top student's details from a function.

/*
Sample Test Cases:
Input 1:
3 students: Riya 101 89, Karan 102 96, Meena 103 92
Output 1:
Top Student: Karan | Roll: 102 | Marks: 96

*/

//Solution:
#include <stdio.h>

struct Student {
    char name[100];
    int roll;
    int marks;
};

struct Student getTopStudent(struct Student s[], int n) {
    int top = 0;
    for(int i = 1; i < n; i++)
        if(s[i].marks > s[top].marks)
            top = i;
    return s[top];
}

int main() {
    int n;
    scanf("%d", &n);

    struct Student s[n];
    for(int i = 0; i < n; i++)
        scanf("%s %d %d", s[i].name, &s[i].roll, &s[i].marks);

    struct Student top = getTopStudent(s, n);

    printf("Top Student: %s | Roll: %d | Marks: %d",
           top.name, top.roll, top.marks);

    return 0;
}
