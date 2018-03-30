# Mobile-full-screen-sliding
a plugin depend on zepto for full-screen slide
## 使用：
``` 
$('#container').pageSwitch({
			selectors :{
				nodes: ".nodes" ,				//所有子页面的容器的class
				node : ".node" ,				//每子页面的class
				pagination:".pagination-box",	//分页按钮的容器的class
				active: ".active",				//分页按钮选中状态
			},
			index: 1,							//默认显示第几个子页
			pagination: true,					//是否生成分页按钮 true：是   false：否
			loop: true,							//是否循环滑动 true：是   false：否
			keyboard:true,						//是否支持键盘（上、左上滑，下、右下滑）true：是   false：否
			direction: "vertical",				//"vertical":竖向排列，"horizontal"：横向排列
			duration: 500,						//页面滑动动画时长
			ease: 'ease',						//页面滑动动画效果
			callback: ''						//动画完成后的回调函数
});
```
其中，#container是包含所有滑动子页面的元素id；

## 微信扫码运行