#鸡兔同笼
#include<stdio.h>  //鸡兔同笼
void main()
{
	int x,y,feet,head;
	printf("请输入头数: ");
	scanf("%d",&head);
	printf("请输入就叫数: ");
	scanf("%d",&feet);
	x=(4*head-feet)/2;
	y=head-feet;
	printf("输出记得数目:%d\n,输出图的数目:%d\n",x,y);
	
}
