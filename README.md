#include <stdio.h>
int main()
{
int n, i = 1;
int factorial = 1;
printf("Enter a number: ");
scanf("%d", &n);
while (i <= n) {
  factorial *= i;
  i++;
}
printf("Factorial = %d\n", factorial);
printf("\n25331A05I6");
return 0;
}
