#include<stdio.h>

int main()
{
	int i,n,sum=0;
	printf("Enter the number :");
	scanf("%d",&n);
	for(;n!=0;)
	{
		i=n%10;
		sum=sum+i;
		n=n/10;
	}
	printf("The sum of the digit is : %d",sum);
} 
