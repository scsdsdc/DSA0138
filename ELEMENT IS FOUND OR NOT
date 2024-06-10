#include <stdio.h>

int linearSearch(int arr[], int size, int target) {
    for (int i = 0; i < size; i++) {
        if (arr[i] == target) {
            return i;
    }
    return -1; 
}

int main() {
    int arr[] = {10, 20, 30, 40, 50};
    int size = sizeof(arr) / sizeof(arr[0]);
    int target = 30;
    
    int index = linearSearch(arr, size, target);
    if (index == -1) {
        printf("Element not found in the array.\n");
    } else {
        printf("Element found at index %d.\n", index);
    }
    
    return 0;
}
