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
  printf("%d * %d = %d \n",n,i,n*i);
  i++;
  }
  return 0;
 }

```c
#include <stdio.h>

int main() {
    for(int i=0;i<=5;i++)
      {
        for(int j=0;j<5-i;j++)
        {
        printf(" ");
        }
        for(int s=0;s<2*i-1;s++)
        {
        printf("*");
        }
        for(int j=0;j<5-i;j++) //공백은 앞에만 있으면 되니 어차피 안써도 됐던거였음 뒤에 
        {
        printf(" ");
        }
        printf("\n");
      }
}
