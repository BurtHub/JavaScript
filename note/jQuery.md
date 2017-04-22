# **jQuery.com** 
 * JohnResig 创建于2006年开源项目
 * 主要用来操作 DOM（document）
 * $是 (jQery) 缩写模式

####  大部分浏览器支持
 * document.getElementById()；
 * document.getElementByTagName()；

#### IE8以下不支持
 * document.getElemntByClassName()；

#### 文件
 * 1. jQuery-1.8.3.js			(开发版->直接修改源码)
 * 2. jQuery-1.8.3.min.js 	(压缩版->直接使用)

#### 基本使用
 * 先引入jQuery的文件
 * 在 script中使用 
 * $(document) .ready(function(){ ***代码区*** });

#### 基本使用
 * 选择器机制，可以使用 css 选择器
 * 封装了DOM操作，简化节点等操作
 * 浏览器操作，包括 IE 6
 * 封装了常用事件
 * 完善的 ajax
 * 链式操作
 * 隐式迭代 比如使用jQuery获取所有元素，设置方法，不用遍历
 * 插件机制
 * 丰富的API
 * 
> 选择器使用
> 
1. $('#id')  $('.class')  $('p') html标签
2. $('.list li') 层次选择器
3. $('.list li , list2 li') 分组选择器 
4. :frist :odd :even :last
5. :eq(num) 特定索引元素
6. $()获取的元素无法使用原生 js 操作
7. $（document）.ready()可以写多个，按照顺序执行
8. window.onload（） 必须等待页面所有元素加载完成后执行（避免图片延迟加载造成整个页面的卡顿）
9. jQuery转化为DOM对象get(index)