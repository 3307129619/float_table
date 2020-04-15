# layui浮动表格

#### 项目介绍
使用layui配合jquery完成


# 使用说明

* 讲解：
* elem -- 【#table_body】指定原始表格元素选择器（推荐id选择器）
* cols -- 【[{}]】 -- 二维数组
*      field -- 数据字段【必须】
*      name -- 第一栏显示名称【必须】
*      width -- 第一栏长度【不填默认为1】
*      default -- 数据默认值如果数据不存在或没有值，则填此值【不填默认为空】
* front -- 【[{}]】 -- 二维数组
*      name -- 头个数据的名称【必须】
*      width -- 头个数据的长度【不填默认为1】
* data -- 【[{}]】 -- 二维数组
*      跟随cols键中的field字段
* 需要的class
*      .t-hover-shadow
*      .t-hover-shadow:hover
*      .shadow-hover
*      .color_type
*      .color_game
*      .color_click
*      .color_click_black
* 需要的function
*      hover();
*      hoverhide();
* 实例：
<pre>
tableBaseStyle({
        elem:"#table_body"
        ,cols:[
            {field:"index",name:"字段1",width:3,default:"0"}
            ,{field:"oxx",name:"字段2",width:2}
			,{field:"oxs",name:"字段3",width:2}
			,{field:"oxss",name:"字段4",width:2}
        ]
        ,front:[
            {name:"头部 \/ 字段",width:2}
            ,{name:"头部1",width:2}
			,{name:"头部2",width:2}
			,{name:"头部3",width:2}
			,{name:"头部4",width:2}
        ]
        ,data:[
            {index:"数据index1",oxx:"数据oxx1",oxss:"数据oxss1",oxs:"数据oxs1"}
            ,{index:"数据index2",oxx:"数据oxx2",oxss:"数据oxss2",oxs:"数据oxs2"}
		    ,{index:"数据index3",oxx:"数据oxx3",oxss:"数据oxss3",oxs:"数据oxs3"}
			,{index:"数据index4",oxx:"数据oxx4",oxss:"数据oxss4",oxs:"数据oxs4"}
			,{index:"数据index5",oxx:"数据oxx5",oxss:"数据oxss5",oxs:"数据oxs5"}
        ]
    });
</pre>

