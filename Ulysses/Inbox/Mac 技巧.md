## Mac 技巧

  
- Mac finder 窗口技巧
	   
Mac 所有窗口大小的调整 都会使用   第一次开启这个软件的动作来调整  
所以  第一次开软件 就把窗口调到位  下次就自动那个位置了
 
 
Shift + 移动 是对角等比的 调大小
Option+移动      四方向同时调整
 
 
Finder 窗口的  上面那条东西  可以自定义的  在那右击就可以
按住⌘  可以拖动位置
 
分栏显示下  option+   永久调整分割线  
 
Hua opt t  显示/隐藏   finder  工具栏
 
快速定位文件          finder里面  按下文件的 第一个字母  
 
Opt + 拖动是复制文件 


不开  airdrop     
 
备忘录 / imessage  也能同步照片  / icloude drive  
 
Handoff    在电脑办公 也不会漏接来电了    手机也不一定要带身边(只要在一个wifi下)
电脑和手机  网络浏览器 无缝链接     



- 关闭安全休眠 就不用经常休眠(读写ssd)
	   
	   
▲ 打開終端機。
接著輸入下列指令：
1.  sudo pmset -a hibernatemode 0 （關閉安全休眠，此時可能會要求你輸入密碼，就是開機密碼）
2.  cd /private/var/vm/（找出先前已保存的 sleepimage 檔案）
3.  sudo rm sleepimage （刪除先前已保存的 sleepimage 檔案）
完成。
恢復安全休眠模式
如果你關閉一段時間下來不喜歡，想要恢復它，當然也沒問題。要恢復「安全休眠」，指令如下：
1.  sudo pmset -a hibernatemode 3
2.  sudo rm /private/var/vm/sleepimage
完成。
 
Finder  开启图片边栏预览 更好.
 
 
设置偏好里  节能器 强制关机 ,  好习惯
 
Com + s  朗读所选
 
 
私密文件    新建.pkg文件夹  就当成安装程序了   双击打不开 只能显示包内容打开
dmg
 
 
mac os shell脚本hello world
 
 
 
1) 可以用shell
 
新建一个a.sh，内容：
# !/bin/bash
echo ‘hello world’
 
保存，运行如下命令：
chmod +x a.sh 
./a.sh
 
 
 文件保存到桌面   终端 先cd到桌面  就可以
 
 
手机发邮件 mac 睡眠: iphone 当遥控器
 
脚本编辑器
写入  tell application “System Events” to sleep  
保存 名字.scpt
 
去邮件的偏好设置 规则 
如果 
主题     是      Mac sleep 
执行  在finder中打开  - 把脚本复制进去     就能选那个脚本了 
 
试试吧 
 
1.  iphone邮件  清空 mac 垃圾桶
2.    脚本命令  写入
• tell application “Finder”
• empty the trash
• end tell
 
 
保存 到mail 的scpt文件夹里面    

Spotlight    快捷键  opt + 空格
 
Imessage  可以 请求控制对方屏幕!   远程帮助的时候用  .
  
Mac ⌘ +u 快速睡眠方法 

Automator  类型选服务   然后资源库列表下面找到 启动睡眠保护程序
拖到右边     上面的服务接收 选择 没有输入项目 输入名字(一键睡眠)   再储存
就能在系统设置 键盘下面 服务下面  找到一键睡眠了  加个快捷键就好了.
 
 
Spotlight:   计算器 /   能搜索各种 浏览器记录啊 -.- 

Mac 出问题  开机的时候  ⌘ + r    可以直接网络恢复全新系统 /或者 timemachine
 
   
- Keynote 技巧 
多张图片的话  调整成统一大小的办法
 先调整好一张图片   再opt+ 拖到就会复制出来另外一张一样大小的图片  更改里面的图片内容就好了.

 
Facebook  去广告浏览器插件        推荐  一般方法好像去不掉这个广告   Cleaner Facebook 
    
查看路径            文件直接拖到浏览器就能复制路径了 .

Siri  能投硬币了额











