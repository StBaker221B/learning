
# markdown grammar

# structure
## level 2 headline
### level 3 headline
...
###### level 6 headline
no level 7 headline

***
cut line
* * *
---

this is 
in the same line,

unless you seperate with a line

many lines count as 1

# font
**bold** *italic*  _italic_also_  ***bold italic***
~~delete line~~  ++underline++ ==highlight==

<font face="黑体">黑体</font>

<font face="微软雅黑">微软雅黑</font>

<font face="STCAIYUN">华文彩云</font>

<font color=#0099ff size=5 face="黑体">黑体</font>
<font color=blue size=5 face="黑体">黑体</font>

<font color=gray size=5 face="Arial">gray</font>
<font color=#00ffff size=3>null</font>


# list
* list start with * - +
- even in the same list
+ you can change the start symbol
    * with indent
        - nesting list
            + as youlike


- [ ] mission list
- [x] missions ...

1. ordered list
2. ...

# table
item1 | item2 |...
-|-|-
a1|a2|a3
b1 | b2 | b3
...|...|...


|item1 | item2 |   item...|
|:-|:-:|-:|
|a1|a2|a3|
|b1 | b2 | b3|
|...|...|...|

# link
add a [link](https://baidu.com "title")

another kind of [link][1]

[1]:https://baidu.com

add a footnote[^1], another one[^2]

[^1]:just a footnote

# pic
![local image](./DinantBelgium.jpg "pic name")
![web image](http://h1.ioliu.cn/bing/TahoeBeach_ZH-CN3786728560_640x480.jpg "pic name")

# citation, notation
> citation
>> second level citation
>>> as deep as you want

a command `cd` or a function `print()` in a line

without `

    def df: 
        sdf
        sdf
        sdf


```c
while(1)
{
    code block;
}
```

$$ x^2 + y^2 = 1  $$

```math
E = mc^2
```
<kbd>Shift</kbd> <kbd>+</kbd> <kbd>Del</kbd> 

<!-- note -->