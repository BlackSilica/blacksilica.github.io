---
title: Markdown语法
categories:  
- 速查表
math: true
mermaid: true
date: 2024-04-03 23:43:12
---
# 标题语法
|markdown|html|可选语法|显示效果|
|--|--|--|--|
|`# 一级标题`|`<h1>一级标题</h1>` |`一级标题<br>=====`|<h1>一级标题</h1>|
|`## 二级标题`|`<h2>二级标题</h2>` ||<h2>二级标题</h2>|
|`### 三级标题`|`<h3>三级标题</h3>` ||<h3>三级标题</h3>|
|`#### 四级标题`|`<h4>四级标题</h4>` ||<h4>四级标题</h4>|
|`##### 五级标题`|`<h5>五级标题</h5>` ||<h5>五级标题</h5>|
|`###### 六级标题`|`<h6>六级标题</h6>` ||<h6>六级标题</h6>|

{% tabs %}

<!-- tab 效果 -->

<details>
<summary>点开看看</summary>

这里是被隐藏的内容

</details>


<!-- endtab -->

<!-- tab 代码 -->

```markdown
<details>
<summary>点开看看</summary>

这里是被隐藏的内容

</details>
```

<!-- endtab -->


{% endtabs %}

{% tabs First unique name %}

<!-- tab First unique name 1 @ri:home-4-line -->

**This is Tab 1.**

<!-- endtab -->

<!-- tab Icon Test @ri:cloud-line -->

**This is Tab 2.**

<!-- endtab -->

<!-- tab -->

**This is Tab 3.**

<!-- endtab -->

{% endtabs %}
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTc4MTcxMDczNF19
-->