# vuePractice
VUE学习
***
此路径下的文件是我VUE学习的练习文件，以记录自己的学习路径和遇到的问题；
版本更新主要是以日期为基准；
# V-2017-05-15
### 1.知识点：
#### 一、Vue原理
1.通俗的来说Vue是一片html代码外加一串json数组；
2.Vue是一个MVVM框架；MVVM框架是指MVC\MVP等框架的统称；
#### 二、Vue的一些规则
* `el`是指`element`，选择器可以是id选择器、class选择器或者标签选择器;
*  `data`里可以放`array`、`number`、`Boolean`、`json`等数据格式；
### 此次更新主要涉及到的知识点有：
* `v-model`——一般表单元素(input)，双向绑定
* `v-for="value in arr"`循环
* 事件`v-on:事件="方法"`
* `v-show="true/false"`隐藏消失

# V-2017-05-17
* 1.Vue中常见的简写如`v-on:click`-->`@click`;
* 2.取消事件冒泡的两种方法：1）原生JS；2）直接在@click后加stop;
* 3.阻止默认行为的两种方法：1）原生JS；2）直接在@click后加prevent;
* 4.键盘事件`@keydown.up`、`@keydown.down`、`@keydown.left`、`@keydown.right`等；
* 5.添加属性使用`v-bind:src=""`可简写为-->':src=""';
* 6.添加class的三种方法：1）`:class="[数据名称]"`；2）`:class="{class:true,class:true}"`；3)`:class="json"`;
* 7.添加行间的style样式方法和class一样；
* 8.模板
* * 1.语法`{{msg}}`双括号表示数据双向绑定；
* * 2.取消数据双向绑定，单次插值，在不需要绑定的数据上加`v-once`(在Vue-1中，单次插值使用`{{* msg}}`);
* * 3.html转义输出`v-html="html"`；它是指将传到msg里面的数据当做html解析(在Vue-1中，单次插值使用`{{{msg}}}`)；
* 9.常见的过滤器：`toUpperCase`、`toLowerCase`、`text[0].toUpperCase() + text.slice(1)`-->首字母大写、`'$' + price.toFixed(2)`-->数字转换成美元的形式；
* 10.使用Vue-resource进行数据交互方法：get、post、jsonp
