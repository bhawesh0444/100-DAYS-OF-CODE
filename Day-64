Q114: Write a program to take a string s as input. The task is to find the length of the longest substring without repeating characters. Print the length as output.

/*
Sample Test Cases:
Input 1:
s = "abcabcbb"
Output 1:
3

Input 2:
s = "bbbbb"
Output 2:
1

Input 3:
s = "pwwkew"
Output 3:
3

*/

//Solution:

#include <stdio.h>
#include <string.h>

int main() {
    char s[100005];
    if(scanf("%100004s", s)!=1) return 0;
    int last[256];
    for(int i=0;i<256;i++) last[i] = -1;
    int start = 0, maxlen = 0;
    int n = strlen(s);
    for(int i=0;i<n;i++) {
        unsigned char c = s[i];
        if(last[c] >= start) start = last[c] + 1;
        int cur = i - start + 1;
        if(cur > maxlen) maxlen = cur;
        last[c] = i;
    }
    printf("%d", maxlen);
    return 0;
}
