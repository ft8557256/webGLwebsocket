﻿webGL,websocket,nodeJS做的3D的多人在线游戏
===

最左侧是聊天系统，进入时默认缩放在左下角，聊天系统支持广播和私聊两种方式，要先输入昵称才能进入聊天室，点击右侧昵称切换到私聊，点击右侧牛头换到广播，支持键盘操作。
server文件夹里面的server.js是静态文件服务器，要注意路径问题，start.js是websocket服务器，注意端口号。常规方式启动就好了，index.html里面的websocket服务器地址修改一下

所有的键盘事件
	上键，向前走
	w键，向前走
	下键，向后走
	s键，向后走
	左键，向左转圈
	a键，向左转圈
	右键，向右转圈
	d键，向右转圈
	空格键，跳跃
	y键，装死
	q键，攻击
	ctrl键，蹲下
	r键，换枪
	g键，蹲下攻击
	f键，蹲下痛苦
	h键，蹲下装死
	t键，嘲讽
	c键，滑动
	u键，痛苦
	v键，wave摇动
	x键，指点
	0--9换枪
	 `键  系统菜单
	聊天时 ctrl+enter 发送聊天消息
	
	所有的动作要按住键盘才能正常进行，松开键盘默认取消该动作。

## License

使用MIT协议发布。