# TreeGrid-JQuery
TreeGrid结合json例子

效果链接https://gaoguangqing.github.io/TreeGrid-JQuery/

引入如下css
```
<link rel="stylesheet" href="css/bootstrap.css" />
<link rel="stylesheet" href="css/jquery.treegrid.css" />
```

引入如下js
```
<script type="text/javascript" src="js/jquery.min.js"></script>
<script type="text/javascript" src="js/jquery.treegrid.min.js"></script>
<script type="text/javascript" src="js/jquery.treegrid.extension.js"></script>
<script type="text/javascript" src="js/tree.table.js"></script>
```
注意：
```
jquery.treegrid.extension.js是对源码有更改
加了tr.data("rowData",item);
```
这些为通用配置
```
{
	title: '菜单ID',
	field: 'id',
	visible: false,
	align: 'center',
	valign: 'middle',
	width: '70px'
}

```
