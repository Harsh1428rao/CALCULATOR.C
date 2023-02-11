# CALCULATOR.C
CALCULATOR CODE WITH THE HELP OF C PROGRAMMING.
#include<stdio.h>
int main()
{
	float a,b;
	int c;
	printf("1.ADDITION\n2.SUBTRACTION\n3.DIVISION\n4.MULTIPLICATION");
	printf("\nENTER THE CHOICE: ");
	scanf("%d",&c);
	switch(c)
	{
		case 1:
			printf("\nENTER THE NUMBER A: ");
	scanf("%f",&a);
	printf("ENTER THE NUMBER A: ");
	scanf("%f",&b);
	
			printf("ADIITION OF A AND B: %.1f ",(a+b));
			break;
		case 2:
			printf("\nENTER THE NUMBER A: ");
			scanf("%f",&a);
			printf("ENTER THE NUMBER A: ");
			scanf("%f",&b);
			printf("SUBTRACTION OF A AND B: %.1f",(a-b));
			break;
		case 3:
			printf("\nENTER THE NUMBER A: ");
			scanf("%f",&a);
			printf("ENTER THE NUMBER A: ");
			scanf("%f",&b);
			printf("DIVISION OF A AND B: %.1f",(a/b));
			break;
		case 4:
			printf("\nENTER THE NUMBER A: ");
			scanf("%f",&a);
			printf("ENTER THE NUMBER A: ");
			scanf("%f",&b);
			printf("MULTIPLICATION OF A AND B: %.1f",a*b);
			break;
		default:
			printf("INVALID");
	}
	return 0;
}
