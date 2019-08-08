# 布隆过滤器

## 问题引入

### 问题描述

给你$n(\le480000)$个字符串,每个字符串包含$32$个字符,对于每个字符串,询问之前有没有出现过,若出现过,输出`Yes`,否则输出`No`.

### 样例输入/输出

```data
5
aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
bbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbb
cccccccccccccccccccccccccccccccc
aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
dddddddddddddddddddddddddddddddd
```

```data
No
No
No
Yes
No
```

### 时空限制

**6s** **2MB**

## 思路

这题看起来像是乱搞哈希.

你可以试试写个哈希表之类的东西.

## BloomFilter

