
#include <stdio.h>

int main() {
    int N;
    int sum = 0;

    printf("Enter N: ");
    scanf("%d", &N);

    for (int i = 1; i <= N; i++) {
        sum = sum + i;
    }

    printf("Sum = %d\n", sum);

    return 0;
}
