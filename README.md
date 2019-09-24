# Joyce Blog

### [我的博客在这里 &rarr;](http://joycefangmm.github.io)

### 来源
这个博客完全学习于[Hux Blog](http://huxpro.github.io)（[GitHub源码](https://github.com/huxpro/huxpro.github.io/)），一点点学习、创建现有博客，并在他的基础上做了修改。

如想使用该博客模板并了解如何配置，建议看[Hux GitHub](https://github.com/huxpro/huxpro.github.io/)，本博客只供本人学习参考。


### 搭建环境
```
ruby 2.6.4p104 (2019-08-28 revision 67798) [x86_64-darwin18]
```

```
gem 3.0.3
```

```
jekyll 4.0.0
```

```
Bundler version 2.0.2
```


### marckdown内Front Matter配置解释

- nav-style : string
<br>**invert**导航栏字体变成黑色

- header-style : string
<br>**text**头部没有图片，纯文本，导航栏会变成黑色；否则导航栏需要设置图片*header-img*

- catalog : boolean
<br>**true**有侧边栏目录

- header-img : string
<br>头部图片地址，若没有使用*config.yml*内*header-img*

- header-bg-css : string
<br>头部图片背景颜色，若图片不存在就使用该颜色；也可以直接不设置图片使用颜色代替
<br>使用案例："linear-gradient(to right, #24b94a, #38ef7d);"

- header-mask : string
<br>添加黑色蒙层，防止*header-img*图片颜色比较明亮

- header-img-credit : string
<br>用于*header-img*图片上，若非原创图片，需要注明作者

- header-img-credit-href : string
<br>用于*header-img*图片上，若非原创图片，需要注明出处

- mathjax : boolean
<br>是否需要支持Mathjax

- title : string
<br>主标题

- subtitle : string
<br>副标题

- date
<br>此时间优先级高于文件名称时间，博客按照此时间排序展示，post的时间由该属性值 唯一 确定。
<br>*config.yml*设置`future=false`，未来时间的post不展示
<br>非字符串，格式：`2015-03-10 12:00:00`

- author : string
<br>作者

- tags
<br>标识
<br>例子：
```
tags:
    - 知乎
    - 产品
```
或者
```
tags:[知乎 产品]
```

- categories
<br>分类
<br>例子：同上*tags*


### 后期迭代

#### V2.0
- TODO：1、支持双语，即中英文
- TODO：2、完善Category页面

#### V1.0
- 学习[Hux Blog](http://huxpro.github.io)和[Jekyll](https://jekyllrb.com)一步步创建；修改原作者的一些配置已满足自己的需求。

