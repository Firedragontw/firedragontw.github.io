---
title: Hello I'm Firedragon
---

# this is my first blog

# testing markdown

## 筆記 - 可用語法紀錄 (客製化)
### admonition

:::(note)[筆記]
筆記欄位
:::

:::(info)[資訊]
資訊欄位
:::

:::(success)[成功]
成功欄位
:::

:::(warn)[警告]
警告欄位
:::

:::(danger)[錯誤]
危險欄位
:::

### check mark

- [ ] werwer
- [-] werwer
- [x] werwer

### comment

-# werwwwr
-# werwe [wwer](https://youtube.com)

### formate family

abc **test** abc
abc __test__ abc
abc /test/ abc

## 筆記 - 可用語法紀錄 (原本)

### 標題

# 這是 H1 標題
## 這是 H2 標題
### 這是 H3 標題
#### 這是 H4 標題
##### 這是 H5 標題
###### 這是 H6 標題

```
# 這是 H1 標題
## 這是 H2 標題
### 這是 H3 標題
#### 這是 H4 標題
##### 這是 H5 標題
###### 這是 H6 標題
```

### 連結

[這是鏈接的文字](https://example.com)

```
[這是鏈接的文字](https://example.com)
```

### 圖片

![沒牙](https://i.redd.it/what-do-you-think-toothless-will-look-like-in-the-live-v0-am48m01f28vc1.jpg?width=1170&format=pjpg&auto=webp&s=04451a33ad31914145ac0a68044e9f845a683f0a)

```
![沒牙](https://i.redd.it/what-do-you-think-toothless-will-look-like-in-the-live-v0-am48m01f28vc1.jpg?width=1170&format=pjpg&auto=webp&s=04451a33ad31914145ac0a68044e9f845a683f0a)
```

### 引用

> 這是一個引用

```
> 這是一個引用
```

### 隱藏

||這是一個隱藏||

```
\||這是一個隱藏||
```

### CodeBlock

`little code`

```cpp
include <iostream>
using namespace std;

int layer(int num){
    if(num <= 1) return 1*num;
    return num * layer(num-1);
}

int layer_int = 10;
cout >> layer(layer_int) >> endl;

//--- output ---
3628800
```