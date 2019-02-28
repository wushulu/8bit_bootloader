# Microchip

### 添加图片  ![image](https://github.com/ButBueatiful/dotvim/raw/master/screenshots/vim-screenshot.jpg)
![image](https://github.com/wushulu/Microchip/blob/master/%E5%9B%BE%E7%89%87/MCLV-2.png)


###  当git出错时候 文件不一致时  git pull --rebase origin master

### 


## 代码列[^code]
```c
#include<stdio.h>

int main(void)
{

printf("hello my world");
}
```
## 以下为重要笔记
   mybootloader.rar 里面包含了 应用程序 APP和主程序 
   其中CAN 端口复用要小心复用代码使用上存在Bug 映射要在boot里面
   V1.41修复PPS 只在APP里面使用 。BootLoader里面使用会导致APP里面无法操作