Q140: Define a struct with enum Gender and print person's gender.

/*
Sample Test Cases:
Input 1:
Gender=MALE
Output 1:
Male

*/

//Solution:
#include <stdio.h>
#include <string.h>

enum Gender { MALE, FEMALE, OTHER };

struct Person {
    enum Gender g;
};

int main() {
    char s[20];
    scanf("%s", s);

    struct Person p;

    if(strcmp(s, "MALE") == 0) p.g = MALE;
    else if(strcmp(s, "FEMALE") == 0) p.g = FEMALE;
    else p.g = OTHER;

    if(p.g == MALE) printf("Male");
    else if(p.g == FEMALE) printf("Female");
    else printf("Other");

    return 0;
}
