2주차 연습문제 내용


```c  //더하기 뺴기 곱하기 나누기
#include <std.io>

int main(void) {
  intx,y;
  
  printf("숫자 입력1: \n");
  scanf("%d",&x);
  printf("숫자 입력2: \n");
  scanf("%d",&y);
  
  printf("%d + %d = %d\n",x,y,x+y);
  printf("%d - %d = %d\n",x,y,x-y);
  printf("%d * %d = %d\n",x,y,x*y);
  printf("%d / %d = %d\n",x,y,x/y);
  return 0;
  }
  
  ```c //원의 면적 계산
  #include <std.io>

int main(void) {
  float r=0.0,s=0.0;
  printf("반지름을 입력하시오: \n");
  scanf("%f",&r)
  s = r * r * 3.14;
  printf("원의 면적:%f",s)
  return 0;
  }
  
  
