---
layout: section
---

# 程式語言的分類

## 以及我們從哪開始學習

---

::div {.h-full .flex .justify-center .items-center}
:::div {.pb-16 .space-y-6}
如果不記得程式語言的發展， {.text-5xl}

::::p {.text-5xl}
你可以觀看
[p.23](/23){.font-mono .text-blue-500 .underline .underline-offset-4}
來重新了解～
::::
:::
::

---
layout: image
---

# 程式語言的多元宇宙

![C Multiple Universe](/c-multiple-universe.png)

<!-- 
注意喔！此圖中，只有 C 跟 C++ 有關係，
另外兩個完全沒關係喔 ( ～'ω')～
-->

---

# 程式語言的分類

### 一般來說，我們大概會這樣分：{.pl-4 .pt-6}

::ul {.pl-18 .pt-4}
* 以「人類是否理解」為分類
* 以「程式設計方法」為分類
* 以「程式語言的設計原因」為分類
::

---
layout: image
---

# 以「人類是否理解」來分類

![Language Classify](/language-classify.png)

---

# 以「人類是否理解」來分類（續）

## 機器語言{.pl-4}

以二進位為主（因現代電腦都是借鑑[馮紐曼架構](https://vocus.cc/article/6735a8c1fd89780001dc7c9d){.text-blue-500 .underline .underline-offset-4}所構成。）

:::div {.flex .justify-center .items-center .mt-1}
::div {.text-center .p-4 .bg-yellow-200 .rounded-6 .font-mono}
10100111 11010000 11010000 10100000 00000000 00000000 00000000 00000000 10010000 10001000 10110100 11010000 {style="font-size: 0.56rem;"}

10100000 00000000 00000000 00000000 11100011 00000000 00000000 00000000 00000000 00000000 00000000 00000000 {style="font-size: 0.56rem;"}

00000000 00000000 00000000 00000000 00000000 11000000 00000000 00000000 00000000 00000000 00000000 00000000 {style="font-size: 0.56rem;"}

00000000 11110011 11100000 00000000 00000000 00000000 10010111 00000000 10000000 00000000 11001010 00000000 {style="font-size: 0.56rem;"}

11001000 00000000 10100110 10000000 00000000 00000000 10101011 10000000 00000000 00000000 00000000 00000000 {style="font-size: 0.56rem;"}

00000000 00000000 00000000 00000000 10000000 00000000 11001000 10000000 10100110 00000000 10100100 10000000 {style="font-size: 0.56rem;"}

11110100 10110000 10010000 11001010 11011000 11011000 11011110 10000000 10101110 11011110 11100100 11011000 {style="font-size: 0.56rem;"}

11001000 10011100 10100100 10000000 11011010 10100000 11100000 11100100 11010010 11011100 11101000 10101001 {style="font-size: 0.56rem;"}

00000000 11110011 00000000 00000000 00000000 00000000 11111010 10000000 11010000 11001010 11011000 11011000 {style="font-size: 0.56rem;"}

11011110 10111000 11100000 11110010 11111010 10000000 11110000 11011010 11011110 11001000 11101010 11011000 {style="font-size: 0.56rem;"}

11001010 11111000 11100100 11000000 00000000 00000000 00000000 10000000 00000000 00000000 00000000 11100110 {style="font-size: 0.56rem;"}

11011000 00000000 00000000 00000000 11110000 11000000 10000000 10000000 10000000 11011000 00000000 10100000 {style="font-size: 0.56rem;"}

10000000 10100000 10000000 11011010 11010001 00000000 10100000 11010100 00000000 10100000 11010000 00000000 {style="font-size: 0.56rem;"}

10100000 11010000 00000000 10100000 11010000 00000000 10100000 11100100 10000000 00000000 00000000 00000000 {style="font-size: 0.56rem;"}
::

👈 二進位程式的範例 {style="font-size: 1.2rem;"}
:::

<!-- 這個二進位程式其實是 python3.11 的 `print("Hello World!")` -->

---

# 以「人類是否理解」來分類（續）

## 組合語言 {.pl-4}

用文字描述電腦處理資料，但依舊很難看懂... ╮(′～‵〞)╭

:::div {.flex .justify-center .items-center .mt-1}
::div {.text-start .p-4 .bg-yellow-200 .rounded-6 .font-mono}
mov rax, 1 {style="font-size: 1.05rem;"}

mov rdi, 1 {style="font-size: 1.05rem;"}

mov rsi, hello {style="font-size: 1.05rem;"}

mov rdx, 14 {style="font-size: 1.05rem;"}

syscall {style="font-size: 1.05rem;"}

mov rax, 60 {style="font-size: 1.05rem;"}

xor rdi, rdi {style="font-size: 1.05rem;"}

syscall {style="font-size: 1.05rem;"}
::
::div
👈 組合語言的範例 {style="font-size: 2rem;"}

當然這不是完全體啦... {.pl-20 .-mt-2 style="font-size: 1.2rem;"}
::
:::

<!-- 這段組合語言是 c 語言中的 hello world

```c
#include <stdio.h>

int main() {
    printf("Hello World!\n");
    return 0;
}
```
 -->

---

# 以「人類是否理解」來分類（續）

## 高階語言 {.pl-4}

用人類能夠理解的語言來進行書寫，目前以英文為主。

::v-click
（沒辦法，都是外國人發明的東西... \_(┐「ε:)_ ） {.block .-mt-2 .text-end .pr-12 style="font-size: 1.2rem;"}
::

::div {.px-18 .mt-6 .page-33-coder}
```py {monaco-run} {lineNumbers: 'on', height: '7rem', outputHeight: '3rem', autorun: false, editorOptions: {fontSize: 18}}
print("Hello World!")
```
::

<style scoped>
.page-33-coder {
    font-size: 1rem;
    font-family: "Noto Sans Mono";
}
</style>

---

::div {.h-full .flex .flex-col .justify-center .items-center .pb-10 .gap-2}
當然，我們學的是 [Python]{.font-mono} 是高階語言！

:::v-click
但是若是深入資安領域，我們也要會「組合語言」才行！ {.text-3xl}
:::
::::p {.text-2xl .mt-4}
:::v-click
至於機器語言...看看就好 [(´-ι_-｀)]{.font-mono}
:::
::::
::

---

# 以「程式設計方法」為分類

::div {.h-full .grid .grid-cols-2 .p-4}
:::div {.flex .flex-col .justify-center .items-center .gap-2 .rounded-tl-8 .rounded-bl-8 .bg-sky-200}
程序導向程式設計 {.text-4xl}

Procedure-Oriented Programming {.text-xl .font-mono}
:::
:::div {.flex .flex-col .justify-center .items-center .gap-2 .rounded-tr-8 .rounded-br-8 .bg-rose-200}
物件導向程式設計 {.text-4xl}

Objective-Oriented Programming {.text-xl .font-mono}
:::
::

---

::div {.h-full .flex .justify-center .items-center .flex-col .pb-10 .gap-4}
:::p {.text-2xl}
關於這種分類方式，之後有機會再來開堂課講 [(*´Д`)つ))´∀`)]{.font-mono}
:::
:::p {.text-4xl}
::::v-click
但你要知道 [Python]{.text-rose-600 .font-mono} 是「[物件導向程式語言]{.text-rose-600}」。
::::
:::
::

::p {.absolute .w-full .text-center .bottom-3 .text-xl .text-slate-400}
:::v-click
另外，要知道其實不只有這些分類...
:::
::

---

# RECAP {.font-mono}

::v-clicks
:::ul {.pt-4 .pl-16}
* 人類比較能了解的是「高階語言」。
* 機器只看得懂二進位。
* 所以我們定義了規則把「高階語言」轉為「二進位」。
* [Python]{.font-mono} 是**高階語言**{.text-rose-600}。
* 分類方法還有很多，但時間有限講不完...[ლ(ﾟдﾟლ)]{.font-mono}。
* [Python]{.font-mono} 是**物件導向程式語言**{.text-rose-600}。
:::
::