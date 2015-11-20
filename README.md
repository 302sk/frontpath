#前端开发
本提纲旨在为正准备学习前端开发的同事提供一条自学路径，方便学习者快速入门前端开发。本文涉及前端开发最基础的语言技能：HTML，Javascript，CSS。以及这些语言的综合使用。最后会提到一些常用框架，方便自学者深入学习。
##学习工具
####本地工具
1. 浏览器Chrome Firefox作为调试工具
2. 文本编辑器Sublime Notepad++等（**不使用Dreamweaver**）作为代码编辑器

####在线工具
1. [JSFiddle](http://jsfiddle.net/)在线直接调试HTML,CSS,Javascript代码,所写即所得
2. [Codecademy](https://www.codecademy.com/)在线交互式教学

####学习方法
1. 使用文本编辑器编辑代码,无论是HTML,CSS还是Javascript
2. 用浏览器预览结果
3. 重复1，2直到结果达到预期

##HTML
1. 什么是HTML
	* 什么是[HTML](http://www.w3school.com.cn/html/html_intro.asp)
	
	```
	HTML 是用来描述网页的一种语言。  
	
	1. HTML 指的是超文本标记语言 (Hyper Text Markup Language)
	2. HTML 不是一种编程语言，而是一种标记语言 (markup language)
	3. 标记语言是一套标记标签 (markup tag)
	4. HTML 使用标记标签来描述网页
	```
	
	* HTML[标签](http://www.w3school.com.cn/html/html_intro.asp)
	
	```
	HTML 标记标签通常被称为 HTML 标签 (HTML tag)
	
	1. HTML 标签是由尖括号包围的关键词，比如 <html>
	2. HTML 标签通常是成对出现的，比如 <b> 和 </b>
	3. 标签对中的第一个标签是开始标签，第二个标签是结束标签
	4. 开始和结束标签也被称为开放标签和闭合标签
	```
	
	* 什么是[网页](http://www.w3school.com.cn/html/html_intro.asp)
	
	```
	HTML 文档 = 网页
	1. HTML 文档描述网页
	2. HTML 文档包含 HTML 标签和纯文本
	3. HTML 文档也被称为网页
	```
	
	* 文档类型描述
		* 文档类型描述[关键字](http://www.w3school.com.cn/html/html_doctype.asp)
		* 常用[类型](http://www.w3school.com.cn/tags/tag_doctype.asp)
	
	* 基础代码练习[UNIT1:INTRODUCTION TO HTML](https://www.codecademy.com/learn/web)


2. HTML常用标签
	
	* HTML[所有标签](http://www.w3school.com.cn/tags/index.asp)
	* [速查手册](http://www.w3school.com.cn/html/html_quick.asp)
	* 基础标签[实例](http://www.w3school.com.cn/example/html_examples.asp)
	* 明确概念（[标签属性](http://www.w3school.com.cn/html/html_attributes.asp)，[标签元素](http://www.w3school.com.cn/html/html_elements.asp)）
	* [事件属性](http://www.w3school.com.cn/tags/html_ref_eventattributes.asp)
	* 常用标签使用练习[UINT2-UINT3](https://www.codecademy.com/learn/web)

3. HTML知识[测试](http://www.w3school.com.cn/quiz/quiz.asp?quiz=html)

##CSS
1. 什么是CSS

	```
	CSS 指层叠样式表 (Cascading Style Sheets)
	样式定义如何显示 HTML 元素
	样式通常存储在样式表中
	把样式添加到 HTML 4.0 中，是为了解决内容与表现分离的问题
	外部样式表可以极大提高工作效率
	外部样式表通常存储在 CSS 文件中
	多个样式定义可层叠为一
	```
	CSS使用效果[UNIT 4: INTRODUCTION TO CSS](https://www.codecademy.com/learn/web)
2. CSS语法
	* [基础语法](http://www.w3school.com.cn/css/css_syntax.asp)
	* CSS[应用方法](http://www.w3school.com.cn/css/css_howto.asp)

3. CSS选择器

	* [id选择器](http://www.w3school.com.cn/css/css_syntax_id_selector.asp)
	* [class选择器](http://www.w3school.com.cn/css/css_syntax_id_selector.asp)
	* [属性选择器](http://www.w3school.com.cn/css/css_syntax_id_selector.asp)
	* 学习CSS选择器的[小游戏](http://flukeout.github.io/)(包含进阶语法)

4. CSS常用样式

	样式，使用键值对方式存储（属性:值）
	* 一些常用样式的应用[实例](http://www.w3school.com.cn/example/csse_examples.asp)
	* CSS样式代码练习[(UINT4-UINT5)](https://www.codecademy.com/learn/web)

5. CSS框模型
	
	* 了解[HTML元素](http://www.w3school.com.cn/html/html_elements.asp)的[框模型](http://www.w3school.com.cn/css/css_boxmodel.asp)
	* 框模型常用样式练习[(UNIT6)](https://www.codecademy.com/learn/web)
	* Chrome浏览器调试模式[查看框模型](http://immmmm.com/chrome-review-elements-learning-tool-for-div-css.html)
	
6. CSS定位HTML元素
	* HTML元素[一切皆为框](http://www.w3school.com.cn/css/css_positioning.asp)
	* 相对定位
	* 绝对定位
	* 固定定位
	* CSS定位练习[(UINT6)](https://www.codecademy.com/learn/web)
	
7. CSS参考[手册](http://www.w3school.com.cn/cssref/index.asp)

##HTML+CSS综合练习
CSS离开HTML是没有意义的，HTML结合CSS的样式描述才能呈现美妙的网页内容。
`此处需要扩展`  

1. Codecademy[在线练习](https://www.codecademy.com/en/skills/make-a-website)
2. 

##Javascript
在这里，假设所有学习者都有至少一门编程语言的基础，使用下面列出的在线课程，迅速掌握Javascript基础语法和基本编程思想

1. 基础语法

	* 基础语法[简介和简单实例](http://www.w3school.com.cn/js/index.asp)(2Days)
	* 基础语法[在线练习](https://www.codecademy.com/learn/javascript)(1Week)  
	
2. Javascript操作HTML DOM对象
	* 什么是[HTML DOM](http://www.w3school.com.cn/js/js_htmldom.asp)
	* Javascript[操作HTML元素](http://www.w3school.com.cn/js/js_htmldom_html.asp)
	* Javascript[操作CSS样式](http://www.w3school.com.cn/js/js_htmldom_css.asp)
	* Javascript[事件处理](http://www.w3school.com.cn/js/js_htmldom_events.asp)
	* Javascript[操作DOM节点](http://www.w3school.com.cn/js/js_htmldom_elements.asp)  

3. Javascript简单任务练习

	* 页面加载后10s隐藏所有`<h1>`标签
	* 点击`<p>`文档段落改变文字颜色
	* 点击`添加DOM`按钮后，向页面插入一张图片
	* 鼠标在图片上悬停时，更换图片

4. 学习Javascript常用库--Jquery
	* Jquery[简介](http://www.w3school.com.cn/jquery/index.asp)
	* Jquery[代码练习](https://www.codecademy.com/learn/jquery)
	* 用Jquery实现上一步中的简单任务

5. 在线交互式学习Javascript资源

	* 从HelloWorld——与浏览器交互[（计蒜客）](http://www.jisuanke.com/course/6)

##DHTML
有了以上三门语言的基础，就可以实现动态页面了,以下是一些可以利用的在线练习环境。此处也可以给出一个页面设计图（及其交互动作说明）让学习者实现
	
1. 实现[交互式页面](https://www.codecademy.com/en/skills/make-an-interactive-website)


##前端与后台交互基础
1. 了解HTTP协议中的方法POST和GET以及[它们的区别](http://www.w3school.com.cn/tags/html_ref_httpmethods.asp)
2. Chrome分析HTTP请求的[方法](http://www.51testing.com/html/22/100922-832779.html)以及更多Chrome DevTool[技巧](http://tutorialzine.com/2015/03/15-must-know-chrome-devtools-tips-tricks/)
3. HTML表单提交[过程解析](http://harttle.com/2015/08/03/form-submit.html)
4. Ajax[基础操作和后台简单接口](http://www.cnblogs.com/fish-li/archive/2011/07/17/2108884.html)
5. 简单后台server log展示