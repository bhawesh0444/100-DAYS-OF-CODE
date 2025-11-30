Q120: Write a program to take a string input. Change it to sentence case.

/*
Sample Test Cases:
Input 1:
str = I am trying to build logic.
Output 1:
I Am Trying To Build Logic

Input 2:
str = The classes are supposed to start early.
Output 2:
The Classes Are Supposed To Start Early.

Input 3:
str = We are going to look at 26 different test cases.
Output 3:
We Are Going To Look At 26 Different Test Cases.

*/

//Solution:

#include <stdio.h>
#include <ctype.h>

int main() {
    char s[100005];
    fgets(s, sizeof(s), stdin);

    int cap = 1;
    for(int i = 0; s[i]; i++) {
        if(cap && s[i] >= 'a' && s[i] <= 'z')
            s[i] = s[i] - 'a' + 'A';
        else if(!cap && s[i] >= 'A' && s[i] <= 'Z')
            s[i] = s[i] - 'A' + 'a';

        if(s[i] == ' ')
            cap = 1;
        else
            cap = 0;
    }

    printf("%s", s);
    return 0;
}
