# 1-hello-c
# 2주차 C 실습
#include <stdio.h>

void main(void) {
    char name[] = "Aarons";
    float age = 43.5;

    printf("Hello, my name is %s\n", name);
    printf("");
    printf("\tI am %.1f years old/n/n.", age);

    return 0; //0:양수 1:음수
}