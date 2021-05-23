# c-star-3
I used the (for) to take a picture of the star. ver3
#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>
int main() {
	int i, j, n;
	scanf("%d", &n);
	for (i = 1; i <= n; i++) {
		for (j = 1; j <= i; j++) {
			printf("*");
		}
		printf("\n");
	}
	for (i = n; i > 1; i--) {
		for (j = 1; j < i; j++) {
			printf("*");
		}
		printf("\n");
	}
	return 0;
}
