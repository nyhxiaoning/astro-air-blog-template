---
layout: '../../layouts/MarkdownPost.astro'
title: 'leetcode-0426'
pubDate: 2023-04-26
description: '今日第一天整理迁移：'
author: 'henry'
cover:
    url: 'https://cdn2.unrealengine.com/vr-week-2023-header-4-1920x1080-376e6c48383f.jpg?resize=1&w=1920'
    square: 'https://cdn2.unrealengine.com/vr-week-2023-header-4-1920x1080-376e6c48383f.jpg?resize=1&w=1920'
    alt: 'cover'
tags:
  [
    "数组",
  ]
theme: 'dark'
featured: true
---

<!-- TODO:文章详情 -->
## 参考[leetcode-master](https://github.com/youngyangyang04/leetcode-master.git)

本地地址[D:\personCode\leetcode-master]
### 1.我是详情1111111111111111111


## 题目说明：



## 思路
### 1.对于去重思路的记录

~~~
常见去重逻辑思路梳理
（1）第一种关于去重的思考部分
if (nums[i] == nums[i + 1]) { // 去重操作
    continue;
}
三元组中出现重复元素的情况直接pass掉了
（2）第二种情况
if (i > 0 && nums[i] == nums[i - 1]) {
    continue;
}
注意，这里不太好懂，我们分成例子：在看 {-1, -1 ,2} 这组数据，当遍历到 第一个 -1 的时候
我们只是使用nums[i]的时候，判断只要前一位没有-1，那么找个数组可以收录。

（3）注意循环中的细微差别作为思考的切入点
这里一般不考虑场景，我们以为num[i]和num[i-1]或是num[i+1]一种，但是其实不是这样

详见：

~~~
[详见](https://programmercarl.com/0015.%E4%B8%89%E6%95%B0%E4%B9%8B%E5%92%8C.html#%E5%8E%BB%E9%87%8D%E9%80%BB%E8%BE%91%E7%9A%84%E6%80%9D%E8%80%83)


## 解法说明

### 解法1



### 解法2




### 解法使用TS


## 总结说明