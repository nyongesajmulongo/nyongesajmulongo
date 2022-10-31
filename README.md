/* Program that stimulates a simple calculator that perfom simple arthmetic like addition, subtraction, multplication, division 
and modulus.
Written by:Jack Nyongesa Mulongo
Date:31/10/2022
*/

include<stdio.h>
int main(void)
{
int a;
int b;
char c;
int chouice;

printf("%d:\n","Enter two intergral values\n");
scanf("%d %d,&a, &b);
printf("%d:\n","Enter choice\n");

printf("\nMenu");
printf("\n1.addition");
printf("\n2.subtraction");
printf("\n.3 multiplication");
printf("\n4. division");
printf("\n5.modulus");

switch (choice)
{
case 1:c=a+b;
printf("the results of addition is %d",c);
break;

case 2:c=a-b;
printf("the results of subtraction is %d",c);
break;

case 3: c=a*b;
printf("the result of multiplication is %d",c);
break;

case 4:c=a/b;
printf("the result of division is %d",c);
break;

case 5; c=a%d;
printf("the  result of modulus is %d",c);
break;

default:
printf("\n Invalid entry);

}

return 0;
}// Waaaah ikazi si mchezo mkuuu...Hailambii.

