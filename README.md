# -
联网坦克大战游戏，可以在网站上查看排行榜
								可联网看排名的坦克游戏系统说明文档

1．系统概述
  本系统包含一个简单的坦克游戏程序和一个轻量级排行榜网站，游戏用java语言编写，在jdk环境下运行。排行榜网站，可以将游戏成绩展示给用户，包含html、css、js、php源码，网络数据库和几百张#图片。
  注册用户，开始游戏
游戏开始时，用户通过键盘操纵坦克移动，转弯和射击，与敌人坦克进行交战。存盘退出可以将成绩上传到网站上
2．功能介绍
 1.1开始游戏
	本程序运行的主函数类是tankGame类，将此类编译后直接运行，就会出现如下界面：
<img width="416" alt="image" src="https://user-images.githubusercontent.com/100510808/167290775-dcf7701e-6467-4d21-86be-712a349d2673.png">

	上图显示的界面为程序的主界面。用户可以通过点击上面的菜单项开始进行游戏或设置游戏规则。点击游戏菜单中的“开始新游戏”菜单项，就可以正式开始游戏，其界面如下显示：
<img width="125" alt="image" src="https://user-images.githubusercontent.com/100510808/167290842-ce0d1f93-6456-4208-8bb5-90a41ebe82ea.png">

	在上图显示的界面中，在下方的橘黄色坦克是用户可以操纵的坦克。上面的10辆浅蓝色坦克是敌人坦克。
 操作：
  控制坦克移动：键盘的W/S/A/D （英文）或者上下左右方向键
  坦克发子弹：J键（英文）和空格键
 1.2 分数统计
  当游戏打爆一个敌方坦克后，右上方的总成绩就会加一，并且上传到排行榜网站，如下图所示：
<img width="416" alt="image" src="https://user-images.githubusercontent.com/100510808/167290815-4c8ee76d-55b1-412c-802a-65940cc2408c.png">
<img width="415" alt="image" src="https://user-images.githubusercontent.com/100510808/167290850-28756f28-8c15-4959-a292-fab4fe958f37.png">

1.3游戏设置
 1.存盘退出
<img width="416" alt="image" src="https://user-images.githubusercontent.com/100510808/167290863-b9027cfe-7579-4577-9576-17f9b4456d32.png">

 如果你不想玩了可以选择存盘退出，可以记录你的成绩和敌方坦克的位置坐标，保证点击继续上局游戏时可以恢复如初。点击存盘退出后，“您的总成绩”和敌方坦克坐标会保存到本地myRecording.txt文档中，并且“您的总成绩”会同步上传到云数据库上。
2.继续上局
          游戏会自动读取myRecording.txt文档中的游戏记录，并继续上次游戏

3．网站介绍
网址：http://124.221.217.3/
1.游戏排行榜是实时动态更新的，“存盘退出”后就能看到您的成绩，但你的设备需要联网，排行榜以最边的成绩动态排名
<img width="415" alt="image" src="https://user-images.githubusercontent.com/100510808/167290882-3053ada3-a859-4a4b-ac5e-ba550d8841c4.png">

4．本系统项目还没有全部完成
存在的问题：
  1.用户注册登录模块还没做
  2.坦克游戏界面的“树（墙）”还没完成
  3.游戏没有闯关模式
  4.游戏主界面的右上角的我方和敌方坦克数据实时更新，跟我方坦克的生命值模块还没完成
目前坦克大战游戏系统项目还没完成，大家敬请期待
