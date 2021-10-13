#2021cc。
資傳一乙第一節程序設計課
序不小心打錯字

```C
#include <stdio.h>
int main() ///在main()裡面,可以省略!!
{
printf("Hello World\n");
return 0; ///Q1: 書上有啊!!! 有寫比較好
} ///Q2: 要用大括號來結尾
///學習步驟:
///(0)學習前準備
///(1)我說給你聽(馬上忘)
///(2)我做給你看(慢慢做/截圖) 10分鐘
///(3)換你做做看(作業) 10分鐘 (卡住了/問題)
///(4)成效追蹤
```
```C
#include <stdio.h>
int main()
{
   int a, b;
   scanf("%d%d", &a, &b );
   printf("%d", a+b );
}
```
```C
#include <stdio.h>
int main()
{
    printf("Hello World\n");
    printf("Hello World\n");

}
```
```C
#include<stdio.h>
int main()
{
    int a, b;
    scanf("%d%d", &a, &b );
    printf("%d", a+b);
}
```
```C
#include <stdio.h>
int main()
{
    printf("Hllo World\n");
    printf("%d" , 300);
}
```
```C
#include <stdio.h>
int main()
{
    printf( "Hllo World\n");
    printf( "Hello%dWorld\n", 300);
    printf( "%d %d    %d" , 300, 200, 100);
}

```
```C
#include <stdio.h>
int main()
{
    int a;
    printf("請輸入一個整數a的值: ");
    scanf("%d" , &a);

    printf("a的值是:%d\n" , a);
}

```
```C
#include<stdio.h>
int main()
{
    int a;
    scanf("%d",&a);
    if(a>0)printf("a是正數");
    if(a<0)printf("a是負數");
    if(a==0)printf("a是0");
}
```
```C
#include <stdio.h>
int main ()
{
    if(10>0)printf("10>0成立\n");
    if(10<0)printf("10<0成立\n");
    if (-3)printf("-3是成立的嗎?\n");
    if (-2)printf("-2是成立的嗎?\n");
    if (-1)printf("-1是成立的嗎?\n");
    if (0)printf("0是成立的嗎?\n");
    if (1)printf("1是成立的嗎?\n");
    if (2)printf("2是成立的嗎?\n");
    if (3)printf("3是成立的嗎?\n");
}
```
```C
1	#include<stdio.h>
2	int main()
3	{
4	    int n;
5	    n=2;
6	    if(n%2==0)printf("even");
7	    else printf("odd");
8	}
```
```C
