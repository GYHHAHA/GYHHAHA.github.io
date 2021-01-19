---
layout: post
title: cpp primer 第四章 表达式
categories: cpp
tags: 
author: GYH
---

* content
{:toc}

## cpp

- 给定两个二叉树，编写一个函数来检验它们是否相同。如果两个树在结构上相同，并且节点具有相同的值，则认为它们是相同的。
- 【思路】把一个节点上的四种情况想清楚，都为空、一个空、值不同、值相同（向下递归），最后通过 `and` 来连接所有的判断。