# C语言100题

## 1~10

### 1. 生成不重复的三位数

有 1、2、3 三个数字，能组成多少个互不相同且无重复数字的三位数

```c
#include <stdio.h>

int main()
{
    int Len = 0;
    for(int i = 1;i<4;i++)
    {
        for(int j =1;j<4;j++)
        {
            for(int x = 1;x<4;x++)
            {
                if(i!=j && j!= x && i!=x)
                {
                    printf("%d%d%d " , i,j,x);
                    Len++;
                }
            }
        }
    }
    printf("\n共有%d个",Len);
}

```

---

### 2. 根据企业利润计算奖金

* 利润低于或等于 10 万元，奖金为10%
* 10~20之间 为 7.5%
* 20~40 为 5%
* 40~60 为 3%
* 60~100 为 1.5%
* 100+ 为 1%
* 键入利润，得奖金

```c
#include <stdio.h>

int main()
{
    int i;
    printf("请键入利润\n");
    scanf("%d",&i);
    printf("奖金应为");
    int prize;
    int getLen(int i);
    getLen(i);
    switch(getLen(i))
    {
        case 1:
            prize = i*0.1;
            break;
        case 2:
            prize = (i-100000)*0.075;
            prize+=10000;
            break;
        case 4:
            prize = (i-200000)*0.05;
            prize+=17500;
            break;
        case 6:
            prize = (i-400000)*0.03;
            prize+=27500;
            break;
        case 10:
            prize = (i-600000)*0.015;
            prize+=33500;
            break;
        case 0:
            prize = (i-1000000)*0.01;
            prize+=39500;
            break;
        default:
            printf("%d" , getLen(i));
    }
    printf("%d" , prize);
}
int getLen(int i)
{
    if(i<=100000)
        return 1;
    else if(i<=200000)
        return 2;
    else if(i<=400000)
        return 4;
    else if(i<=600000)
        return 6;
    else if(i<=1000000)
        return 10;
    else
        return 0;
}

```

---

### 3.求完全平方数

一个整数，它加上100后是一个完全平方数(为某个数的平方)，再加上168又是一个完全平方数，求该数

---

### 4.判断某日期是今年的第几天

```c
# include <stdio.h>
/*
    键入日期，求该日期是今年的第多少天
*/
int main()
{
    int year,month,day,days;
    _Bool r;
    printf("请输入年份(YYYY)");
    scanf("%d" , &year);
    printf("请输入月份(MM)");
    scanf("%d" , &month);
    printf("请输入日(DD)");
    scanf("%d" , &day);

    // 判断是否为闰年
    if(year%4==0 && year%100!=0)
    {
        r=1;
    }
    else
    {
        r=0;
    }

    // 计算日
    switch(month)
    {
        case 12:
            days+=31;
        case 11:
            days+=30;
        case 10:
            days+=31;
        case 9:
            days+=30;
        case 8:
            days+=31;
        case 7:
            days+=31;
        case 6:
            days+=30;
        case 5:
            days+=31;
        case 4:
            days+=30;
        case 3:
            days+=31;
        case 2:
            if(r)
                days+=29;
            else
                days+=28;
        case 1:
            days+=0;
    }
    days += day;
   printf("输入的日期为%d%d%d 为今年的第%d天" , year,month,day,days);
}
```

---

### 5.三个数大小排序

```c
#include <stdio.h>
/*
    键入三个整数，按顺序从大到小输出
*/
int main()
{
    int a,b,c,x;
    printf("请输入第一个数字");
    scanf("%d" , &a);
    printf("请输入第二个数字");
    scanf("%d" , &b);
    printf("请输入第三个数字");
    scanf("%d" , &c);

// 排序
    a<b ? x=a,a=b,b=x : x;
    b<c ? x=b,b=c,c=x : x;
    a<b ? x=a,a=b,b=x : x;
        
    printf("从大到小排列为%d>%d>%d" , a,b,c);
}

```

---

### 6.使用*输出C

```c
#include <stdio.h>
/*
    用*号输出字母c
*/
int main()
{
    int len,copyLen;
    printf("请输入宽度(3~10)");
    scanf("%d" , &len);
    for(int i = 0; i<len;i++)
    {
        printf("* ");
    }
    printf("\n");
    for(int i = 0; i<len;i++)
    {
        printf("*\n");
    }
    for(int i = 0; i<len;i++)
        {
            printf("* ");
        }
        printf("\n");
    
}

```

---

### 7.输出特殊图案

```c
#include <stdio.h>
/*
    输出特殊字符
    Linux环境 a = 32,b = 33
    windows a=176 , b = 219
    !   !
     ! ! 
      !
     ! !
    !   !
*/
int main()
{
    char a = 32,b=33;
    printf("%c%c%c%c%c\n" , b,a,a,a,b);
    printf("%c%c%c%c%c\n" , a,b,a,b,a);
    printf("%c%c%c%c%c\n" , a,a,b,a,a);
    printf("%c%c%c%c%c\n" , a,b,a,b,a);
    printf("%c%c%c%c%c\n" , b,a,a,a,b);
}

```

---

### 8.九九乘法表

```c
#include <stdio.h>
/*
    输出99乘法表
*/
int main()
{
    for(int i = 1;i<=9;i++)
    {
        for(int j = 1;j<=i;j++)
        {
            printf("%d×%d=%d " , j,i,i*j);
        }
        printf("\n");
    } 
}

```

---

### 9. 输出国际象棋棋盘

```c
#include <stdio.h>
/*
    输出国际象棋棋盘
*/
int main()
{
    int w = 0;
    for (int i = 0; i < 8; i++)
    {
        for (int j = 0; j < 4; j++)
        {
            if (w == 0)
            {
                printf("██  ");
            }
            else
            {
                printf("  ██");
            }
        }
        w = !w;
        printf("\n");
    }
}

```

---

### 10. 打印楼梯图案和笑脸

这题目给我看闷了

---

## 11~20

### 11. 兔子生崽

```c
#include <stdio.h>
/*
    兔子生崽：有一对兔子，从出生后第三个月起每个月都生一对兔子
        小兔子长到第三个月后每个月又生一对兔子
        假如兔子都不死，问每个月的兔子为多少(输出40个月)
        斐波那契数列 ，下个月是上两个月之和
        1,1,2,3,5,8,13
        2 2
        2 2
        22 4
        222 6
        22222 10
*/
int main()
{
    int arr[40] = {};
    for(int i = 0;i<40;i++)
    {
        if(i<2)
        {
            arr[i] = 2;
        }
        else
        {
            arr[i] = arr[i-1]+arr[i-2];
        }
    }
    printf("%d",arr[39]);
}

```

## 更多题型

[点击查看更多](Language/C/moreCase)
