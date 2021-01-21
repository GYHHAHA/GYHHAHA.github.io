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

## 体会

- P163的错误的例子为什么属于作用域？这可以由case只有break才完全退出想到。
- 练习5.12中，cin.get(char)才能读取特殊符号。

## 疑问

- 迭代器是什么类型？
- default的真正含义是什么？