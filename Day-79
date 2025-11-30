Q129: A file numbers.txt contains a list of integers separated by spaces. Read all integers, compute their sum and average, and print both.

/*
Sample Test Cases:
Input 1:
File: numbers.txt (Content: 10 20 30 40 50)
Output 1:
Sum = 150
Average = 30.00

*/

//Solution:

#include <stdio.h>

int main() {
    FILE *fp = fopen("numbers.txt", "r");
    if(fp == NULL) return 0;

    int x, sum = 0, count = 0;

    while(fscanf(fp, "%d", &x) == 1) {
        sum += x;
        count++;
    }

    fclose(fp);

    printf("Sum = %d\n", sum);
    if(count > 0)
        printf("Average = %.2f\n", (float)sum / count);

    return 0;
}
