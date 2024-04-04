---
title: Markdown语法
categories:  
- 速查表
math: true
mermaid: true
date: 2024-04-03 23:43:12
---
# 标题语法
| markdown         | html               | 显示效果          |
| ---------------- | ------------------ | ---------------- |
| `# 一级标题`      | `<h1>一级标题</h1>` | <h1>一级标题</h1> |
| `## 二级标题`     | `<h2>二级标题</h2>` | <h2>二级标题</h2> |
| `### 三级标题`    | `<h3>三级标题</h3>` | <h3>三级标题</h3> |
| `#### 四级标题`   | `<h4>四级标题</h4>` | <h4>四级标题</h4> |
| `##### 五级标题`  | `<h5>五级标题</h5>` | <h5>五级标题</h5> |
| `###### 六级标题` | `<h6>六级标题</h6>` | <h6>六级标题</h6> |

# 文本效果

| 效果名称 | markdown                | html | 效果 |
| -------- | ----------------------- | ---- | ---- |
| 粗体     | `**粗体**`   `__粗体__` | `<b>粗体</b>` | **粗体** |
| 斜体     | `*斜体*` `_斜体_`       | `<i>斜体</i>` | *斜体* |
| 粗斜体   | `***粗斜体***`  `___粗斜体___`      | `<b><i>粗斜体</i></b>` | ***粗斜体*** |
| 删除线   | `~~删除线~~`            | `<s>删除线</s>` | ~~删除线~~ |
| 行内代码 | `` `行内代码` `` | `<code>行内代码</code>` | `行内代码` |
| 文字上标 | `文字^上标^` | `文字<sup>上标</sup>` |文字^上标^|
| 文字下标 | `文字~下标~` | `文字<sub>下标</sub>` | 文字~下标~ |
| 键盘码 |  | `<kbd>Ctrl</kbd>` | <kbd>Ctrl</kbd> |
| 颜色文字 |  | `<font color="#54FF9F">颜色文字</font>` | <font color="#54FF9F">颜色文字</font> |
| 文字大小 |  | `<span style="font-size:0.7em;">0.7em 文字大小</span>` | <span style="font-size:0.7em;">0.7em 文字大小</span> |
| 文本缩写 |  | `<abbr title="文本缩写">wbsx</abbr>`    | <abbr title="文本缩写">wbsx</abbr> |
|文本左对齐|                                |`<div align=left>文本左对齐</div>`|<div align=left>文本左对齐</div> |
|文本居中|                                |`<div align=center>文本居中</div>`|<div align=center>文本居中</div>|
|文本右对齐|                                |`<div align=right>文本右对齐</div>`|<div align=right>文本右对齐</div>|
|文本扩展|                                |`<div align=justify>文本扩展</div>`|<div align=justify>文本扩展</div>|

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

<!--stackedit_data:
eyJoaXN0b3J5IjpbOTg1MjkwMjA1LDMyODIxMDAwMSwtNzgxNz
EwNzM0XX0=
-->