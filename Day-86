Q136: Use enum to represent menu choices (ADD, SUBTRACT, MULTIPLY) and perform operations using switch.

/*
Sample Test Cases:
Input 1:
ADD 10 20
Output 1:
30

*/

//Solution:

#include <stdio.h>
#include <string.h>

enum Choice { ADD, SUBTRACT, MULTIPLY };

int main() {
    char op[20];
    int a, b;
    scanf("%s %d %d", op, &a, &b);

    enum Choice c;

    if(strcmp(op, "ADD") == 0) c = ADD;
    else if(strcmp(op, "SUBTRACT") == 0) c = SUBTRACT;
    else c = MULTIPLY;

    switch(c) {
        case ADD: printf("%d", a + b); break;
        case SUBTRACT: printf("%d", a - b); break;
        case MULTIPLY: printf("%d", a * b); break;
    }

    return 0;
}
