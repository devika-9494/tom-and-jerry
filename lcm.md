# tom-and-jerry
#include<stdio.h>
int lcm(int a,int b);
int main()
{
  int num1,num2,LCM;
  printf("entry any two numbers to findlcm:");
  scanf(%d%d",&num1,&num2);
    if(num1>num2)
      LCM=lcm(num2,num1);
    else
      LCM=LCM(num1,num2);
  printf("LCM of %d and %d=%d",num1,num2,LCM);
  return 0;
  }
  
