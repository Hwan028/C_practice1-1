4주차 연습문제

```c
#include <stdio.h>

int main(void) {

    int num1, num2, result;
    char op;

    printf("수식을 입력하세요:");
    scanf("%d %c %d",&num1, &op, &num2);

    switch (op)
    {
    case '+':
        result = num1 + num2;
        break;
    
    case '-':
        result = num1 - num2;
        break;

    case '*':
        result = num1 * num2;
        break;

    case '/':
        result = num1 / num2;
        break;

    case '%':
        result = num1 % num2;

    default:
        printf("지원되지 않는 연산자 입니다.");
        break;
    }

    printf("%d %c %d = %d\n",num1, op, num2, result);

    return 0;
}

```c
#include <stdio.h> 
int main(void) 
{
int x=0, y=0; 
int result;
result = 2 > 3 || 6 > 7; 
printf("%d", result);
result = 2 || 3 && 3 > 2; 
printf("%d", result);
result = x = y = 1; 
printf("%d", result);
result = - ++x + y--; 
printf("%d", result);
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

#include <stdio.h> 
int main(void) 
{
double f_temp; 
double c_temp;
printf("화씨온도를  입력하시오"); 
scanf("%lf", &f_temp);
}
c_temp = 5.0 / 9.0 * (f_temp - 32);
printf("섭씨온도는  %f입니다", c_temp); //5/9 면 0이됨 주의
return 0;
}
