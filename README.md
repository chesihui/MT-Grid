#关于
* 基于 [Semantic.gs](http://semantic.gs/)扩展完成layout，适用于需兼容ie6&ie7的人民；
* 使用sass，预编译配置计算宽度 
* 代码简洁易用，易移植到个性化项目中

#使用的目的
* 支持响应式的fluid布局，更适用在多终端，因此需要一个成熟的layout计算方法,同时要支持ie6&7；
* fluid布局可以让页面响应屏幕大小的情况下可缩放；
* 减少media query的使用

#配置
```
//栅格系统配置
$columns: 21;
$column-width: 30px;
$gutter-width: 10px;

//液态设置100%；固态设置固定px,如：$total-width: 1000px; 
$total-width: 100%;

//针对ie6&ie7的hack; 
$fixie-width: 960;

```
