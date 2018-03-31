---
layout: post
title: "第一次發文"
date: 2018-03-31 16:37:00 +0800
categories: zh
tags: 其他 閒聊 中文
---
這兩天趁著長假期，終於下定決心用Jekyll寫博客，然後生成html發在github page。

之後會慢慢更新的，目前預定是這樣：
- 改博客主題，大概會是MD吧
- 主頁分成中英日文三語入口，三面放的東西當然也不同，英文主談技術，中文是雜項／日常／摘要／作品，日文是ACG相關的
- 有一些不方便在其他地方說的也會放上這，基本上都是中文

目前主要在破乎上打滾，但氛圍實在是不敢恭圍，加上各種有的沒的小麻煩，退乎進行中，ＦＢ／ＰＬＵＲＫ也是潛水狀態，技術話題沒人有興趣，然而我除了技術外實在沒有談資，也就罷了

這年的TODO也列出來一下，權作年末打臉的記錄用：

`必需`
- 完成Programming in Haskell
- 完成CPPP -> Effective CPP
- 令寫小說變成習慣
- 完成Programming Rust -> 寫一個自動check git status -> parse rst doc in Python code -> gen doc -> commit to doc repo, 公司用的

`希望能做到`
- SICP + Racket
- Introduction to Algorithm
- SCAPP
- OpenGL
- Effective Modern C++

至於編譯原理,網絡之類的基本功,下年或後年再說

目前CPPP基本已完成……那這篇就這麼多吧，最後順帶測試一下代碼塊轉換能不能用

```cpp
#include <string>
#include <iostream>
const std::string a = "Hello World!";
int main() {
    std::cout << a << std::endl;
}
```