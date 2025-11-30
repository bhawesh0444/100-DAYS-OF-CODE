Q112: Write a program to take an integer array arr as input. The task is to find the maximum sum of any contiguous subarray using Kadane's algorithm. Print the maximum sum as output. If all elements are negative, print the largest (least negative) element.

/*
Sample Test Cases:
Input 1:
arr[] = [2, 3, -8, 7, -1, 2, 3]
Output 1:
11

Input 2:
arr[] = [-2, -4]
Output 2:
-2

Input 3:
arr[] = [5, 4, 1, 7, 8]
Output 3:
25

*/

//Solution:

#include <stdio.h>
#include <limits.h>

int main() {
    int n;
    scanf("%d", &n);

    int arr[n];
    for (int i = 0; i < n; i++)
        scanf("%d", &arr[i]);

    int max_so_far = INT_MIN;  
    int curr_sum = 0;           

    for (int i = 0; i < n; i++) {
        curr_sum += arr[i];

        if (curr_sum > max_so_far)
            max_so_far = curr_sum;

        
        if (curr_sum < 0)
            curr_sum = 0;
    }

    printf("%d", max_so_far);

    return 0;
}
