---
layout: post
title: 在VS中使用正则替换
date: 2016-12-06
categories: blog
tags: [js,ES6]
description: 
---

### JavaScript 和 ES5，ES6 是什么关系

1.ES5和ES6是国际标准，JavaScript是标准的实现


### js ==与===区别

- 对于string,number等基础类型，==和===是有区别的
	--不同类型间比较，==之比较“转化成同一类型后的值”看“值”是否相等，===如果类型不同，其结果就是不等
- 对于Array,Object等高级类型，==和===是没有区别的
	--进行“指针地址”比较
- 基础类型与高级类型，==和===是有区别的
	--对于==，将高级转化为基础类型，进行“值”比较
	--因为类型不同，===结果为false

### Changelog

- 2016-12-06 创建