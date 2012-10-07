---
layout: post
category : 前台技术
tags : [jquery,checkbox,select,radio]
---
{% include JB/setup %}

jquery对多选按钮(checkbox),单选按钮(radio),下拉选择框(select)的操作在使用时经常会遗忘，故在此对常用操作做一个总结。 

### jquery操作checkbox

#### 1.对已选中按钮的获取

	var jqobj = $("input[name=xxx]:checked");

### jquery操作radio

#### 1.对已选中按钮的获取

	var jqobj = $("input[name=xxx]:checked");
	
### jquery操作select

#### 1.获取选中项的值

	var selval = $("select[name=xxx]").val();
	
	注：此方法在Chrome中有问题最好采用$("option:selected").val()的方式来获取已经选择的值。