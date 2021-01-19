---
layout: post
title: cpp primer 第四章 表达式
categories: cpp
tags: 
author: GYH
---

* content
{:toc}

## 知识点

- 当一个对象被用作右值时，用的是对象的值（内容）；当对象被用作左值时，用的是对象的身份（在内存中的位置）。（P121）
- 如果表达式求解的结果为左值，decltype作用于表达式（不是变量）得到一个引用类型。（P121）
- 下面的程序未定义：（P123）

```
int i = 1;
cout << i << " " << ++i << endl;
```

## 体会

- 左值是存储对象，右值是临时对象