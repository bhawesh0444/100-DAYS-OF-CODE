Q133: Create an enum for months and print how many days each month has.

/*
Sample Test Cases:
Input 1:
FEB
Output 1:
28 or 29 days

*/

//Solution:

#include <stdio.h>
#include <string.h>

enum Month { JAN, FEB, MAR, APR, MAY, JUN, JUL, AUG, SEP, OCT, NOV, DEC };

int main() {
    char s[10];
    scanf("%s", s);

    enum Month m;

    if(strcmp(s,"JAN")==0) m = JAN;
    else if(strcmp(s,"FEB")==0) m = FEB;
    else if(strcmp(s,"MAR")==0) m = MAR;
    else if(strcmp(s,"APR")==0) m = APR;
    else if(strcmp(s,"MAY")==0) m = MAY;
    else if(strcmp(s,"JUN")==0) m = JUN;
    else if(strcmp(s,"JUL")==0) m = JUL;
    else if(strcmp(s,"AUG")==0) m = AUG;
    else if(strcmp(s,"SEP")==0) m = SEP;
    else if(strcmp(s,"OCT")==0) m = OCT;
    else if(strcmp(s,"NOV")==0) m = NOV;
    else m = DEC;

    if(m == FEB)
        printf("28 or 29 days");
    else if(m==APR || m==JUN || m==SEP || m==NOV)
        printf("30 days");
    else
        printf("31 days");

    return 0;
}
