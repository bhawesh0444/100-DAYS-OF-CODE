Q132: Define an enum for traffic lights (RED, YELLOW, GREEN) and print 'Stop', 'Wait', or 'Go' based on its value.

/*
Sample Test Cases:
Input 1:
GREEN
Output 1:
Go

*/

//Solution:

#include <stdio.h>
#include <string.h>

enum Light { RED, YELLOW, GREEN };

int main() {
    char s[20];
    scanf("%s", s);

    enum Light signal;

    if(strcmp(s, "RED") == 0) signal = RED;
    else if(strcmp(s, "YELLOW") == 0) signal = YELLOW;
    else signal = GREEN;

    if(signal == RED) printf("Stop");
    else if(signal == YELLOW) printf("Wait");
    else printf("Go");

    return 0;
}
