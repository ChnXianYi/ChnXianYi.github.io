# C

markdown

1、下面程序的输出是(<small class="pass">D</small>)

```markdown

# include<stdio.h>

void main()

{ int k=11;

printf("k=%d,k=%o,k=%x\n",k,k,k);

}

 A. k=11,k=12,k=11 B. k=11,k=13,k=13

 C. k=11,k=013,k=0xb D. k=11,k=13,k=b

```

---

2、在下列选项中,不正确的赋值语句是(<small class="pass">D</small>).

```markdown

  A. ++t;   B. n1=(n2=(n3=0));

  C. k=i=j;   D. a=b+c=1;

```

---

3、下面合法的C语言字符常量是(<small class="pass">A</small>).

```markdown

  A. '\t'   B. "A"   C. 65   D. A

```

---

4、表达式: 10!=9的值是(<small class="pass">D</small>).

```markdown

  A. true   B. 非零值   C. 0   D. 1

```

---

5、C语言提供的合法的数据类型关键字是(<small class="pass">B</small>).

```markdown

  A. Double   B. short   C. integer   D. Char

```

---

6、字符(char)型数据在微机内存中的存储形式是(<small class="pass">D</small>).

```markdown

  A. 反码   B. 补码   C. EBCDIC码   D. ASCII码

```

---

7、C语言程序的基本单位是(<small class="pass">C</small>).

```markdown

  A. 程序行   B. 语句   C. 函数   D. 字符

```

---

8、设 int a=12,则执行完语句a+=a-=a*a后,a的值是(<small class="pass">D</small>)

```markdown

  A. 552   B. 264   C. 144   D. -264

```

---

9、执行下面程序中的输出语句后,输出结果是(<small class="pass">B</small>).

```markdown

# include<stdio.h>

void main()

{int a;

printf("%d\n",(a=3*5,a*4,a+5));

}

  A. 65   B. 20   C. 15   D. 10

```

---

10、下面程序的输出是(<small class="pass">B</small>).

```markdown

# include<stdio.h>

void main()

{int x=023;

printf("%d\n",--x);

}

  A. 17   B. 18   C. 23   D. 24

```

---

11、下面程序的输出的是(<small class="pass">C</small>).

```markdown

# include<stdio.h>

void main()

{int x=10,y=3;

printf("%d\n",y=x/y);

}

  A. 0   B. 1   C. 3   D. 不确定的值

```

---

12、已知字母A的ASCII码为十进制的65,下面程序的输出是(<small class="pass">A</small>).

```markdown

# include<stdio.h>

void main()

{char ch1,ch2;

ch1='A'+'5'-'3';

ch2='A'+'6'-'3';

printf("%d,%c\n",ch1,ch2);

}

  A. 67,D   B. B,C   C. C,D   D. 不确定的值

```

---

13、若要求在if后一对圆括号中表示a不等于0的关系,则能正确表示这一关系的表达式为(<small class="pass">D</small>).

```markdown

  A. a<>0   B. !a   C. a=0   D. a

```

---

14、以下程序的输出结果是(<small class="pass">D</small>).

```markdown

# include<stdio.h>

void main()

{ int x=10,y=10;

printf("%d %d\n",x--,--y);

}

  A. 10 10   B. 9 9   C. 9 10   D. 10 9

```

---

15、设有如下定义:

int x=10,y=3,z;

则语句

printf("%d\n",z=(x%y,x/y));

的输出结果是(<small class="pass">D</small>).

```markdown

  A. 1   B. 0   C. 4   D. 3

```

---

16、为表示关系x≥y≥z,应使用C语言表达式(<small class="pass">A</small>).

```markdown

  A. (x>=y)&&(y>=z)   B. (x>=y)AND(y>=z)

  C. (x>=y>=z)   D. (x>=y) & (y>=z)

```

---

17、C语言中非空的基本数据类型包括(<small class="pass">B</small>).

```markdown

  A. 整型,实型,逻辑型   B. 整型,实型,字符型

  C. 整型,字符型,逻辑型

  D. 整型,实型,逻辑型,字符型

```

---

18、若x和y都是int型变量,x=100,y=200,且有下面的程序片段:

printf("%d",(x,y));

上面程序片段的输出结果是(<small class="pass">A</small>).

```markdown

  A. 200   B. 100

  C. 100 200   D. 输出格式符不够,输出不确定的值

```

---

19、阅读下面的程序

```c
# include<stdio.h>

void main()

{

char ch;

scanf("%3c",&ch);

printf("%c",ch);

}
```

如果从键盘上输入

abc<回车>

则程序的运行结果是(<small class="pass">A</small>).

```markdown

  A. a   B. b   C. c   D. 程序语法出错

```

---

20、阅读下面的程序

```c
# include<stdio.h>

void main()

{

int i,j;

i=010;

j=9;

printf("%d,%d",i-j,i+j);

}
```

则程序的运行结果是(<small class="pass">D</small>).

```markdown

  A. 1,19   B. -1,19   C. 1,17   D. -1,17

```

---

21、阅读下面的程序

```c
# include<stdio.h>

void main()

{

int i,j,m,n;

i=8;j=10;

m=++i;

n=j++;

printf("%d,%d,%d,%d",i,j,m,n);

}
```

程序的运行结果是(<small class="pass">C</small>).

```markdown

  A. 8,10,8,10   B. 9,11,8,10

  C. 9,11,9,10   D. 9,10,9,11

```

---

22、已知a=12,则表达式a+=a-=a*=a的结果是(<small class="pass">A</small>).

```markdown

  A. 0   B. 144   C. 12   D. -264

```

---

23、若已定义int a,则表达式a=10,a+10,a++的值是(<small class="pass">B</small>).

```markdown

  A. 20   B. 10   C. 21   D. 11

```

---

24、阅读下面的程序

```c
# include<stdio.h>

void main()

{

int i,j;

scanf("%3d%2d",&i,&j);

printf("i=%d,j=%d\n",i,j);

}
```

如果从键盘上输入1234567<回车>,则程序的运行结果是(<small class="pass">D</small>).

```markdown

  A. i=123,j=4567   B. i=1234,j=567

  C. i=1,j=2   D. i=123,j=45

```

---

25、下面程序的输出结果是(<small class="pass">D</small>).

```markdown

# include<stdio.h>

void main()

{

int a=-1, b=4, k;

k=(++a<=0)&&(b--<=0);

printf("%d,%d,%d\n",k,a,b);

}

  A. 1,1,2   B. 1,0,3   C. 0,1,2   D. 0,0,3

```

---

26、下面程序的输出结果是(<small class="pass">A</small>).

```markdown

# include<stdio.h>

void main()

{

int a=5,b=3;

float x=3.14, y=6.5;

printf("%d,%d\n",a+b!=a-b,x<=(y-=6.1));

}

  A. 1,0   B. 0,1   C. 1,1   D. 0,0

```

---

27、执行下面程序段后,输出结果是(<small class="pass">A</small>).

```markdown

int a;

int b=65536;

a=b;

printf("%d\n",a);

  A. 65536   B. 0   C. -1   D. 1

```

---

28、若有以下定义和语句:

int a=010, b=0x10, c=10;

printf("%d,%d,%d\n",a,b,c);

则输出结果是(<small class="pass">B</small>).

```markdown

  A. 10,10,10   B. 8,16,10   C. 8,10,10   D. 8,8,10

```

---

29、已知有double型变量x=2.5,y=4.7,整型变量a=7,

则表达式 x+a%3*(int)(x+y)%2/4 的值是(<small class="pass">B</small>).

```markdown

  A. 2.4   B. 2.5   C. 2.75   D. 0

```

---

30、若已定义x和y是整型变量,x=2;,则表达式y=2.75+x/2的值是(<small class="pass">C</small>).

```markdown

  A. 5.5   B. 5   C. 3   D. 4.0

```

---

31、以下程序的输出结果是(<small class="pass">D</small>).

```markdown

# include<stdio.h>

void main()

{

int a=12, b=12;

printf("%d,%d\n",--a,++b);

}

  A. 10,10   B. 12,12   C. 11,10   D. 11,13

```

---

32、设有以下语句:int x=10;x+=3+x%(3),则x的值是.(<small class="pass">A</small>)

```markdown

  A. 14   B. 15   C. 11   D. 12

```

---

33、若d为double型变量,则表达式d=1,d+5,d++的值是(<small class="pass">D</small>).

```markdown

  A. 1   B. 6.0   C. 2.0   D. 1.0

```

---

34、表达式5!=3的值是(<small class="pass">D</small>).

```markdown

  A. T   B. 非零值   C. 0   D. 1

```

---

35、若有定义int a=12,n=5,则表达式a%=(n%2)运算后,a的值(<small class="pass">A</small>).

```markdown

  A. 0   B. 1   C. 12   D. 6

```

---

36、若有定义int x=3,y=2和float a=2.5,b=3.5,则表达式:(x+y)%2+(int)a/(int)b的值是(<small class="pass">D</small>).

```markdown

  A. 0   B. 2   C. 1.5   D. 1

```

---

37、在C语言中,以下叙述不正确的是(<small class="pass">A</small>).

```markdown

  A. 在C程序中,无论是整数还是实数,都能被准确无误的表示

  B. 在C程序中,变量名代表存储器中的一个位置

  C. 静态变量的生存期与整个程序的生存期相同

  D. C语言中变量必须先定义后引用

```

---

38、C语言中的变量名只能由字母,数字和下划线三种字符组成,且第一个字符(<small class="pass">C</small>).

```markdown

  A. 必须为字母

  B. 必须为下划线

  C. 必须为字母或下划线

  D. 可以是字母,数字或下划线中的任意一种

```

---

39、设有说明:char w; int x; float y; double z; 则表达式: w*x+z-y值的数据类型是(<small class="pass">D</small>).

```markdown

  A. float   B. char   C. int   D. double

```

---

40、一个C语言的执行是从(<small class="pass">A</small>).

```markdown

  A. 本程序的主函数开始,到本程序的主函数结束

  B. 本程序的第一个函数开始,到本程序的最后一个函数结束

  C. 本程序的主函数开始,到本程序的最后一个函数结束

  D. 本程序的第一个函数开始,到本程序的主函数结束

```

---

41、设a为整型变量,不能正确表达数学关系10<a<15的C语言表达式是(<small class="pass">A</small>).

```markdown

  A. 10<a<15   B. a==11||a==12||a==13||a==14

  C. a>10&&a<15   D. !(a<=10)&&!(a>=15)

```

---

42、下列程序执行后的输出结果是(<small class="pass">C</small>).

```markdown

# include <stdio.h>

void main( )

{ int a=5,b=60,c;

if (a<b)

{c=a*b;printf("%d*%d=%d\n",b,a,c);}

else

{c=b/a;printf("%d/%d=%d\n",b,a,c);}

}

  A. 60/5=12   B. 300   C. 60*5=300   D. 12

```

---

43、如果c为字符型变量，判断c是否为空格不能使用(<small class="pass">A</small>).(假设已知空格ASCII码为32)

```markdown

  A. if(c=='32')   B. if(c==32)

  C. if(c=='\40')   D. if(c==' ')

```

---

44、运行下面程序时，若从键盘输入"3,5<CR>"，则程序的输出结果是(<small class="pass">D</small>).

```markdown

# include <stdio.h>

void main( )

{

int x,y;

scanf("%d,%d",&x,&y);

if (x==y)

printf("x==y");

else if (x>y)

printf("x>y");

else

printf("x<y");

}

  A. 3<5   B. 5>3   C. x>y   D. x<y

```

---

45、运行下面程序时，若从键盘输入数据为"6,5,7<CR>"，则输出结果是(<small class="pass">C</small>).

```markdown

# include <stdio.h>

void main( )

{ int a,b,c;

scanf("%d,%d,%d",&a,&b,&c);

if (a>b)

if (a>c)

printf("%d\n",a);

else

printf("%d\n",c);

else

if (b>c)

printf("%d\n",b);

else

printf("%d\n",c);

}

  A. 5   B. 6   C. 7   D. 不定值

```

---

46、执行下面程序时,若从键盘输入"2<CR>"，则程序的运行结果是(<small class="pass">A</small>).

```markdown

# include <stdio.h>

void main( )

{ int k; char cp;

cp=getchar( );

if (cp>='0' && cp<='9')

k=cp-'0';

else if (cp>='a' && cp<='f')

k=cp-'a'+10;

else k=cp-'A'+10;

printf("%d\n",k);

}

  A. 2   B. 4   C. 1   D. 10

```

---

47、运行下面程序时,从键盘输入"2.0<CR>"，则输出结果是(<small class="pass">B</small>).

```markdown

# include <stdio.h>

void main( )

{ float a,b;

scanf("%f",&a);

if (a<0.0) b=0.0;

else if ((a<0.5) && (a!=2.0)) b=1.0/(a+2.0);

else if (a<10.0) b=1.0/2;

else b=10.0;

printf("%f\n",b);

}

  A. 0.000000   B. 0.500000

  C. 1.000000   D. 0.250000

```

---

48、执行下面程序后,运行结果是(<small class="pass">A</small>).

```markdown

# include <stdio.h>

void main( )

{ int x=41,y=1;

if (x%3==0 && x%7==0)

{ y+=x;printf("y=%d\n",y);}

else

{y=x;printf("y=%d",y);}

}

  A. y=41   B. y=43   C. y=42   D. y=1

```

---

49、运行下面程序时，从键盘输入"12,34,9<CR>"，则输出结果是(<small class="pass">A</small>).

```markdown

# include <stdio.h>

void main( )

{ int x,y,z;

scanf("%d,%d,%d",&x,&y,&z);

if (x<y)

if (y<z)printf("%d\n",z);

else printf("%d\n",y);

else if (x<z)printf("%d\n",z);

else printf("%d\n",x);

}

  A. 34   B. 12   C. 9   D. 不确定的值

```

---

50、运行下面程序时，从键盘输入字母H，则输出结果是(<small class="pass">C</small>).

```markdown

# include <stdio.h>

void main( )

{ char ch;

ch=getchar( );

switch(ch)

{ case 'H':printf("Hello!\n");

case 'G':printf("Good morning!\n");

default:printf("Bye_Bye!\n");

}

}

  A. Hello!   B. Hello!

Good Morning!

  C. Hello!   D. Hello!

Good morning! Bye_Bye!

Bye_Bye!

```

---

51、执行下列程序段后的输出结果是(<small class="pass">A</small>).

```markdown

int x=1,y=1,z=1;

x+=y+=z;

printf("%d\n",x<y?y:x);

  A. 3   B. 2   C. 1   D. 4

```

---

52、设ch是char型变量,值为'A',则表达式ch=(ch>='A' && ch<='Z')?ch+32:ch的值是(<small class="pass">B</small>).

```markdown

  A. Z   B. a   C. z   D. A

```

---

53、下面程序的输出结果是(<small class="pass">C</small>).

```markdown

# include <stdio.h>

void main( )

{ int x=8,y=-7,z=9;

if (x<y)

if (y<0) z=0;

else z-=1;

printf("%d\n",z);

}

  A. 8   B. 1   C. 9   D. 0

```

---

54、运行下面程序时,若从键盘输入"5 <CR>",则程序的输出结果是(<small class="pass">B</small>).

```markdown

# include <stdio.h>

void main( )

{ int a ;

scanf("%d",&a);

if (a++>5)printf("%d\n",a);

else printf("%d\n",a--) ;

}

  A. 7   B. 6   C. 5   D. 4

```

---

55、运行下面程序时，若从键盘输入"3，4 <CR>"，则程序的输出结果是(<small class="pass">B</small>).

```markdown

# include <stdio.h>

void main( )

{ int a,b,s;

scanf("%d,%d",&a,&b);

s=a;

if (s<b) s=b;

s=s*s;

printf("%d\n",s) ;

}

  A. 14   B. 16   C. 18   D. 20

```

---

56、下列程序的执行结果是(<small class="pass">D</small>).

```markdown

# include <stdio.h>

void main( )

{ int x=0,y=1,z=0;

if (x=z=y)

x=3;

printf("%d,%d\n",x,z);

}

  A. 3,0   B. 0,0   C. 0,1   D. 3,1

```

---

57、假定等级和分数有以下对应关系：

等级：A 分数：85～100

　等级：B 分数：60～84

　等级：C 分数：60 以下

对于等级grade输出相应的分数区间，能够完成该功能的程序段是(<small class="pass">D</small>).

```markdown

  A. switch (grade)

{

case 'A':printf("85--100\n");

case 'B':printf("60--84\n");

case 'C':printf("60以下\n");

default:printf("等级错误!\n");

}

  B. switch (grade)

{

case 'A':printf("85--100\n");break;

case 'B':printf("60--84\n");

case 'C':printf("60以下\n");

default:printf(" 等级错误!\n");

}

  C. switch (grade)

{

case 'A':printf("85--100\n");break;

case 'B':printf("60--84\n");break;

case 'C':printf("60以下\n");

default:printf("等级错误!\n");

}

  D. switch (grade)

{

case 'A':printf("85--100\n");break;

case 'B':printf("60--84\n");break;

case 'C':printf("60以下 \n");break;

default:printf("等级错误!\n");

}

```

---

58、能够完成如下函数计算的程序段是(<small class="pass">B</small>).

```markdown

┌ -1 x<0

y= ┤ 0 x=0

└ 1 x>0

  A. y=1;   B. if (x>=0)

if(x!=0) if(x>0) y=1;

if(x>0) y=1; else y=0;

else y=0; else y=-1;

  C. y=0;   D. y=-1;

if (x>=0) if (x>0) y=1;

if (x>0) y=1; else y=0;

else y=-1;

```

---

59、有如下程序

```c
# include <stdio.h>

void main( )

{ float x=5.0,y;

if(x<0.0) y=0.0;

else if (x<10.0) y=1.0/x;

else y=1.0;

printf("%f\n",y);

}

```

该程序的输出结果是(<small class="pass">C</small>).

```markdown

  A. 0.000000   B. 0.50000

  C. 0.200000   D. 1.000000

```

---

60、以下程序的执行结果是(<small class="pass">B</small>).

```markdown

# include <stdio.h>

void main( )

{ int x=1,y=0;

switch (x)

{

case 1:

switch (y)

{

case 0:printf("first\n");break;

case 1:printf("second\n");break;

}

case 2:printf("third\n");

}

}

  A. first   B. first

second third

  C. first   D. second

third

```

---

61、以下程序的执行结果是(<small class="pass">A</small>).

```markdown

# include <stdio.h>

void main( )

{ int a,b,c,d,x;

a=c=0;

b=1;

d=20;

if (a) d=d-10;

else if(!b)

if (!c) x=15;

else x=25;

printf("d=%d\n",d);

}

  A. d=20   B. d=10   C. d=15   D. 25

```

---

62、有如下程序:

```c
# include <stdio.h>

void main( )

{ int a=2,b=-1,c=2;

if (a<b)

if (b<0) c=0;

else c++;

printf("%d\n",c);

}
```

该程序的输出结果是(<small class="pass">C</small>).

```markdown

  A. 0   B. 1   C. 2   D. 3

```

---

63、下列程序执行后的输出结果是(<small class="pass">B</small>).

```markdown

# include <stdio.h>

void main( )

{ int x,y=1,z;

if ((z=y)<0) x=4;

else if (y==0) x=5;

else x=6;

printf("%d,%d\n",x,y);

}

  A. 4,1   B. 6,1   C. 5,0   D. 出错信息

```

---

64、有如下程序

```c
# include <stdio.h>

void main( )

{ int x=1,a=0,b=0;

switch(x)

{

case 0: b++;

case 1: a++;

case 2: a++;b++;

}

printf("a=%d,b=%d\n",a,b);

}
```

该程序的输出结果是(<small class="pass">A</small>).

```markdown

  A. a=2,b=1   B. a=1,b=1   C. a=1,b=0   D. a=2,b=2

```

---

65、下面程序的输出结果是(<small class="pass">C</small>).

```markdown

# include <stdio.h>

void main( )

{ int a=-1,b=1,k;

if ((++a<0) && (b--<=0))

printf("%d %d\n",a,b);

else

printf("%d %d\n",b,a);

}

  A. -1 1   B. 0 1   C. 1 0   D. 0 0

```

---

66、假定w、x、y、z、m均为int型变量，有如下程序段：

w=1;x=2;y=3;z=4;

m=(w<x)?w:x; m=(m<y)?m:y; m=(m<z)?m:z;

则该程序段执行后，m的值是(<small class="pass">D</small>).

```markdown

  A. 4   B. 3   C. 2   D. 1

```

---

67、以下程序的输出结果是(<small class="pass">D</small>).

```markdown

main( )

{ int a=100;

if (a>100) printf("%d\n",a>100);

else printf("%d\n",a<=100);

}

  A. a<=100   B. 100   C. 0   D. 1

```

---

68、若执行下面的程序从键盘上输入9,则输出结果是.(<small class="pass">B</small>)

```markdown

# include <stdio.h>

void main( )

{int n;

scanf("%d",&n);

if (n++<10) printf("%d\n",n);

else printf("%d\n",n--);}

  A. 11   B. 10   C. 9   D. 8

```

---

69、以下程序输出结果是(<small class="pass">D</small>).

```markdown

# include <stdio.h>

void main( )

{ int m=4;

if (++m>5) printf("%d\n",m--);

else printf("%d\n",--m);

}

  A. 7   B. 6   C. 5   D. 4

```

---

70、若执行下面的程序从键盘上输入5,则输出结果是.

```c
# include <stdio.h>

void main( )

{int x;

scanf("%d",&x);

if (x++>5) printf("%d\n",x);

else printf("%d\n",x--);

}

  A. 7   B. 6   C. 5   D. 4

```

---

71、以下程序段运行结果是(<small class="pass">A</small>).

```markdown

int x=1,y=1,z=-1;

x+=y+=z;

printf("%d\n",x<y?y:x);

  A. 1   B. 2   C. 4   D. 不确定的值

```

---

72、有以下程序

```c
# include <stdio.h>

void main( )

{ int a,b,c=246;

a=c/100%9;

b=(-1)&&(-1);

printf("%d,%d\n",a,b);

}
```

输出结果是(<small class="pass">A</small>).

```markdown

  A. 2,1   B. 3,2   C. 4,3   D. 2,-1

```

---

73、运行下面程序时，若从键盘输入数据为"123"，

则输出结果是(<small class="pass">C</small>).

```markdown

# include "stdio.h"

void main()

{ int num,i,j,k,place;

scanf("%d",&num);

if (num>99)

place=3;

else if(num>9)

place=2;

else

place=1;

i=num/100;

j=(num-i*100)/10;

k=(num-i*100-j*10);

switch (place)

{ case 3: printf("%d%d%d\n",k,j,i);

break;

case 2: printf("%d%d\n",k,j);

break;

case 1: printf("%d\n",k);

}

}

  A. 123   B. 1,2,3   C. 321   D. 3,2,1

```

---

74、执行下列程序后的输出结果是(<small class="pass">D</small>).

```markdown

# include <stdio.h>

void main( )

{ int k=4,a=3,b=2,c=1;

printf("%d\n",k<a?k:c<b?c:a);

}

  A. 4   B. 3   C. 2   D. 1

```

---

75、以下条件表达式中能完全等价于条件表达式x的是(<small class="pass">B</small>).

```markdown

  A. (x==0)   B. (x!=0)   C. (x==1)   D. (x!=1)

```

---

76、若运行下面程序时,给变量a输入15,则输出结果是(<small class="pass">A</small>).

```markdown

# include <stdio.h>

void main( )

{ int a,b;

scanf("%d",&a);

b=a>15?a+10:a-10;

printf("%d\n",b) ;

}

  A. 5   B. 25   C. 15   D. 10

```

---

77、运行下面程序后,输出是(<small class="pass">D</small>).

```markdown

# include <stdio.h>

void main( )

{ int k=-3;

if (k<=0) printf("****\n");

else printf("####\n")

}

  A. ####

  B. ****

  C. ####****

  D. 有语法错误不能通过编译

```

---

78、执行下面程序的输出结果是(<small class="pass">C</small>).

```markdown

# include <stdio.h>

void main( )

{ int a=5,b=0,c=0;

if (a=a+b) printf("****\n");

else printf("####\n");

}

  A. 有语法错误不能编译

  B. 能通过编译，但不能通过连接

  C. 输出 ****

  D. 输出 ####

```

---

79、为了避免嵌套的if-else语句的二义性，C语言规定else总是与(<small class="pass">C</small>)组成配对关系.

```markdown

  A. 缩排位置相同的if

  B. 在其之前未配对的if

  C. 在其之前尚未配对的最近的if

  D. 同一行上的if

```

---

80、设x 、y 、z 、t均为int型变量,则执行以下语句后,t的值为(<small class="pass">C</small>).

```markdown

x=y=z=1;

t=++x || ++y && ++z;

  A. 不定值   B. 4   C. 1   D. 0

```

---

81、以下程序段(<small class="pass">C</small>).

```markdown

x=-1;

do

{

x=x*x;

} while (!x);

  A.是死循环   B.循环执行两次

  C.循环执行一次   D.有语法错误

```

---

82、对下面程序段描述正确的是(<small class="pass">B</small>).

```markdown

int x=0,s=0;

while (!x!=0) s+=++x;

printf("%d",s);

  A. 运行程序段后输出0

  B. 运行程序段后输出1

  C. 程序段中的控制表达式是非法的

  D. 程序段循环无数次

```

---

83、下面程序段的输出结果是(<small class="pass">C</small>).

```markdown

x=3;

do { y=x--;

if (!y) {printf("*");continue;}

printf("#");

} while(x=2);

  A. ##   B. ##*   C. 死循环   D.输出错误信息

```

---

84、下面程序的运行结果是(<small class="pass">B</small>).

```markdown

# include<stdio.h>

void main( )

{ int a=1,b=10;

do

{ b-=a;a++;

} while(b--<0);

printf("%d,%d\n",a,b);

}

  A. 3,11   B. 2,8   C. 1,-1   D. 4,9

```

---

85、下面程序段的运行结果是(<small class="pass">B</small>).

```markdown

int n=0;

while (n++<=2)

printf("%d",n);

  A. 012   B. 123   C. 234   D. 错误信息

```

---

86、下面程序段的运行结果是(<small class="pass">D</small>).

```markdown

int x=0,y=0;

while (x<15) y++,x+=++y;

printf("%d,%d",y,x);

  A. 20,7   B. 6,12   C. 20,8   D.8,20

```

---

87、下面程序的运行结果是(<small class="pass">B</small>).

```markdown

# include<stdio.h>

void main()

{ int s=0,i=1;

while (s<=10)

{ s=s+i*i;

i++;

}

printf("%d",--i);

}

  A. 4   B. 3   C. 5   D. 6

```

---

88、函数pi的功能是根据以下近似公式求π值：(<small class="pass">C</small>)

```markdown

(π*π)/6=1+1/(2*2)+1/(3*3)+..+1/(n*n)

请填空，完成求π的功能。

# include <math.h>

void main( )

{ double s=0.0; int i,n;

scanf("%ld",&n);

for(i=1;i<=n;i++)

s=s+_______ ;

s=(sqrt(6*s));

printf("s=%e",s);

}

  A. 1/i*i   B. 1.0/i*i   C. 1.0/(i*i)   D. 1.0/(n*n)

```

---

89、下面程序段的运行结果是(<small class="pass">B</small>).

```markdown

for(x=10;x>3;x--)

{ if(x%3) x--;

--x; --x;

printf("%d ",x);

}

  A. 6 3   B. 7 4   C. 6 2   D. 7 3

```

---

90、下面程序的运行结果是(<small class="pass">D</small>).

```markdown

# include<stdio.h>

void main( )

{ int a,b;

a=-1;

b=0;

do {

++a;

++a;

b+=a;

} while(a<9);

printf("%d\n",b);

}

  A. 34   B. 24   C. 26   D. 25

```

---

91、下面程序段的运行结果是(<small class="pass">D</small>).

```markdown

for(i=1;i<=5;)

printf("%d",i);

i++;

  A. 12345   B. 1234   C. 15   D. 无限循环

```

---

92、下面程序的输出结果是(<small class="pass">B</small>).

```markdown

# include<stdio.h>

void main( )

{ int n=4;

while (n--) printf("%d ",n--);

}

  A. 2 0   B. 3 1   C. 3 2 1   D. 2 1 0

```

---

93、以下程序运行后的输出结果是(<small class="pass">D</small>).

```markdown

# include<stdio.h>

void main()

{ int i=10,j=0;

do

{ j=j+1; i--;

}while(i>2);

printf("%d\n",j);

}

  A. 50   B. 52   C. 51   D. 8

```

---

94、以下函数的功能是：求x的y次方，请填空.(<small class="pass">C</small>)

```markdown

# include<stdio.h>

void main()

{ int i,x,y;

double z;

scanf("%d %d",&x,&y);

for(i=1,z=x;i<y;i++)

z=z*______ ;

printf("x^y=%e\n",z);

}

  A. i++   B. x++   C. x   D. i

```

---

95、有如下程序

```c
# include<stdio.h>

void main()

{ int x=23;

do

{ printf("%d",x--);

}while(!x);

}
```

该程序的执行结果是(<small class="pass">B</small>)

```markdown

  A. 321   B. 23

  C. 不输出任何内容   D. 陷入死循环

```

---

96、以下程序段的执行结果是(<small class="pass">C</small>).

```markdown

int i,j,m=0;

for(i=1;i<=15;i+=4)

for(j=3;j<=19;j+=4)

m++;

printf("%d\n",m);

  A. 12   B. 15   C. 20   D. 25

```

---

97、下面程序的输出结果是(<small class="pass">A</small>).

```markdown

# include<stdio.h>

void main( )

{ int i;

for(i=1;i<6;i++)

{ if (i%2!=0) {printf("#");continue;}

printf("*");

}

printf("\n");

}

  A. #*#*#   B. #####   C. *****   D. *#*#*

```

---

98、下面程序的输出结果是(<small class="pass">D</small>).

```markdown

# include<stdio.h>

void main( )

{ int x=10,y=10,i;

for(i=0;x>8;y=++i)

printf("%d %d ",x--,y);

}

  A. 10 1 9 2   B. 9 8 7 6

  C. 10 9 9 0   D. 10 10 9 1

```

---

99、执行以下程序后，输出的结果是(<small class="pass">D</small>).

```markdown

# include<stdio.h>

void main( )

{ int y=10;

do {y--;}

while (--y);

printf("%d\n",y--);

}

  A. -1   B. 1   C. 8   D. 0

```

---

100、有如下程序

```c
# include<stdio.h>

void main( )

{ int n=9;

while(n>6) {n--;printf("%d",n);}

}
```

该程序段的输出结果是(<small class="pass">B</small>).

```markdown

  A. 987   B. 876   C. 8765   D. 9876

```

---

101、有如下程序

```c
# include<stdio.h>

void main( )

{ int i,sum=0;

for(i=1;i<=3;sum++) sum+=i;

printf("%d\n",sum);

}
```

该程序的执行结果是(<small class="pass">C</small>).

```markdown

  A. 6   B. 3   C. 死循环   D. 0

```

---

102、以下循环体的执行次数是(<small class="pass">D</small>)

```markdown

# include<stdio.h>

void main( )

{ int i,j;

for(i=0,j=1; i<=j+1; i+=2, j--)

printf("%d \n",i);

}

  A. 3   B. 2   C. 1   D. 0

```

---

03、在执行以下程序时，如果从键盘上输入：ABCdef<回车>，则输出为(<small class="pass">B</small>).

```markdown

# include <stdio.h>

void main( )

{ char ch;

while ((ch=getchar( ))!='\n')

{ if (ch>='A' && ch<='Z') ch=ch+32;

else if (ch>='a' && ch<'z') ch=ch-32;

printf("%c",ch);

}

printf("\n");

}

  A. ABCdef   B. abcDEF   C. abc   D. DEF

```

---

104、下面程序的输出结果是(<small class="pass">D</small>).

```markdown

main( )

{

int i,k=0, a=0, b=0;

for(i=1;i<=4;i++)

{

k++;

if (k%2==0) {a=a+k; continue;}

b=b+k;

a=a+k;

}

printf("k=%d a=%d b=%d\n",k,a,b);

}

  A. k=5 a=10 b=4   B. k=3 a=6 b=4

  C. k=4 a=10 b=3   D. k=4 a=10 b=4

```

---

105、执行下面程序段后,k的值是(<small class="pass">D</small>).

```markdown

int i,j,k;

for(i=0,j=10;i<j;i++,j--)

k=i+j;

  A. 9   B. 11   C. 8   D. 10

```

---

106、下面程序是计算n个数的平均值,请填空.(<small class="pass">B</small>)

```markdown

# include<stdio.h>

void main( )

{ int i,n;

float x,avg=0.0;

scanf("%d",&n);

for(i=0;i<n;i++)

{ scanf("%f",&x);

avg=avg+______; }

avg=________;

printf("avg=%f\n",avg);

}

  A. i   B. x   C. x   D. i

avg/i avg/n avg/x avg/n

```

---

107、以下程序的功能是:从键盘上输入若干个学生的成绩, 统计并输出最高成绩和最低成绩,当输入负数时结束输入。请填空。(<small class="pass">D</small>)

```markdown

# include<stdio.h>

void main( )

{ float x,amax,amin;

scanf("%f",&x);

amax=x;

amin=x;

while (________ )

{ if (x>amax) amax=x;

if (______) amin=x;

scanf("%f",&x);

}

printf("\namax=%f\namin=%f\n",amax,amin);

}

  A. x<=0   B. x>0   C. x>0   D. x>=0

x>amin x<=amin x>amin x<amin

```

---

108、阅读以下程序，程序运行后的输出结果是(<small class="pass">B</small>).

```markdown

# include<stdio.h>

void main( )

{ int x;

for(x=5;x>0;x--)

if (x--<5) printf("%d,",x);

else printf("%d,",x++); }

  A. 4,3,2   B. 4,3,1,   C. 5,4,2   D. 5,3,1,

```

---

109、以下程序段的输出结果是(<small class="pass">C</small>).

```markdown

int k,n,m;

n=10;m=1;k=1;

while (k<=n) {m*=2;k+=4;}

printf("%d\n",m);

  A. 4   B. 16   C. 8   D. 32

```

---

110、下面程序的输出结果是(<small class="pass">B</small>).

```markdown

# include<stdio.h>

void main( )

{int y=9;

for(;y>0;y--)

{if(y%3==0)

{printf("%d",--y);

continue;}

}

}

  A. 741   B. 852   C. 963   D. 875421

```

---

111、下面程序的输出结果是(<small class="pass">B</small>).

```markdown

# include<stdio.h>

void main( )

{int x=3;

do {

printf("%d ",x-=2);

}while(!(--x));

}

  A. 1   B. 1 -2   C. 3 0   D.是死循环

```

---

112、定义如下变量:

int n=10;

则下列循环的输出结果是(<small class="pass">B</small>).

```markdown

while(n>7)

{ n--; printf("%d\n",n);}

  A. 10   B. 9   C. 10   D. 9

9 8 9 8

8 7 8 7

7 6

```

---

113、语句while(!e);中的条件 !e 等价于(<small class="pass">A</small>).

```markdown

  A. e==0   B. e!=1   C. e!=0   D. ~e

```

---

114、以下叙述正确的是(<small class="pass">B</small>).

```markdown

  A. continue语句的作用是结束整个循环的执行

  B. 只能在循环体内和switch语句体内使用break语句

  C. 在循环体内使用break语句或continue语句的作用相同

  D. 从多层循环嵌套中退出时,只能使用goto语句

```

---

115、在下列选项中，没有构成死循环的程序段是(<small class="pass">D</small>).

```markdown

  A. int i=100;   B. for( ; ; );

while (1)

{ i=i%100+1;

if (i>100) break;

}

  C. int k=1000;   D. int s=36;

do {++k;} while (k>=1000); while (s) --s;

```

---

116、下面程序的输出结果是(<small class="pass">A</small>).

```markdown

# include<stdio.h>

void main( )

{ int i;

for(i=1;i<=5;i++)

{ if (i%2) printf("*");

else continue;

printf("#");

}

printf("$\n");

}

  A. *#*#*#$   B. #*#*#*$   C. #*#*$   D. *#*#$

```

---

117、下面程序段中,循环体的执行次数是(<small class="pass">C</small>).

```markdown

int a=10,b=0;

do {b+=2;a-=2+b;} while(a>=0);

  A. 4   B. 5   C. 3   D. 2

```

---

118、若i为整型变量,则以下循环语句的循环次数是(<small class="pass">B</small>).

```markdown

for(i=2;i==0;)

printf("%d",i--);

  A. 无限次   B. 0次   C. 1次   D. 2次

```

---

119、C语言中while 和do-while 循环的主要区别是.(<small class="pass">A</small>)

```markdown

  A. do-while的循环体至少无条件执行一次

  B. while 的循环控制条件比do-while 的循环控制条件严格

  C. do-while 允许从外部转到循环体内

  D. do-while 的循环体不能是复合语句

```

---

120、对于for(表达式1;;表达式3)可理解为(<small class="pass">B</small>).

```markdown

  A. for(表达式1;0;表达式3)

  B. for(表达式1;1;表达式3)

  C. for(表达式1;表达式1;表达式3)

  D. for(表达式1;表达式3;表达式3)

```

---

121、合法的数组定义是(<small class="pass">D</small>).

```markdown

  A. int a[6]={"string"};   B. int a[5]={0,1,2,3,4,5};

  C. char a={"string"};   D. char a[]={0,1,2,3,4,5};

```

---

122、要求下面的程序运行后，显示如下结果：

2 10 4 6

1 5 2 3

2 4 7 8

5 1 3 2

则程序中的划线处应填入(<small class="pass">B</small>).

```markdown

# include <stdio.h>

void main( )

{ int a[4][4]={ ________ };

int i,j;

for(i=0;i<4;i++)

{for(j=0;j<4;j++) printf("%4d",a[i][j]);

printf("\n"); }

}

  A. {1,5,2,3},{2,4,7,8},{5,1,3,2}

  B. {2,10,4,6},{1,5,2,3},{2,4,7,8},{5,1,3,2}

  C. {5,1,3,2},{2,4,7,8},{1,5,2,3}

  D. {2,1,2,5},{10,5,4,1},{4,2,7,3},{6,3,8,2}

```

---

123、给出以下定义:

char x[ ]="abcdefg";

char y[ ]={'a','b','c','d','e','f','g'};

则正确的叙述为 (<small class="pass">C</small>).

```markdown

  A. 数组x和数组y等价

  B. 数组x和数组y的长度相同

  C. 数组x的长度大于数组y的长度

  D. 数组x的长度小于数组y的长度

```

---

124、定义如下变量和数组:

int i;

int x[4][4]={1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16};

则下面语句的输出结果是(<small class="pass">C</small>).

```markdown

for(i=0;i<4;i++) printf("%3d",x[i][3-i]);

  A. 1 5 9 13   B. 1 6 11 16

  C. 4 7 10 13   D. 4 8 12 16

```

---

125、下面程序输出的结果是(<small class="pass">D</small>).

```markdown

# include <stdio.h>

void main( )

{ int i,j,x=0;

static int a[6]={1,2,3,4,5,6};

for(i=0,j=1;i<5;++i,j++) x+=a[i]*a[j];

printf("%d\n",x);

}

  A. 数组a中首尾的对应元素的乘积

  B. 数组a中首尾的对应元素的乘积之和

  C. 数组a中相邻各元素的乘积

  D. 数组a中相邻各元素的乘积之和

```

---

126、若希望下面的程序运行后输出45，程序空白处的正确选择是(<small class="pass">C</small>).

```markdown

# include <stdio.h>

void main( )

{ int i,j=10,a[ ]={1,3,5,7,9,11,13,15};

for( ____________ )

j+=a[i];

printf("%d\n",j);

}

  A. i=5;i>1;i--   B. i=0;i<7;++i

  C. i=5;i>=1;--i   D. i=2;i<6;++i

```

---

127、若有以下说明：

char s1[ ]={"tree"},s2[]={"flower"}; ,

则以下对数组元素或数组的输出语句中，正确的是(<small class="pass">C</small>).

```markdown

  A. printf("%s%s",s1[5],s2[7]);

  B. printf("%c%c",s1,s2);

  C. puts(s1);puts(s2);   D. puts(s1,s2);

```

---

128、下列一维数组初始化语句中，正确且与语句float a[ ]={0,3,8,0,9};等价的是(<small class="pass">D</small>).

```markdown

  A. float a[6]={0,3,8,0,9};   B. float a[4]={0,3,8,0,9};

  C. float a[7]={0,3,8,0,9};   D. float a[5]={0,3,8,0,9};

```

---

129、运行下面程序段的输出结果是(<small class="pass">A</small>).

```markdown

char s1[10]={'S','e','t','\0','u','p','\0'};

printf("%s",s1);

  A. Set   B. Setup   C. Set up   D. 'S''e''t'

```

---

130、以下程序段的输出结果是(<small class="pass">B</small>).

```markdown

char s[ ]="an apple";

printf("%d\n",strlen(s));

  A. 7   B. 8   C. 9   D. 10

```

---

131、若有说明:char c[10]={'E','a','s','t','\0'};，则下述说法中正确的是(<small class="pass">D</small>).

```markdown

  A. c[7]不可引用   B. c[6]可引用，但值不确定

  C. c[4]不可引用   D. c[4]可引用，其值为空字符

```

---

132、下列初始化语句中，正确且与语句

char c[ ]="string";等价的是(<small class="pass">C</small>).

```markdown

  A. char c[ ]={'s','t','r','i','n','g'};

  B. char c[ ]='string';

  C. char c[7]={'s','t','r','i','n','g','\0'};

  D. char c[7]={'string'};

```

---

133、若有说明char c[7]={'s','t','r','i','n','g'};则对元素的非法引用是(<small class="pass">C</small>).

```markdown

  A. c[0]   B. c[9-6]   C. c[4*2]   D. c[2*3]

```

---

134、如有说明：char s1[5],s2[7]; ,要给数组s1和s2整体赋值，下列语句中正确的是(<small class="pass">C</small>).

```markdown

  A. s1=getchar(); s2=getchar();

  B. scanf("%s%s",s1,s2);

  C. scanf("%c%c",s1,s2);

  D. gets(s1,s2);

```

---

135、下列一组初始化语句中，正确的是(<small class="pass">B</small>).

```markdown

  A. int a[8]={ };   B. int a[9]={0,7,0,4,8};

  C. int a[5]={9,5,7,4,0,2};   D. int a[7]=7*6;

```

---

136、以下程序输出的结果是(<small class="pass">D</small>).

```markdown

# include <stdio.h>

void main( )

{ char str[ ]="1a2b3c"; int i;

for(i=0;str[i]!='\0';i++)

if(str[i]>='0'&&str[i]<='9') printf("%c",str[i]);

printf("\n");

}

  A. 123456789   B. 1a2b3c   C. abc   D. 123

```

---

137、以下程序输出的结果是(<small class="pass">C</small>).

```markdown

# include <stdio.h>

void main( )

{ int a[ ]={5,4,3,2,1},i,j;

long s=0;

for(i=0;i<5;i++) s=s*10+a[i];

printf("s=%ld\n",s);

}

  A. s=12345   B. s=5 4 3 2 1

  C. s=54321   D. 以上都不对

```

---

138、以下程序输出的结果是(<small class="pass">A</small>).

```markdown

# include <stdio.h>

void main( )

{ int a[ ]={1,2,3,4,5},i,j,s=0;

for(i=0;i<5;i++) s=s*10+a[i];

printf("s=%d\n",s);

}

  A. s=12345   B. s=1 2 3 4 5

  C. s=54321   D. s=5 4 3 2 1

```

---

139、在定义int a[5][6];后，数组a中的第10个元素是.(<small class="pass">C</small>)（设a[0][0]为第一个元素）

```markdown

  A. a[2][5]   B. a[2][4]   C. a[1][3]   D. a[1][5]

```

---

140、当接受用户输入的含有空格的字符串时，应使用(<small class="pass">A</small>)函数.

```markdown

  A. gets( )   B. getchar( )   C. scanf( )   D. printf( )

```

---

141、以下程序执行时输入Language Programming<回车>，输出结果是(<small class="pass">D</small>).

```markdown

# include <stdio.h>

void main( )

{ char str[30];

gets(str);

printf("str=%s\n",str);

}

  A. Language Programming   B. Language

  C. str=Language   D. str=Language Programming

```

---

142、以下一维数组a的正确定义是(<small class="pass">D</small>)

```markdown .

  A. int a(10);   B. int n=10,a[n];

  C. int n;   D. #define SIZE 10

scanf("%d",&n); int a[SIZE];

int a[n];

```

---

143、以下对二维数组a进行正确初始化的是(<small class="pass">B</small>).

```markdown

  A. int a[2][3]={ {1,2},{3,4},{5,6} };

  B. int a[ ][3]={1,2,3,4,5,6 };

  C. int a[2][ ]={1,2,3,4,5,6};

  D. int a[2][ ]={ { 1,2},{3,4}};

```

---

144、以下关于数组的描述正确的是(<small class="pass">C</small>).

```markdown

  A. 数组的大小是固定的，但可以有不同类型的数组元素。

  B. 数组的大小是可变的，但所有数组元素的类型必须相同。

  C. 数组的大小是固定的，所有数组元素的类型必须相同。

  D. 数组的大小是可变的，可以有不同类型的数组元素。

```

---

145、以下程序的输出结果是(<small class="pass">B</small>).

```markdown

# include<stdio.h>

void main()

{ int a[4][4]={{1,3,5,},{2,4,6},{3,5,7}};

printf("%d%d%d%d\n",a[0][0],a[1][1],a[2][2],a[3][3]);

}

  A. 0650   B. 1470   C. 5430   D. 输出值不定

```

---

146、以下程序的输出结果是(<small class="pass">A</small>).

```markdown

# include <stdio.h>

void main()

{ int a[4][4]={{1,3,5,},{2,4,6},{3,5,7}};

printf("%d%d%d%d\n",a[0][3],a[1][2],a[2][1],a[3][0]);

}

  A. 0650   B. 1470   C. 5430   D. 输出值不定

```

---

147、已知short int类型变量占用两个字节，若有定义：short int x[10]={0,2,4}; ，则数组x在内存中所占字节数是(<small class="pass">D</small>).

```markdown

  A. 3   B. 6   C. 10   D. 20

```

---

148、在定义int a[5][4]; 之后，对a的引用正确的是.(<small class="pass">C</small>)

```markdown

  A. a[2][4]   B. a[1,3]   C. a[4][3]   D. a[5][0]

```

---

149、以下数组定义中不正确的是(<small class="pass">D</small>).

```markdown

  A. int a[2][3];

  B. int b[][3]={0,1,2,3};

  C. int c[100][100]={0};

  D. int a[3][]={{1,2},{1,2,3},{1,2,3,4}};

```

---

150、在执行语句： int a[ ][3]={1,2,3,4,5,6}; 后，a[1][0]的值是(<small class="pass">A</small>).

```markdown

  A. 4   B. 1   C. 2   D. 5

```

---

151、以下程序的输出结果是(<small class="pass">C</small>).

```markdown

# include <stdio.h>

void main()

{ int i,a[10];

for(i=9;i>=0;i--) a[i]=10-i;

printf("%d%d%d",a[2],a[5],a[8]);

}

  A. 258   B. 741   C. 852   D. 369

```

---

152、以下定义语句中，错误的是(<small class="pass">B</small>).

```markdown

  A. int a[]={1,2};   B. char a={"test"};

  C. char s[10]={"test"};   D. int a[]={'a','b','c'};

```

---

153、以下定义语句中，错误的是(<small class="pass">D</small>).

```markdown

  A. int a[]={1,2};   B. char a[]={"test"};

  C. char s[10]={"test"};   D. int n=5,a[n];

```

---

154、下列程序的输出结果是(<small class="pass">C</small>).

```markdown

# include <stdio.h>

void main()

{char b[]="ABCDEFG";

char p=0;

while(p<7)

putchar(b[p++]);

putchar('\n');

}

  A. GFEDCBA   B. BCDEFG

  C. ABCDEFG   D. GFEDCB

```

---

155、下述对C语言字符数组的描述中错误的是(<small class="pass">C</small>).

```markdown

  A. 字符数组可以存放字符串

  B. 字符数组中的字符串可以整体输入、输出

  C. 可以在赋值语句中通过赋值运算符"="对字符数组整体赋值

  D. 不可以用关系运算符对字符数组中的字符串进行比较

```

---

156、以下程序的输出结果是(<small class="pass">A</small>).

```markdown

# include<stdio.h>

void main()

{ int i,x[3][3]={1,2,3,4,5,6,7,8,9};

for(i=0;i<3;i++)

printf("%d,",x[i][i]);

printf("\n");

}

  A. 1,5,9,   B. 1,4,7,   C. 3,5,7,   D. 3,6,9,

```

---

157、如有定义语句int a[]={1,8,2,8,3,8,4,8,5,8}; ，则数组a的大小是(<small class="pass">A</small>).

```markdown

  A. 10   B. 11   C. 8   D. 不定

```

---

158、有如下程序

```c
# include<stdio.h>

void main()

{ char ch[80]="123abcdEFG*&";

int j;long s=0;

puts(ch);

for(j=0;ch[j]>'\0';j++)

if(ch[j]>='A'&&ch[j]<='Z')

ch[j]=ch[j]+'e'-'E';

puts(ch);

}
```

该程序的功能是(<small class="pass">D</small>).

```markdown

  A. 测字符数组ch的长度

  B. 将数字字符串ch转换成十进制数

  C. 将字符数组ch中的小写字母转换成大写

  D. 将字符数组ch中的大写字母转换成小写

```

---

159、设有如下定义:

char aa[2][20]={ "abcd", "ABCD"};

则以下说法中错误的是(<small class="pass">D</small>).

```markdown

  A. aa是个二维数组，可以存放2个19个字符以下的字符串

  B. aa是个二维数组，每行中分别存放了字符串"abcd"和"ABCD"

  C. aa[0]可以看作是一维数组名

  D. aa[0][0]可以看作是一维数组名

```

---

160、以下对C语言函数的有关描述中,正确的是(<small class="pass">A</small>).

```markdown

  A. 在C中,调用函数时,只能把实参的值传送给形参,形参的值不能传送给实参

  B. C函数既可以嵌套定义又可以递归调用

  C. 函数必须有返回值,否则不能使用函数

  D. C程序中有调用关系的所有函数必须放在同一个源程序文件中

```

---

161、有如下说明: int a[10]={0,1,2,3,4,5,6,7,8,9};

则数值不为9的表达式是(<small class="pass">B</small>).

```markdown

  A. a[10-1]   B. a[8]   C. a[9]-0   D. a[9]-a[0]

```

---

162、设有数组定义:char array[]="China";则数组array所占的存储空间为(<small class="pass">C</small>).

```markdown

  A. 4个字节   B. 5个字节

  C. 6个字节   D. 7个字节

```

---

163、下面程序的输出是(<small class="pass">B</small>).

```markdown

# include <stdio.h>

int m=13;

int fun2(int x, int y)

{ int m=3;

return(x*y-m);

}

void main()

{ int a=7, b=5;

printf("%d\n",fun2(a,b)/m);

}

  A. 1   B. 2   C. 7   D. 10

```

---

164、请读程序:

```c
# include <stdio.h>

f(int b[ ], int n)

{ int i, r=0;

for(i=0; i<=n; i++) r=r+b[i];

return r;

}

void main()

{

int x, a[]={ 2,3,4,5,6,7,8,9};

x=f(a, 3);

printf("%d\n",x); }
```

上面程序的输出结果是(<small class="pass">B</small>).

```markdown

  A. 20   B. 14   C. 9   D. 5

```

---

165、请读程序:

```c
# include <stdio.h>

f(int b[ ], int n)

{ int i, r=1;

for(i=0; i<=n; i++) r=r*b[i];

return r; }

void main()

{ int x, a[]={ 2,3,4,5,6,7,8,9};

x=f(a, 3);

printf("%d\n",x); }
```

上面程序的输出结果是(<small class="pass">B</small>).

```markdown

  A. 720   B. 120   C. 24   D. 6

```

---

166、请读程序：

```c
# include<stdio.h>

f(char s[ ])

{ int i,j;

i=0;j=0;

while( s[j]!= '\0') j++;

return (j-i); }

void main()

{printf("%d\n",f("ABCDEF"));}
```

上面程序的输出结果是(<small class="pass">B</small>).

```markdown

  A. 0   B. 6   C. 7   D. 8

```

---

167、对以下程序，正确的说法是(<small class="pass">D</small>).

```markdown

sub (char x,char y)

{ int z; z=x%y; return z; }

void main( )

{ int g=5,h=3,k;

k=sub(g,h);

printf("%d\n",k); }

  A. 实参与其对应的形参类型不一致，程序不能运行

  B. 被调函数缺少数据类型说明，程序不能运行

  C. 主函数中缺少对被调函数的说明语句，程序不能运行

  D. 程序中没有错误，可以正常运行

```

---

168、若已定义实参数组int a[3][4]={2,4,6,8,10};，则在被调用函数f的下述定义中，对形参数组b定义正确的选项是(<small class="pass">B</small>).

```markdown

  A. f(int b[ ][6])   B. f(b) int b[ ][4];

  C. f(int b[3][ ]);   D. f(b) int b[4][5];

```

---

169、若函数调用时用数组名作为函数参数，以下叙述中，不正确的是(<small class="pass">C</small>).

```markdown

  A. 实参与其对应的形参共占用同一段存储空间

  B. 实参将其地址传递给形参，结果等同于实现了参数之间的双向值传递

  C. 实参与其对应的形参分别占用不同的存储空间

  D. 在调用函数中必须说明数组的大小，但在被调函数中可以使用不定尺寸数组

```

---

170、以下叙述中，不正确的是(<small class="pass">B</small>).

```markdown

  A. 使用static float a定义的外部变量存放在内存中的静态存储区

  B. 使用float b定义的外部变量存放在内存中的动态存储区

  C. 使用static float c定义的内部变量存放在内存中的静态存储区

  D. 使用float d定义的内部变量存放在内存中的动态存储区

```

---

171、如果一个函数位于C程序文件的上部，在该函数体内说明语句后的复合语句中定义了一个变量，则该变量(<small class="pass">C</small>).

```markdown

  A. 为全局变量，在本程序文件范围内有效

  B. 为局部变量，只在该函数内有效

  C. 为局部变量，只在该复合语句中有效

  D. 定义无效，为非法变量

```

---

172、调用函数时，当实参和形参都是简单变量时，它们之间数据传递的过程是(<small class="pass">D</small>).

```markdown

  A. 实参将其地址传递给形参，并释放原先占用的存储单元

  B. 实参将其地址传递给形参，调用结束时形参再将其地址回传给实参

  C. 实参将其值传递给形参，调用结束时形参再将其值回传给实参

  D. 实参将其值传递给形参，调用结束时形参并不将其值回传给实参

```

---

173、以下叙述中，不正确的是(<small class="pass">B</small>).

```markdown

  A. 在同一C程序文件中，不同函数中可以使用同名变量

  B. 在main函数体内定义的变量是全局变量

  C. 形参是局部变量，函数调用完成即失去意义

  D. 若同一文件中全局变量和局部变量同名，则全局变量在局部变量作用范围内不起作用

```

---

174、若函数调用时参数为基本数据类型的变量(俗称简单变量)，以下叙述正确的是(<small class="pass">C</small>).

```markdown

  A. 实参与其对应的形参共占存储单元

  B. 只有当实参与对应的形参同名时才共占存储单元

  C. 实参与其对应的形参分别占用不同的存储单元

  D. 实参将数据传递给形参后，立即释放原先占用的存储单元

```

---

175、若主调用函数类型为double，被调用函数定义中没有进行函数类型说明，而return语句中的表达式类型为float型，则被调函数返回值的类型是(<small class="pass">A</small>)。

```markdown

  A. int 型   B. float 型

  C. double 型   D. 由系统当时的情况而定

```

---

176、在以下叙述中，不正确的选项是(<small class="pass">B</small>)。

```markdown

  A. C语言程序总是从main( )函数开始执行

  B. 在C语言程序中，被调用的函数必须在main( )函数中定义

  C. C程序是函数的集合，在这个函数集中包括标准函数和用户自定义函数

  D. 在C语言程序中，函数的定义不能嵌套，但函数的调用可以嵌套

```

---

177、C语言中，若未说明函数的类型，则系统默认该函数的类型是(<small class="pass">C</small>)。

```markdown

  A. float型   B. long型   C. int型   D. double型

```

---

178、下面函数的功能是(<small class="pass">B</small>)。

```markdown

sss(s, t)

char s[ ], t[ ];

{ int i=0;

while((s[i])&&(t[i])&&(t[i]== s[i])) i++;

return (s[i]-t[i]);}

  A. 求字符串的长度

  B. 比较两个字符串的大小

  C. 将字符串s复制到字符串t中

  D. 将字符串s接续到字符串t中

```

---

179、设有如下函数定义:

int f(char s[ ])

{ int i=0;

while(s[i++]!='\0');

return (i-1); }

如果在主程序中用下面的语句调用上述函数,则输出结果为(<small class="pass">C</small>).

```markdown

printf("%d\n",f("goodbey!"));

  A. 3   B. 6   C. 8   D. 9

```

---

180、对于C语言的函数，下列叙述中正确的是(<small class="pass">A</small>).

```markdown

  A. 函数的定义不能嵌套，但函数调用可以嵌套

  B. 函数的定义可以嵌套，但函数调用不能嵌套

  C. 函数的定义和调用都不能嵌套

  D. 函数的定义和调用都可以嵌套

```

---

181、以下说法中正确的是(<small class="pass">C</small>).

```markdown

  A. C语言程序总是从第一个定义的函数开始执行

  B. 在C语言程序中,要调用的函数必须在main()函数中定义

  C. C语言程序总是从main()函数开始执行

  D. C语言程序中的main()函数必须放在程序的开始部分

```

---

182、以下程序的输出结果是(<small class="pass">B</small>).

```markdown

# include <stdio.h>

int a,b;

void fun()

{ a=100; b=200; }

void main()

{ int a=5,b=7;

fun();

printf("%d%d\n",a,b); }

  A. 100200   B. 57   C. 200100   D. 75

```

---

183、以下函数func()的功能是：使具有n个元素的一维数组b的每个元素的值都增加2，划线处应填入(<small class="pass">D</small>).

```markdown

func(int b[ ],int n)

{ int ;

for(i=0;i<n;i++)

__________; }

  A. b[i++]   B. b[i]++   C. b[i+=2]   D. b[i]+=2

```

---

184、设有以下函数：

```c
# include <stdio.h>

int f(int a)

{ int b=0,c;

c=3;

b++ ; c++;

return (a+b+c); }
```

如果在下面的程序中调用该函数，则输出结果是(<small class="pass">B</small>).

```markdown

void main()

{ int i;

for(i=0;i<3;i++) printf("%d\n",f(i)); }

  A. 5   B. 5   C. 3   D. 3

7 6 4 3

9 7 5 3

```

---

185、设有以下函数：

```c
# include <stdio.h>

int f(int a)

{ int b=0;

static c=3;

b++ ; c++;

return (a+b+c); }
```

如果在下面的程序中调用该函数，则输出结果是(<small class="pass">A</small>).

```markdown

void main()

{ int a=2,i;

for(i=0;i<3;i++) printf("%d\n",f(a)); }

  A. 7   B. 7   C. 7   D. 7

8 9 10 7

9 11 13 7

```

---

186、在调用函数时，如果实参是简单变量，它与对应形参之间的数据传递方式是(<small class="pass">B</small>).

```markdown

  A. 地址传递   B. 单向值传递

  C. 由实参传给形参，再由形参传回实参

  D. 传递方式由用户指定

```

---

187、C语言规定，除主函数外，程序中各函数之间(<small class="pass">A</small>).

```markdown

  A. 既允许直接递归调用也允许间接递归调用

  B. 不允许直接递归调用也不允许间接递归调用

  C. 允许直接递归调用不允许间接递归调用

  D. 不允许直接递归调用允许间接递归调用

```

---

188、以下函数fun形参的类型是(<small class="pass">D</small>).

```markdown

fun( float x)

{ float y;

y=3*x-4;

return y; }

  A. int   B. 不确定   C. void   D. float

```

---

189、下面程序的输出是(<small class="pass">C</small>).

```markdown

int fun3(int x)

{static int a=3;

a+=x;

return(a); }

void main()

{int k=2,m=1,n;

n=fun3(k);

n=fun3(m);

printf("%d\n",n); }

  A. 3   B. 4   C. 6   D. 9

```

---

190、下列程序执行后输出的结果是(<small class="pass">C</small>).

```markdown

# include<stdio.h>

int f(int a)

{int b=0;

static c=3;

a=c++,b++;

return(a); }

void main()

{int a=2,i,k;

for(i=0;i<3;i++)

k=f(a++);

printf("%d\n",k); }

  A. 3   B. 0   C. 5   D. 4

```

---

191、C语言中规定函数的返回值的类型是由(<small class="pass">D</small>).

```markdown

  A. return语句中的表达式类型所决定

  B. 调用该函数时的主调用函数类型所决定

  C. 调用该函数时系统临时决定

  D. 在定义该函数时所指定的类型所决定
```
