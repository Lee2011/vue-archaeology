---
title: 早期探索
type: guide
order: 4
---

> 时间：13/7/29 上午12:35
> 坐标：871ed9126639c9128c18bb2f19e6afd42c0c5ad9
> 事件：对最初想法的探索，seed 的诞生

这是第二次代码提交，在 `package.json` 中将 repo 命名为 `seed`。之后很长一段时间里都一直沿用着这个名字，可以称作 `seed` 时代。

这次提交并没有正式开始写代码，而是在 `explorations` 文件夹中写了个简单的 [getset.html](https://github.com/vuejs/vue/blob/871ed9126639c9128c18bb2f19e6afd42c0c5ad9/explorations/getset.html) 文件来试验自己的想法。

这个 html 虽然简单，总共只有66行代码，但是却实现了 Vue 最核心的功能之一：响应的数据绑定。

通过学习这60几行代码，我们可以相对比较容易的理解 Vue 最基本的思想。

<iframe width="100%" height="600" src="//jsfiddle.net/lixinghua/858dLt9L/embedded/result,js,html/" allowfullscreen="allowfullscreen" frameborder="0"></iframe>

## 代码分析



### 参考阅读

* [document.getElementById](https://developer.mozilla.org/en-US/docs/Web/API/Document/getElementById)
* [Element.innerHTML.replace](https://developer.mozilla.org/en-US/docs/Web/API/Element/innerHTML)
* [Element.querySelectorAll](https://developer.mozilla.org/en-US/docs/Web/API/Element/querySelectorAll)
* [Element.removeAttribute](https://developer.mozilla.org/en-US/docs/Web/API/Element/removeAttribute)
* [Object.defineProperty](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/defineProperty)