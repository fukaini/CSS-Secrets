---
title: "勘误表"
issue: "#2"
---

> #### 如何提交勘误？ <a name="how-to">&nbsp;</a>

> 如果你在阅读本书的过程书中发现任何错误（包括编辑、排版、翻译、技术等方面的错误），[请新开一个 issue](https://github.com/cssmagic/CSS-Secrets/issues/new) 来描述这个错误，并请在标题中注明 “提交勘误”。当编辑或译者确认为错误后，将会收录到本页面中。

> 感谢你的严谨让这本书变得圆满，其他读者必将从中受益！


## 中文版勘误 <a name="zh">&nbsp;</a>

### 第 xxiv 页 · 本页的两个代码块

本页有两个代码块，均包含以下这行代码：

> ```stylus
background: linear-gradient(90deg, yellow, red);
```

其中 `90deg` 应为 `0deg`。

<sup>（贡献者：@yifon）</sup>


### 第 30 页 · 第二段

> 对于一个 45° 的直角三角形来说，它的两条直角边是等长的，因此这个算式会变成 ![\sqrt{2a} = a\sqrt{2}](http://latex.codecogs.com/gif.latex?%5csqrt{2a}%20%3d%20a%5csqrt{2})。

句末的算式应为 ![\sqrt{2a^2} = a\sqrt{2}](http://latex.codecogs.com/gif.latex?%5csqrt{2a^2}%20%3d%20a%5csqrt{2})。

<sup>（贡献者：@cssmagic）</sup>


### 第 45 页 · 脚注

> 构成相对质数的这些数字**没有公约数**

“**没有公约数**” 应为 “**没有公约数**（除了 1 以外）”。

<sup>（贡献者：微信网友 “剑猫情缘”）</sup>

### 第 45 页 · “相对质数” 一词

* 第一段：

	> 为了让最小公倍数最大化，这些数字最好是 “相对质数”

	应改为 “……这些数字最好是 ‘互质’ 的”
	
	> 举例来说，3、4 和 5 是相对质数
	
	应改为 “……3、4 和 5 是互质的”
	
	> 要达成相对质数，……
	
	应改为 “要达成互质关系，……”

	> 因为**质数跟其他任意数字都是相对质数**。

	应改为 “因为**质数跟其他任意数字都是互质的**”

* 脚注

	> *相对质数*是一种**数字之间的关系**
	
	应改为 “*互质*是一种**数字之间的关系**”
	
	> 构成相对质数的这些数字……
	
	应改为 “构成互质关系的这些数字……”

	> 比如说，10 和 27 是相对质数……
	
	应改为 “比如说，10 和 27 是互质的……”
	
	> **……一个质数跟其他所有数字都可以构成相对质数。**
	
	应改为 “**……一个质数跟其他所有数字都可以构成互质关系。**”

<sup>（贡献者：微信网友 “剑猫情缘”）</sup>

### 第 61 页 · 第二段

> 因此，把 `max-width` 的值设置为 ![formula](http://latex.codecogs.com/gif.latex?%5csqrt{2}%20%5ctimes%20100%5c%%20%5capprox%20414.4213562%5c%) 是很合理的……

算式右侧的 “**414**.421 356 2%” 应为 “**141**.421 356 2%”。

<sup>（贡献者：@ourfeel）</sup>


### 第 65 页 · 倒数第二个代码块

> ```css
background:    linear-gradient(-45deg, transparent 15px, #58a 0)        right,    linear-gradient(45deg, transparent 15px, #655 0)        left;
```

此条声明中的 `#58a` 和 `#655` 应互换。

<sup>（贡献者：@ArvinTung）</sup>


### 第 108 页 · 图 4-31

> `cosθ = y/r`

> `sinθ = x/r`

图中公式中的 `cos` 应为 `sin`，`sin` 应为 `cos`。

<sup>（贡献者：@peacelee）</sup>


### 第 169 页 · 第二个代码块 · 第 5 行

> ```js
slider.insertBefore(img, div);
```

本行应为：

```js
slider.insertBefore(div, img);
```

<sup>（原载于英文原书勘误表，中文版整理者：@keyfoxth）</sup>


### 第 184 页 · 第四段

> 如果把 `width` 这一行声明注释掉，你会发现其实没有影响。……只有把 width 显式地设置为 900px 之外（或大或小）的其他值，我们才有可能看出区别。

应为：

“如果把 `max-width` 这一行声明注释掉，你会发现其实没有影响。……只有把容器的 `width` 属性指定为 900px 之外（或大或小）的其他值，我们才有可能看出区别。”

<sup>（原载于英文原书勘误表，中文版整理者：@cssmagic）</sup>

***

### 英文原书勘误表 <a name="en">&nbsp;</a>

> by O’Reilly Media, Inc.

* [出版社已确认的](http://www.oreilly.com/catalog/errata.csp?isbn=0636920031123)
* [待确认的](http://www.oreilly.com/catalog/errataunconfirmed.csp?isbn=0636920031123)
