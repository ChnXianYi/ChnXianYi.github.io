# Advanced

## CSS 隐藏元素方法

1. display: none(取消加载)
2. visibility: hidden(透明)
3. Position

## 清除浮动

* clear:both
* overflow: hidden
* 伪元素 (:after(什么之后)  :before(什么之前))
* 给父元素添加一个类.clearfix::after {content: "";display: block;clear: both;}

## transition

* property: 过渡的 CSS 属性的名称
* duration: 动画花费时间
* timing-function: 时间曲线
    * ease:默认
    * linear(匀速)
    * ease-in(加速)
    * ease-out(减速)
    * ease-in-out(先快后慢)
* delay: 过渡效果何时开始

## 深层选择器

!> 此条未经推敲，谨慎浏览

```markdown

【old】 /deep/ 单独影响一个样式，强制修改默认样式。可以在 scoped Style 标签中
Sass中使用 ::v-deep
 >>> , 将选择器作用的更深 ， /deep/ , ::v-deep 都是 >>> 的别名
词选择器生成的将是 hash 代
【new】 :dee
```
