#### 简介
<hr>

- 智能久坐提醒：利用深度学习神经网络训练的人脸检测模型，每天可自动监测久坐时间，提醒精度高
- 可自定义：可自定义久坐提醒时长、最小活动时长、监测时间段、提醒语
- 绿色：不更改注册表，不更改任何系统项，无需安装点击即用


#### 原理
<hr>

- 利用训练的深度学习神经网络模型实时检测人脸
- 在自定义的久坐提醒时长内一直检测到人脸的话，进行久坐提醒（使用屏幕遮罩，遮罩后只有站起来活动最小活动时长才会解除遮罩）
- 离开自定义最小活动时长后自动解除屏幕遮罩


#### 软件截图
<hr>


<table align ="center">
<caption align="bottom">软件截图</caption>
<tr><td><img src="https://github.com/lanbing510/SedentaryReminder/raw/master/screenshots/sedentary-reminder-1.png"  width="600px" /></td></tr>
</table>


<table align ="center">
<caption align="bottom">设置对话框截图</caption>
<tr><td><img src="https://github.com/lanbing510/SedentaryReminder/raw/master/screenshots/sedentary-reminder-2.png"  width="600px"/></td></tr>
</table>


<table align ="center">
<caption align="bottom">屏幕遮罩效果图</caption>
<tr><td><img src="https://github.com/lanbing510/SedentaryReminder/raw/master/screenshots/sedentary-reminder-3.jpg"  width="600px"/></td></tr>
</table>




#### 下载及问题反馈
<hr>

由于没有太多不同的计算机，本人只在四台不同计算机上进行了移植兼容性测试，有问题和反馈可在Issue留言。



#### 其他
<hr>

- 软件需要摄像头，平时聊天网络摄像头即可
- 考虑到多数人使用的是Windows操作系统，Mac笔记本好像有款类似软件，所以没有进行其他系统平台的编译
- 考虑到计算效率和实用性，并未加入识别网络
- 后期有时间在做坐姿检测，提醒规范坐姿
- 祝大家身体健康！