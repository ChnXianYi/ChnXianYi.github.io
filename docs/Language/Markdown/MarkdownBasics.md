# Markdown

## 标题

```markdown
    # 一级标题
    ...
    ###### 六级标题
```

***

## *斜体* **粗体** ***粗斜体***

```markdown
    斜体 *text* _text_
    粗体 **text** __text__
    粗斜体 ***text*** ___text___
```

***

## 分隔线

```markdown
    ***
    * * *
    ******
    - - -
    -----------
```

***

## ~~删除线~~

```markdown
    ~~删除线
```

***

## <u>下划线</u>

```markdown
    <u>下划线</u>
```

***

## 脚注

> 本文档不适用
[^1]

```markdown
    [^1]
    文档末尾进行脚注赋值
```

***

## 列表

### 无序列表

* \*
* \+
* \-

```markdown
* *
+ +
- -
```

***

### 有序列表

1. 有序
2. 数字+.

```markdown
1. 有序
2. 数字+.
```

***

### 嵌套

* 嵌套
    * 嵌套

```markdown
* 嵌套
    * 嵌套
```

***

## 区块

> 区块
>> 区块显示

***

## 代码块

`function()` 函数

```js
let code = 'js'
alert(js);
```

```markdown
    `function()`函数
    ```js
    let code = 'js'
    alert(js);
    ```
```

***

## 链接

[Google](https://www.google.com.hk/?hl=zh-cn)

```markdown
    [Google](https://www.google.com.hk/?hl=zh-cn)
```

<https://www.google.com.hk/?hl=zh-cn>

```markdown
    <https://www.google.com.hk/?hl=zh-cn>
```

[Google]

```markdown
    [Google]
    文档末尾进行变量赋值
    [Google]: https://www.google.com.hk/?hl=zh-cn
```

***

## 图片

![alt:'alt'](https://www.google.com.hk/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png)

```markdown
    ![alt:'alt'](url)
```

![img]

```markdown
    ![img]
    文档末尾变量赋值
```

<img src="https://www.google.com.hk/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png" width="10%">

```markdown
    <img src='url' width='10%'>
```

***

## 表格

|左对齐|居中|右对齐|
|:-------|:-------:|------:|
|单|元|格|

```markdown
    |左对齐|居中|右对齐|
    |:-------|:-------:|------:|
    |单|元|格|
```

[^1]: text
[Google]: https://www.google.com.hk/?hl=zh-cn
[img]: https://www.google.com.hk/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png
