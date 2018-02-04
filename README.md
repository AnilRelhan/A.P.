# A.P.
Arithmatic Progression
#include<stdio.h>
int main()
{
	int a, n, d, l, sum;
	printf("First term of A.P.\n");
	scanf("%d", &a);
	
	printf("Total Number of terms of A.P.\n");
	scanf("%d", &n);

	printf("Common Difference of A.P.\n");
	scanf("%d", &d);
	
	l = a + (n-1)*d;        //mathematical formula for last term
	
	sum = ( n * (a + l) ) / 2;    //mathematical formula for sum of n terms
	
	printf("Last Term is : %d\n", l);
	printf("Sum of A.P. is : %d\n", sum);
	
	return 0;
}
