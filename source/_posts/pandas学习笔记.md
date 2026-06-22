---
title: pandas学习笔记
abbrlink: eaac5978
date: 2026-06-22 18:30:14
tags:
---

pandas笔记：
1. 过滤

num_mask = df['num_col']==num_val
str_mask = df['str_col']=='str_val'
filtered_df = df[num_mask & str_mask]

2. 拼接
pd.concat([list1, list2, ...])
3. 填充
4. 重采样
5. 性能优化

Q:
1. 索引有啥重要作用？
2. 