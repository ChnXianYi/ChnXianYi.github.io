# RegExp

Regular Expression - 一种文本模式。旨在使用单个字符串来描述、匹配一系列匹配某个句法规则的字符串

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
