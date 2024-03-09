# Typora Theme Kiwi

## Basic Syntax

### Headings

> ## Heading level 2 标题级别 2
>
> ### Heading level 3 标题级别 3
>
> #### Heading level 4 标题级别 4
>
> #### Heading level 5 标题级别 5
>
> ##### Heading level 6 标题级别 6

### Emphasis

**This is bold text** **这是粗体文本**

_This text is italicized_ _这是斜体文本_

**This text is _extremely_ important** **此文本*非常*重要**

**_All this text is important_** **_所有这些文本都很重要_**

### Blockquotes

> Text that is a quote 引用文本
>
> adaadasd ad
>
> > Text that is a quote 引用文本

### Lists

#### Ordered Lists

1. First item 第一项

2. Second item 第二项

3. Third item 第三项

4. Fourth item 第四项

#### Unordered Lists

- First item 第一项
- Second item 第二项
- Third item 第三项
- Fourth item 第四项

### Code

At the command prompt, type `echo Hello world`
在命令行提示符下，输入 `echo Hello world`

### Horizontal Rules

---

### Links

Search engine [Google](www.google.com)
搜索引擎[谷歌](www.google.com)

### Image

![Google](https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png)

## Extended Syntax

### Tables

| Syntax    | Description |   Test Text |
| :-------- | :---------: | ----------: |
| Header    |    Title    | Here's this |
| Paragraph |    Text     |    And more |

### Fenced Code Blocks

```c
#include <stdio.h>
int main(void) {
   // printf() displays the string inside quotation
   printf("Hello, World!");
   return 0;
}
```

### Math

$$
{}
1 + 1 = 2; //注释 \\
1 + 2 = 3
$$

### Footnotes

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.
[^bignote]: Here's one with multiple paragraphs and code.<br> Indent paragraphs to include them in the footnote.

### Heading IDs

### Definition Lists

First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.

### Strikethrough

~~This was mistaken text~~

~~这是错误文本~~

### Checkbox

- [ ] Write the press release
- [ ] Update the website
- [ ] Contact the media

### Emoji

Gone camping! :tent: Be back soon.

That is so funny! :joy:

### Highlight

I need to highlight these ==very important words==.

### Subscript

This isn’t common, but some Markdown processors allow you to use subscript to position one or more characters slightly below the normal line of type. To create a subscript, use one tilde symbol (~) beforeand after the characters.

```markdown
H~2~O
```

The rendered output looks like this:

H~2~O

Alternatively, if your Markdown application supports HTML, you can use the sub HTML tag.

This is a <sub>subscript</sub> text

这是<sub>下标<sub>文本

### Superscript

This isn’t common, but some Markdown processors allow you to use superscript to position one or more characters slightly above the normal line of type. To create a superscript, use one caret symbol (^) before and after the characters.

```markdown
X^2^
```

The rendered output looks like this:

X^2^

Alternatively, if your Markdown application supports HTML, you can use the sup HTML tag.

This is a <sup>superscript</sup> text

这是<sup>上标<sup>文本

### Alerts

> [!NOTE]
>
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

### Automatic URL Linking

http://www.google.com

### Disabling Automatic URL Linking

`http://www.google.com`

<!-- this is a comment -->
