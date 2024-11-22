---
title: 电路
date: 2024-11-10 18:13:52
ai:
  - 本文讲解基本的入门电路，通过这些电路实现半加器，全加器，半减器，全减器。
  - 有其他问题可以提交ississ
main_color: "#c0e0e0"
categories: 前端开发
description: "基础入门加法电路"
toc: true
indexing: true
tags: 电子
mathjax: true
top_img: https://jsd.cdn.zzko.cn/gh/beforelike/picx-images-hosting@master/2023-10-31.OHR.HalloweenCuteAI_ZH-CN1079713117_UHD.3nrcsx7rh9.webp
cover: https://jsd.cdn.zzko.cn/gh/beforelike/picx-images-hosting@master/2de40dbb9c44372889.54xicdcnd4.jpg
---
# 二进制的数据表达

## 二进制数据表达

### 编码与解码

电报系统：编码，解码。两个过程，

### 位的概念

使用二进制进行编码，每当位数增加一位，不同取值的数量就会增加

如果：N = 位数

能产生的结果 = 2的N次方

计算机中将位数称为比特(bit)，计算机的最小数据单位

### 早期的编码 摩尔斯电码

降低成本，引入  **时序** 的概念

### ASCⅡ码

7位，扩展了到8位

## 二进制图片

### 图片像素化

将图片拆分成色块

### 像素数字化

三个字节表示色彩

位深为8

拓展到每个字节用三个字节表示，位深是32

## 二进制表示声音

### 采样率

将1s拆分成很多份，采样率越高，信息丢失越少

### 量化

每个采样率用一个数字表示高度，是一个连续量化离散的过程，与图片色深类似，取值与图片相似，叫做声音的位深。

## 二进制存视频

将图片，音频拼接起来

## 与或非门

输入 = 0/1

输出 = 1/0

 ## 与门

两个输入都为1，输出1

否则为0

Y = A * B

## 或门

 有一个输入为1，输出为1

Y = A + B 

## 非门

Y = Ā

进1出0，进0出1

## 异或门

比较两个信号，相同则为0，不同则为1

## 与非门

先与，后非

全1出0，其他出1

## 或非门

先或，后非

有1出0，全0出1

## 运算器

### 加法

半加器![image-20241006234547267](C:\Users\woo_w\AppData\Roaming\Typora\typora-user-images\image-20241006234547267.png)

1bit加法器

![image-20241006235109132](C:\Users\woo_w\AppData\Roaming\Typora\typora-user-images\image-20241006235109132.png)

多位加法器

![image-20241007020631938](C:\Users\woo_w\AppData\Roaming\Typora\typora-user-images\image-20241007020631938.png)

### 减法

半减器

![半减器](C:\Users\woo_w\AppData\Roaming\Typora\typora-user-images\image-20241007021234476.png)

1bit减法器

![全减器](C:\Users\woo_w\AppData\Roaming\Typora\typora-user-images\image-20241007021627215.png)


