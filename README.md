#include <stdio.h>
void displayArray(int arr[], int size);
int main()
{
    printf("25331A05D6\n");
    int numbers[5] = {1,2,3,4,5};
    displayArray(numbers, 5);
     return 0;
     }

void displayArray(int arr[], int size) {
    int i;
    printf("Array elements are:\n");
    for (i = 0; i < size; i++)
{
    printf("%d ", arr[i]);
    }
    printf("\n");
}
