---
title: "微互動元件庫"
date: 2025-03-20T16:22:00+08:00
lastmod: 2025-03-20T16:22:00+08:00
author: "專注的閒人"
avatar: "/avatar/avatar-512X512.png"
cover: "/cover/cover1.png"
coverAlt: "微互動"
images:
  - "/cover/cover1.png"
categories:
  - "互動設計"
tags:
  - "微互動"
  - "愉悅"
nolastmod: true
draft: false
isCJKLanguage: false
---

為 UI 元件設計了令人愉悅的微互動。

<!--more-->

這些包括按鈕點擊、滑鼠懸停動畫、空狀態和細緻的回饋，讓應用程式感覺更加動態且精緻。

> *本專案為展示用途而虛構。 [Cover Refer from here](https://dribbble.com/shots/14390245-VR-Editor-Microinteractions)*

# H1 標題（文章標題）

## H2 標題（段落標題）

### H3 標題（小節標題）

#### H4 標題

##### H5 標題

###### H6 標題

## 基本文字樣式

**粗體文字**  
*斜體文字*  
~~刪除線~~  
`單行程式碼` (inline code)

## 🔠 區塊引用 & 清單

> 這是一段引用文字。  
> 可以換行使用 `>`。

- 無序清單項目 1
- 無序清單項目 2
  - 子項目
  - 子項目

1. 有序清單項目一
2. 有序清單項目二

## 💻 程式碼

```bash
bash run.sh
```

### Python 範例

```python
def greet(name):
    return f"Hello, {name}!"

print(greet("World"))
```

### JavaScript 範例

```js
function greet(name) {
  return `Hello, ${name}!`;
}
console.log(greet("World"));
```

### 設定不同的Coding Style

參考 [Hugo Doc](https://gohugo.io/content-management/syntax-highlighting/)

```go {linenos=inline hl_lines=[3,"6-8"] style=emacs}
package main

import "fmt"

func main() {
    for i := 0; i < 3; i++ {
        fmt.Println("Value of i:", i)
    }
}
```

## 📐 數學公式

Inline formula：$\( a^2 + b^2 = c^2 \)$

simple latex equation:

```math
\[
  x^2 + y^2 = z^2
\]
```

Complex latex equation:

```math
\[
\begin{aligned}
KL(\hat{y} || y) &= \sum_{c=1}^{M}\hat{y}_c \log{\frac{\hat{y}_c}{y_c}} \\
JS(\hat{y} || y) &= \frac{1}{2}(KL(y||\frac{y+\hat{y}}{2}) + KL(\hat{y}||\frac{y+\hat{y}}{2}))
\end{aligned}
\]
```

using `$`:

$$\int_{-\infty}^{\infty} e^{-x^2} dx$$.

using `$$`:

$$
\int_{0}^{1} x^2 \,dx = \frac{1}{3}
$$

## 🧩 表格

| 專案名稱         | 類型         | 狀態     |
| ------------ | ---------- | ------ |
| Portfolio UI | Web Design | ✅ 完成   |
| App Redesign | Mobile     | 🛠 開發中 |

## 🔗 超連結與圖片

[訪問我的網站](https://focusidler.com)
![alt text](/demoimg.jpeg)

<!-- 這是一段 HTML 註解，不會顯示出來 -->


## 🧾 註腳範例

這是一段帶有註腳的句子。[^1]

[^1]: 註腳說明文字出現在文章底部。

