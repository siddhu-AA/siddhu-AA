#include <stdio.h>
#include <stdlib.h>
int compare(const void *a, const void *b) 
{
    return (*(int*)b - *(int*)a);
}
int main() {
    int arr[] = {33,37,45,78};
    int n = sizeof(arr) / sizeof(arr[0]);
    qsort(arr, n, sizeof(int), compare);
    for (int i = 0; i < n; i++)
        printf("%d ", arr[i]);
    return 0;
}
