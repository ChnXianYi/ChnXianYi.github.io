# 更多的例子

## 1~10

### 1. 顺时针旋进的螺旋方阵

![alt:'case1'](../../public/00001.jpg)

```c
# include <stdio.h>
#include <string.h>

int main()
{
    int n = 5;
    int arr[10][10];
    int len,copyLen;
    int value = 1;
    int x,y;
    int cir = 1; //1下2左3上0右
    float min = 1;
    printf("请输入n=");
    scanf("%d" , &len);
    copyLen = len;

        for(int i = 0;i<len;i++)
        {
            arr[0][i] = value++;
            printf("%d" , arr[0][i]);
            x=0;
            y=i;
        }
        len--;
        printf("\n一轮结束 x=%d y=%d len=%d min=%f value=%d\n" , x,y,len,min,value);

        while (len>0)
        {
                switch(cir)
            {
                case 1:
                    for(int i = 0;i<len;i++)
                    {
                        arr[++x][y]=value++;
                        printf("%d",arr[x][y]);
                    }
                    min-=0.5;
                    if(min == 0)
                    {
                        len--;
                        min = 1;
                    }
                    printf("\n一轮结束 x=%d y=%d len=%d min=%f value=%d\n" , x,y,len,min,value);
                    cir = 2;
                    break;//y不变x从上到下
                case 2:
                    for(int i = 0;i<len;i++)
                    {
                        arr[x][--y]=value++;
                        printf("%d",arr[x][y]);
                    }
                    min-=0.5;
                    if(min == 0)
                    {
                        len--;
                        min = 1;
                    }
                    printf("\n一轮结束 x=%d y=%d len=%d min=%f value=%d\n" , x,y,len,min,value);
                    cir = 3;
                    break;//x不变y从右到左
                case 3:
                    for(int i = 0;i<len;i++)
                    {
                        arr[--x][y]=value++;
                        printf("%d",arr[x][y]);
                    }
                    min-=0.5;
                    if(min == 0)
                    {
                        len--;
                        min = 1;
                    }
                    printf("\n一轮结束 x=%d y=%d len=%d min=%f value=%d\n" , x,y,len,min,value);
                    cir = 0;
                    break;//y不变x从下往上
                case 0:
                    for(int i = 0;i<len;i++)
                    {
                        arr[x][++y]=value++;
                        printf("%d",arr[x][y]);
                    }
                    min-=0.5;
                    if(min == 0)
                    {
                        len--;
                        min = 1;
                    }
                    printf("\n一轮结束 x=%d y=%d len=%d min=%f value=%d\n" , x,y,len,min,value);
                    cir = 1;
                    break;//x不变y从左往右
                default:printf("寄");
            }
        }
    for(int i = 0;i<copyLen;i++)
    {
        for(int j = 0;j<copyLen;j++)
        {
            printf("%d ",arr[i][j]);
        }
        printf("\n");
    }
}
```

### 2. 求个十百位只和和逆序

* 键入一个三位数，求出该三位数三位之和 与 将该三位数逆序排列输出

```c
#include <stdio.h>

int main()
{   
    int three,sum,new;
    printf("请输入一个三位数");
    scanf("%d" , &three);
    int o,t,h;
    o=three%10;
    t=(three%100-o)/10;
    h=(three-o-10*t)/100;
    sum = o+t+h;
    printf("三位数个位%d十位%d百位%d 和为%d\n" , o,t,h,sum);
    new = h+t*10+o*100;
    printf("逆序为%d" , new);
}
```
