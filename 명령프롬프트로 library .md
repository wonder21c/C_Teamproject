> ## ***1. 라이브러리 함수***  
> ### add.c(덧셈) :

```c
#include<stdio.h>  
int add(int a,int b){  
printf("%d\n",a+b);  
return a+b;  
}  
```  
> ### sub.c(뺄셈) :

```c
#include<stdio.h>
int sub(int a,int b){
printf("%d\n",a-b);
 return a-b;
}  
```  
> ### mul.c(곱셈) :

```c
#include<stdio.h>
int sub(int a,int b){
printf("%d\n",a-b);
 return a-b;
}  
```  
> ### div.c(나눗셈) :

```c
#include<stdio.h>
int sub(int a,int b){
printf("%d\n",a-b);
 return a-b;
}  
```  
> ### div2.c(몫) :

```c
#include<stdio.h>
int sub(int a,int b){
printf("%d\n",a-b);
 return a-b;
}  
```  
> ### div3.c(나머지) :

```c
#include<stdio.h>
int sub(int a,int b){
printf("%d\n",a-b);
 return a-b;
}  
```  
  
* * *
> ## ***2. main함수(test.c) :***

```c
#include<stdio.h>
int add(int a,int b);
int sub(int a,int b);
int mul(int a,int b);
int div(float a,float b);
int div2(int a,int b);
int div3(int a,int b);

int main(){
  int a,b; a=2;b=3;
  add(a,b);
  sub(a,b);
  mul(a,b);
  div(a,b);
  div2(a,b);
  div3(a,b);
}
```   


   
     
* * *
> ## ***3. 명령 프롬프트 :***

```
 > cl /c *.c
 > lib /OUT:my.lib add.obj sub.obj mul.obj div.obj div2.obj div3.obj
 > link test my.lib
 > test
 > 5
   -1
   6
   0.666667
   0
   2
```

> ## ***3-1. 결과 사진 :***
![주석 2019-10-08 164038](https://user-images.githubusercontent.com/50895677/66376699-2cd12080-e9eb-11e9-8e09-ea358e34e570.png)
  
  
* * *
> ## ***4. 소감 :***  
평소에 코딩을 하면서 썼던 stdio 헤더파일도 전부 일일히 만들어진 라이브러리의 집합이였다는 것을 알 수 있었습니다.
오늘은 라이브러리가 어떻게 만들어지고 집합되는지에 대해 직접 실습을 해보면서 코딩에 대한 이해도가 더 넓어지는 계기가 되었습니다.
**C언어 너무 재밌습니다.** **C언어 사랑합니다.**
