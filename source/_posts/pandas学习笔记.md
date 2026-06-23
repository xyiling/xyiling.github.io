---
title: pandas学习笔记
abbrlink: eaac5978
date: 2026-06-22 18:30:14
tags:
---

pandas笔记：
1. 过滤

```python
num_mask = df['num_col']==num_val
str_mask = df['str_col']=='str_val'
filtered_df = df[num_mask & str_mask]
```

2. 拼接
```python
pd.concat([list1, list2, ...])
```
3. 填充
4. 重采样
5. 性能优化

Q:
1. 索引有啥重要作用？

pandas支持两个行坐标访问方式，分别是loc和iloc，访问过滤后的df有不同的行为：
    - df.loc[1]访问索引值为1的数据，如果某个切片没有索引值为1的数据，pandas会抛出异常。
    - df.iloc[1]访问第2行的数据
2. 