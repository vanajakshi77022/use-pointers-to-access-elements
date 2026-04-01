# use-pointers-to-access-elements
#include <stdio.h>
int main() {
    printf("25331A05E8\n");
    int arr[5] = {10, 20, 30, 40, 50};
    int *ptr;  
    int i;
    ptr = arr;
    printf("Accessing array elements using pointers:\n");

    for(i = 0; i < 5; i++) {
        printf("Element %d = %d\n", i, *(ptr + i));
    }
    return 0;
}
