6주차 연습문제

```c
#include <stdio.h>

int main(void) 
{ 
  int n,i=1;
  
  printf("출력하고 싶은 단:");
  scanf("%d",&n);
  
  while(i<=9)
  {
  printf("%d * i = %d",n,n*i);
  }
  
  return 0;
}

```c
#include <stdio.h>

int main(void) 
{ 
  int n,i=1;
  
  printf("출력하고 싶은 단:");
  scanf("%d",&n);
  
  while(i<=9)
  {
  printf("%d * %d = %d \n",n,i,n*i);
  i++;
  }
  return 0;
 }
