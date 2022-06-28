# 【模板】文艺平衡树

## 题目描述

您需要写一种数据结构（可参考题目标题），来维护一个有序数列。  

其中需要提供以下操作：翻转一个区间，例如原有序序列是 $5\ 4\ 3\ 2\ 1$，翻转区间是 $[2,4]$ 的话，结果是 $5\ 2\ 3\ 4\ 1$。

## 输入格式

第一行两个正整数 $n,m$，表示序列长度与操作个数。序列中第 $i$ 项初始为 $i$。  
接下来 $m$ 行，每行两个正整数 $l,r$，表示翻转的区间。

## 输出格式

输出一行 $n$ 个正整数，表示原始序列经过 $m$ 次变换后的结果。

## 样例 #1

### 样例输入 #1

```
5 3
1 3
1 3
1 4
```

### 样例输出 #1

```
4 3 2 1 5
```

## 提示

【数据范围】  
对于 $100\%$ 的数据，$1 \le n, m \leq 100000 $，$1 \le l \le r \le n$。
