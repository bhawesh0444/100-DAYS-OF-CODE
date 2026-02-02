Q149: Use malloc() to allocate structure memory dynamically and print details.

/*
Sample Test Cases:
Input 1:
Student allocated dynamically with details: Tina 105 88
Output 1:
Name: Tina | Roll: 105 | Marks: 88

*/

//Solution:

#include <stdio.h>
#include <stdlib.h>

struct Student {
    char name[100];
    int roll;
    int marks;
};

int main() {
    struct Student *s = (struct Student*)malloc(sizeof(struct Student));
    if(s == NULL) return 0;

    scanf("%s %d %d", s->name, &s->roll, &s->marks);

    printf("Name: %s | Roll: %d | Marks: %d", s->name, s->roll, s->marks);

    free(s);
    return 0;
}
