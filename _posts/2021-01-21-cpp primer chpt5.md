---
layout: post
title: cpp primer 第五章 语句
categories: cpp
tags: 
author: GYH
---

* content
{:toc}

## 知识点

- case标签必须是整型常量表达式。（P161）
- 不允许跨过变量的初始化语句直接跳转到该变量作用域的另一个位置。（P163）
- 范围for语句中，如果想对循环变量进行写操作，必须声明成引用类型。（P168）
- 范围for语句中，不能增加容器的元素，否则end迭代器失效。（P169）
- 在do while语句中，condition使用的变量必须定义在循环体外。（P169）

## 体会

- P163的错误的例子为什么属于作用域？这可以由case只有break才完全退出想到。
- 练习5.12中，cin.get(char)才能读取特殊符号。

## 疑问

- 迭代器是什么类型？
- default的真正含义是什么？