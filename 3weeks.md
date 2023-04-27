3주차 연습문제

```c
#include <stdio.h>
int main(void)
{

    char code = 'A';

    printf("%d %d %d \n", code, code + 1, code + 2);
    printf("%c %c %c \n", code, code + 1, code + 2);

    return 0;
}

```c
#include <stdio.h>

int main(void) {

    int money, change, price, c1000, c500, c100;

    printf("물건 값: ");
    scanf("%d",&price);

    printf("넣은 돈: ");
    scanf("%d",&money);

    change = money - price;

    c1000 = change / 1000;
    change = change % 1000;

    c500 = change / 500;
    change = change % 500;

    c100 = change / 100;

    printf("\n천원권: %d장\n", c1000);
    printf("오백원 동전: %d개\n", c500);
    printf("백원 동전: %d개\n", c100);


    return 0;

}

```c
#include <stdio.h>

int main(void) {

    int year, result;

    printf("연도를 입력하세요: ");
    scanf("%d",&year);

    result = ((year % 4 == 0) && (year % 100 != 0)) || (year % 400 == 0);

    printf("result=%d \n",result);

    return 0;

}

```c
#include <stdio.h>
int main(void) {

    int months, days;

    printf("달 : ");
    scanf("%d",&months);

    switch (months)
    {
    case 2:
        days = 28;
        break;

    case 4:
    case 6:
    case 9:
    case 11:
        days = 30;
        break;

    default:
        days = 31;
        break;
    }

    printf("%d월의 일수는 %d일",months, days);

    return 0;
}
