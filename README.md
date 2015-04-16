# touchSlider
调用参数说明：
- 第一个为外层容器选择器（必选）
- 第二个为可选项，json中的各项也都是可选项，
	- timeout：每个多少毫秒动一下（默认4000）；
	- scale：图片宽高比（防止拉伸变形，默认480/140,你可以根据你的图片宽高比自行设置）；
	- speed：滑一下用时（默认400），auto：是否自动播放，默认是true。


	`touchSlider('#box',{timeout:2000,scale:480/150,speed:500,auto:false});`