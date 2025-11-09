Q109: Write a program to take an integer array arr and an integer k as inputs. Print the maximum sum of all the subarrays of size k.

/*
Sample Test Cases:
Input 1:
arr[100, 200, 300, 400] = , k = 2
Output 1:
700

Input 2:
arr[1, 4, 2, 10, 23, 3, 1, 0, 20] = , k = 4
Output 2:
39

Input 3:
arr[100, 200, 300, 400] = , k = 1
Output 3:
400

*/

//Solution:
#include <stdio.h>

int main() {
    int arr[100], n, k, i, j, sum, maxSum = -1;
    scanf("%d", &n);
    for (i = 0; i < n; i++)
        scanf("%d", &arr[i]);
    scanf("%d", &k);
    for (i = 0; i <= n - k; i++) {
        sum = 0;
        for (j = i; j < i + k; j++)
            sum += arr[j];
        if (sum > maxSum)
            maxSum = sum;
    }
    printf("%d\n", maxSum);
    return 0;
}
