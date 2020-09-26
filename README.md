# 555
#define _CRT_SECURE_NO_WARNINGS
#include<stdlib.h>
#include<stdio.h>
int main()
{
	float a, b, c, temp;
	printf("请输入a,b,c\n");
	scanf("%f,%f,%f", &a, &b, &c);
	if (a > b)
	{
		temp = a; a = b; b = temp;
	}
	if (a > c)
	{
		temp = a; a = c; c = temp;
	}
	if (b > c)
	{
		temp = b; b = c; c = temp;
	}
	printf("%7.2f,%7.2f,%7.2f", a, b, c);
	system("pause");
}
