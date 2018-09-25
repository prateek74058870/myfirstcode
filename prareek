   
#include<stdio.h>
#include<conio.h>
void main()
{
 int m,n,i,j,a[100],b[100],count;
 clrscr();
 printf("Enter no. of elements of 1st & 2nd sorted sets:->\n");
 scanf("%d%d",&m,&n);
 printf("\n enter first sorted  set:\n");
 for(i=0;i<m;i++)
 {
  scanf("%d",&a[i]);
 }
 printf("\n enter second sorted set:\n");
 for(j=0;j<n;j++)
 {
  scanf("%d",&b[j]);
 }
 printf("\n Diff. of two sorted array:->\n");
 for(i=0;i<m;i++)
 {
  printf("\t%d",a[i]);
 }
 for(i=0;i<n;i++)
 {
  count=0;
  for(j=0;j<m;j++)
  {
   if(a[j]==b[i])
    count++;
  }
  if(count==0)
  {
   printf("\t%d",b[i]);
  }
 }
 getch();
}
