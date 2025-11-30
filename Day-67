Q117: Write a program to take two sorted arrays of size m and n as input. Merge both the arrays such that the merged array is also sorted. Print the merged array.

/*
Sample Test Cases:
Input 1:
nums1 = [2,7,11,15] nums2 = [4,8,10]
Output 1:
2 4 7 8 10 11 15

Input 2:
nums1 = [1,2,7] nums2 = [9,10,17]
Output 2:
1 2 7 9 10 17

Input 3:
nums1 = [-10,-2,7] nums2 = [-3, -1, 7]
Output 3:
-10 -3 -2 -1 7 7

*/

//Solution:
#include <stdio.h>

int main() {
    int m, n;
    scanf("%d", &m);
    int a[m];
    for(int i = 0; i < m; i++) scanf("%d", &a[i]);

    scanf("%d", &n);
    int b[n];
    for(int i = 0; i < n; i++) scanf("%d", &b[i]);

    int i = 0, j = 0;
    while(i < m && j < n) {
        if(a[i] <= b[j]) {
            printf("%d ", a[i]);
            i++;
        } else {
            printf("%d ", b[j]);
            j++;
        }
    }

    while(i < m) {
        printf("%d ", a[i]);
        i++;
    }

    while(j < n) {
        printf("%d ", b[j]);
        j++;
    }

    return 0;
}
