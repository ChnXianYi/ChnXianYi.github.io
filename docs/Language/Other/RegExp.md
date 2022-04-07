# RegExp

Regular Expression - 一种文本模式。旨在使用单个字符串来描述、匹配一系列匹配某个句法规则的字符串
<br>

## 语法

### 普通字符

|字符|描述|示例|
|:-------|:-------:|:-------:|
|`[ABC]`|匹配 `[...]` 中的所有字符| `/[aeiou]/g` 匹配字符串 `"Example 123"` 中所有的 `e o u a` 字母。<br>{{ inputRegExp('Example 123',/[aeiou]/g)}}|
|`[^ABC]`|匹配除了`[...]`中字符的所有字符| `/[^aeiou]/g` 匹配字符串`"Example 123"`中除了`e o u a`的字符。<br>{{ inputRegExp('Example 123',/[^aeiou]/g)}}|
|`[A-Z]`|`[A-Z]` 表示一个区间，匹配所有大写字母，`[a-z]` 表示所有小写字母。| `/[A-Z]/g` 匹配字符串`"Example 123"`中所有的大写字符。<br>{{ inputRegExp('Example 123',/[A-Z]/g)}}|
|`.`|匹配除换行符（\n、\r）之外的任何单个字符，相等于 `[^\n\r]`| `/./g` 匹配字符串`"Example 123"`中所有的字符。<br>{{ inputRegExp('Example 123',/./g)}}|
|`[\s\S]`|匹配所有。`\s` 是匹配所有空白符，包括换行，`\S` 非空白符，不包括换行。| `/[\s\S]/g` 匹配字符串`"Example 123"`中所有的字符。<br>{{ inputRegExp('Example 123',/[\s\S]/g)}}|
|`\w`|匹配字母、数字、下划线。等价于 `[A-Za-z0-9_]`| `/[\w]/g` 匹配字符串`"Example 123"`中所有的字符。<br>{{ inputRegExp('Example 123',/[\w]/g)}}|

---

## 正则表达式中的特殊字符

|字符|描述|示例|
|:-------|:-------:|:-------:|
|`\`|转义字符，表示下一个字符将进行转义| |
|`^`| | |
|`$`| | |
|`*`|匹配前一个表达式0次或多次,等价{0,}|`/bo*/`匹配`'book'`中的{{inputRegExp('book',/bo*/)}}<br>`/bo*/`匹配`'back'`中的{{inputRegExp('back',/bo*/)}}|
|`+`|匹配前一个表达式1次或多次,等价{1,}|`/bo+/`匹配`'book'`中的{{inputRegExp('book',/bo+/)}}<br>`/bo+/`匹配`'back'`中的{{inputRegExp('back',/bo+/)}}|
|`?`| | |
|`.`|默认匹配除换行符之外的任何单个字符|`/.n/`匹配`'name is nico tiny'`中的{{inputRegExp("nay, an apple is on the tree",/.n/)}}|
|`(x)`|匹配 'x' 并且记住匹配项。其中括号被称为捕获括号| |

## 例子

### 多看阅读Epub

多看阅读读电子书的效果我比较喜欢，但是epub格式下图片不能够放缩。导致观感不是很好，但是多看提供了交互图的方式。此例旨在匹配插图修改为支持交互图的方式

```html
<p style="text-align: center;"><img alt="001" src="../Images/001.jpg" /><br /></p>
```

由于本人看的轻小说大体图片格式是这样，需要更改为如下

```html
<div class="illus duokan-image-single"><img alt="001" src="../Images/001.jpg" /></div>
<div class="illus duokan-image-single"><img alt="009" src="../Images/009.jpg" /></div>
```

方法为匹配到图片序号，然后进行替换

* 查找语句为`/<p.*><img alt="(.*)".*/`
* 替换语句为`/<div class="illus duokan-image-single"><img alt="\1" /></div>/`

---

### vscode 搜索和替换

需要将由 ^^ 字符括起来的文字转换为`<small class="pass">` 以达到效果

查找语句为 `\^(.*)\^`

替换语句为 `<small class="pass">$1</small>`

---
