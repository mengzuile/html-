## 第十二章:表格`(table)`

### 一.table表格结构

> 表格由`<table></table>`标签来定义 ,若干行`<tr></tr>`, 每行分割为若干单元格,表头`<th></th>`,内容区域`<td></td>`
> 1. thead / tbody / tfoot 
1) tr 定义表格行
2) th 定义表格头单元格
3) td 定义内容单元格
### 二.table默认特征
> 1、单元格默认平分table 的宽度 
2、th里面的内容默认加粗并且左右上下居中 
3、td里面的内容默认上下居中 左对齐显示 
4、 table 决定了整个表格的宽度； 
5、table里面的单元格宽度会被转换成百分比； 
6、 表格里面的每一列必须有宽度； 
7、表格同一列/行会继承最大值； 
8、th,td中没有margin 
单元格可以包含:(文本、图片、列表、段落、表单、表格) 等等。

### 三.table样式

> 属性 width / height / border 样式属性
border-spacing:x y; 
指定单元格边界之间的水平和垂直间距
border-collapse:collapse; 
如果可能,边框会合并为一个单一的边框,会忽略border-spacing
重置表格默认样式 
table{border-collapse:collapse;} 
table th,table td{padding:0;}
>- 表格单元格布局算法`table-layout`
>1. automatic 默认单/''元格由内容来决定宽度
>2. fixed 单元格平分表格宽度
### 四.table表格合并
> 1、colspan 属性规定单元格横跨的列数（横向合并） <td colspan="2"></td>
> 2、rowspan 属性规定单元格横跨的行数（纵向合并） <td rowspan="2"></td>
>
### 五.display:table;
>
> 支持margin:auto;
> 默认内容撑开宽度
> 支持宽高
> 表格前后带有换行符