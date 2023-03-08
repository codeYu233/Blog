---
title: Q1 of Discrete Mathematics

date: 2023/3/7
author: codeYu233
img: ../pictures/DM.jpg
cover:
coverImage: ../pictures/DM.jpg
summary: 
categories: Study
tags:
 - DM
 - Program
---
# ***Q1 of Discrete Mathematics***

## Question

Two kinds of inhabitants:

Knights: always tell the truth;  Knaves: always  lie.

You encounter 2 people A and B.
A says:”B is a knight”, B says: “I and A are of opposite types”. 
What are A and B?



## Solution

A与B所说的话实际各代表一个逻辑关系。根据每人所陈述的逻辑关系，我们可以假设A为真，A为负，从而在A的话的前提下推出所有结果(得到*Result A*)。同理，我们也可以根据B推出所有结果（*Result B*）。

根据RA和RB两个集合，将其取重复的交集，即可得到真实存在的，同时满足A,B所说的话的最终结果。

![](Q1-DM.png)



## Site

代码链接： https://github.com/codeYu233/Study/tree/main/Question1	

