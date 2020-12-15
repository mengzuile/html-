## 第十八章:iframe,阿里图标,swiper

### 一.内联框架`(iframe)`

>```html
><iframe src='200' width='200' height='' frameborder='1' scrolling='yes'></iframe>
>```
> 1. width和height属性用于规定iframe的宽度和高度
> 2. 默认是象素,可以使用百分数
> 3. 放在body标签里面使用,可以和其它任何标签一起使用
> 4.  frameborder = "0" / "1" 无边框 / 有边框
> 5. scrolling 规定是否显示滚动条 yes/no/auto
> 6. 使用iframe作为链接的目标 
> iframe 可用作链接的目标 target,链接的target属性必须引用 iframe 的 name 属性
>
> ```html
> <iframe src='' name='iframe_a'></iframe>
> <p>
>   <a href='www.baidu.com' target='iframe_a'>百度</a>
> </p>
> ```
>### 二.阿里图标
> 1. 添加方法,点击购物车
> 2. 引入方法
> 3. 使用方法
> - [阿里图标官网](http://www.iconfont.cn/plus)
>
### 三.swiper
> 1. 引入方法
> 2. 修改参数方法
> 3. 调试方法
> - [swiper官网](http://www.swiper.com.cn/)