#include<stdio.h>
int main()
{
int X,P,count=0;
scanf("%d%d",&X,&P);
while(X>0)
  {
    X=((X*P)/100);
    count++;
  }
printf("%d",count);
return 0;
}

  
  
  
