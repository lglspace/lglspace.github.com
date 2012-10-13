#encoding: utf-8
---
layout: post
title: jquery操作checkbox,radio,select的简单总结
category: jquery
---
{% include JB/setup %}

jquery对多选按钮(checkbox),单选按钮(radio),下拉选择框(select)的操作经常会遗忘，故在此对常用操作做一个总结,以便在使用时能及时查询。 

<ul>
    
</ul>
- jquery操作checkbox
    1. 获取已选择的checkbox对象    `var jqobj = $("input[name=xxx]:checked");`
    2. 设定某按钮为选中状态    `$("#xxx").attr("check",true);`
    
- jquery操作radio
    1. 获取已选择的radio对象     `var jqobj = $("input[name=xxx]:checked");`
    2. 设定某按钮为选中状态    `$("#xxx").attr("check",true);`
    
- jquery操作select
    1. 获取已选择的下拉框的值   `var selval = $("select[name=xxx]").val();`
        注：此方法在Chrome中有问题最好采用$("option:selected").val()的方式来获取已经选择的值。
    2. 选择某下拉选项    `$("option").attr("select",true);`
    
    