#include <stdio.h>              //使用函數庫
 int main()
{
     printf("Hello, World! \n");  //顯示Hello, World!
     return 0;   //回傳結束
}
========================================================
#include <iostream>         //使用
using namespace std;
int main()
{
    cout << "Hello, world!" << endl;
    return 0;
}
========================================================
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}

========================================================
#include<stdio.h>
 
int main()
    {
    int i,j,k;  
    printf("\n");
    for(i=1;i<5;i++) {   // 以下?三重循?
    for(j=1;j<5;j++) {
    for (k=1;k<5;k++) {   // 确保i、j、k三位互不相同
    if (i!=k&&i!=j&&j!=k) { 
    printf("%d,%d,%d\n",i,j,k);
    }
    }
    }
    }
    }
=========================================================

