#include<stdio.h>

int sum of digit(int n)
{
  if( n==0)
  return 0;
  return (n%10+ sum of digit(n/10))
 }
 int main()
 {
  int num =12345;
  int result = sum of digit(num);
  printf("sum of digits in %d is %d\n", num,result);
  result 0;
}
