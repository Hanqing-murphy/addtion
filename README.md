# addtion
站位专用

#include <stdio.h>

int main()
{
    printf("23+43=%d\n", 23+43);

    return 0;
}

4．找您多少元

#include <stdio.h>

int main()
{
    int price = 0;

    printf("请输入金额（元）：");
    scanf("%d", &price);

    int change = 100 - price;

    printf("找您%d元。\n", change);

    return 0;
