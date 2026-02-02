Q137: Create an enum for user roles (ADMIN, USER, GUEST) and display messages based on role.

/*
Sample Test Cases:
Input 1:
GUEST
Output 1:
Welcome Guest!

*/

//Solution:
#include <stdio.h>
#include <string.h>

enum Role { ADMIN, USER, GUEST };

int main() {
    char s[20];
    scanf("%s", s);

    enum Role r;

    if(strcmp(s, "ADMIN") == 0) r = ADMIN;
    else if(strcmp(s, "USER") == 0) r = USER;
    else r = GUEST;

    if(r == ADMIN) printf("Welcome Admin!");
    else if(r == USER) printf("Welcome User!");
    else printf("Welcome Guest!");

    return 0;
}
