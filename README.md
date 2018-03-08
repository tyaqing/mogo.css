# Argon-CSS
是一个可移植的布局插件,采用`less`语言编写.

[GitHub地址](https://github.com/tyaqing/mogo.css)
使用npm自动构建

```
    npm run build  
```

## 1.颜色/Color

|名称|类|描述|
|---|---|---|
|主色|.c-primary|主色调|
|成功|.c-success|用于成功信息|
|警告|.c-warning|用于警告信息|
|错误|.c-error|用于错误信息|
|默认字体颜色|.c-grey |用于重要文字信息|
|灰色等级1|.c-grey-1|用于普通级信息、引导词|
|灰色等级2|.c-grey-2 |用于次要的文章信息、普通按钮描边|
|灰色等级3|.c-grey-3 |用于分割线|
|灰色等级4|.c-grey-4 |用于背景色|
|主色|.bg-primary|主色调|
|成功|.bg-success|用于成功信息|
|警告|.bg-warning|用于警告信息|
|错误|.bg-error|用于错误信息|
|默认字体颜色|.bg-grey |用于重要文字信息|
|灰色等级1|.bg-grey-1|用于普通级信息、引导词|
|灰色等级2|.bg-grey-2 |用于次要的文章信息、普通按钮描边|
|灰色等级3|.bg-grey-3 |用于分割线|
|灰色等级4|.bg-grey-4 |用于背景色|
![](images/屏幕快照2018-03-05下午3.07.18.png)
## 2.字体/font
> 字体大小默认分为8 10px-24px种  每2px递增

|类|样字体大小|
|---|---|
|`fs-n`| 字体大小,n的范围为`10,12,...,24`|
|`lh-n`| 行高,n的范围为`10,12,...,24`|
|`text-decoration`|删除线|
|`blod` | 加粗|
|`text-c`|内容居中|
|`text-r`|内容右对齐|
|`text-l`|内容左对齐|
|`&nbsp;`|占位符|
|`.line-n`|只显示n行,其他显示省略号.n的范围`1-3`|

## 盒模型
|类名|介绍|
|-|-|
| ` .content` | 自动加上内边距 `padding:15px`  |
| ` .content.radius` | 自动加上圆角 `border-radius: 5px;`  |
|`.block`|强制转换成盒模型,常用于`img`标签|
|  .pd-2,.pd-4,...,.pd-20  | 内边距  `pading: n px ` |
|  .pd-t-2 ~ .pd-t-20  | 内上边距 ` padding-top:20px`  |
|  .mg-2,.mg-4,...,.mg-20  | 外边距  `margin: n px ` |
|  .mg-t-2 ~ .mg-t-20   |  外上边距` margin-top:20px`  |
|`.float-l`|向左浮动|
|`.float-r`|向右浮动|
|`.border-b`| 下方分隔线 `border-bottom:1px solid @grey-3;`|
|`.border-l`|左端分隔线`border-left: 1px solid @grey-3;`|
|`clearfix`|清除浮动,在浮动的父级元素上添加|
|`round`|将形状变成圆形|
|`shadow`|为盒模型加上阴影,颜色为@grey-3|

## 助手类
|类名|介绍|
|-|-|
|`.hidden`|隐藏元素|

