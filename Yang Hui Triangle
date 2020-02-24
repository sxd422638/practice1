#include<stdio.h>
int main(){
    int row = 1;
    int col;
    int i, j;
    printf("请输入你想打印多少行的杨辉三角:");
    scanf("%d", &col);
    printf("1\n");
    for(i = 2; i <= col; i++){
        printf("1 ");
        for(j = 1; j <= i - 2; j++)
            printf("%-2d ",(row = (i - j) * row / j));
            printf("1\n");
            row = 1;
    }
    return 0;
}
