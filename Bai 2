#include <stdio.h>

int isPerfectSquare(int n) {
    int i = 1;
    while (i * i <= n) {
        if (i * i == n) {
            return 1;
        }
        i++;
    }
    return 0;
}

void printPerfectSquares(int n) {
    printf("Cac so chinh phuong nho hon %d la:\n", n);
    for (int i = 1; i < n; i++) {
        if (isPerfectSquare(i)) {
            printf("%d ", i);
        }
    }
    printf("\n");
}

int main() {
    int n;
    printf("Nhap vao so nguyen duong n: ");
    scanf("%d", &n);
    printPerfectSquares(n);
    return 0;
}
