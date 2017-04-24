# cydia_s
first c-program

#include<stdio.h>
#include<string.h>
int main()
{
char a[20],b=7,c[10];
int i;
gets(a);
for(i=0;i<strlen(a);i++)
{
c[i]=a[i]^b;
printf("%c\t",c[i]);	
}
} 
