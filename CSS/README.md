## CSS 真是想写点什么，发现好多东西要补充，之前都是应付得了工作即可

## [闲逛，发现不错的教程，不适合入门。（适合再就业 😂）](http://www.cnblogs.com/wangfupeng1988/p/4237249.html)

## 费力的堆字，只是想改变，知其然而不知其所以然(因为这样的简历，人家不要我 😅)

学习 css2.1 版本的选择器：
基础选择器：标签选择器、id 选择器、类选择器、通配符选择器。
高级选择器：后代选择器、交集选择器、并集选择器。

## 问题：如何使用一句样式，完成下面的样式？（以前知道不会用，还是感慨）

![Alt text](/CSS/不一样的选择器.png 'Optional title')

```    
    <style>
        ul li+li {
            border-top: 1px solid skyblue;
        }
    </style>
```

## [关于盒子模型](http://www.cnblogs.com/wangfupeng1988/p/4287292.html)  
    啰嗦一句：大名鼎鼎的bootstrap也把box-sizing:border-box加入到它的 * 选择器中，我们为什么不这样做呢？

## 虽然我知道，如何用什么属性画三角形？（transparsent）但是没有实操，这不科学
```
    div {
            border: 10px solid;
            border-color: red transparent transparent transparent;
            width: 0;
        }  
```

## [关于浮动，简单过一下，记住下面的话](http://www.cnblogs.com/wangfupeng1988/p/4314160.html)
you remember 'float被设计出来的初衷是用于——文字环绕效果'，要深刻理解。

罪过，尽然不记得‘行块二象性’这个拗口的词汇是啥意思......

经典清楚浮动：  

        .clearfix:after {
            content: '\A';  
            display: block;
            clear: both;
        }

\A是ASCII码不是A， 不过你也可以使用 空格
'\A' 提升逼格用的

## position：static/relative/absolute/fixed
> static  静态的，默认  
> relative  相对于自己的原始位置，移动    
> absolute  相对于第一个有定位父级的文章，移动   
> fixed   相对于，浏览器视口   


## 总结 ：  
我之所以写这文字（乱写），是为了巩固基础，换一个被人的理解，结合自己的想法，巩固CSS基础；
css属性五个大重点：
> 文字和字本  
> 盒模型  
> 背景  
> 浮动  
> 定位  

## 字体  
    font: italic bold 30px/50px "consolas";

字体属性连写，意义：倾斜 加粗 大小 行高 字体

## 盒模型  
    box-sizing: content-box/border-box
    content-box，默认值，此时设置盒子的width 为内容的宽，padding 和 border 设置宽度的时候，都会影响盒子实际，宽度。
    border-box，推荐使用，此时设置盒子的width 为border内的宽度（含有border的宽度）；bootstrap也是这么使用的。

## 背景  

    这个不好写，但是看的时候，比较困难，主要是CSS3 丰富了属性，背景图的切割、定位......  
    
