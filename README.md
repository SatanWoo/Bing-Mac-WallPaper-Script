# Bing-Mac-WallPaper-Script

#### 怎么使用这个脚本
使用这个脚本很简单的。只要把auto_bakcground_changer放到你的桌面上，
把com.ziqiwu.autochanger.plist 放入~/Library/LaunchAgents就可以了。
放入~/Library/LaunchAgents只是为了让这个脚本周期性执行。

最后重启下电脑就ok，或者在命令行里面输入launchctl load com.ziqiwu.autochanger.plist

#### 有几个参数需要调整的哦
1. com.ziqiwu.autochanger.plist 文件里面
<string>/Users/自己的用户名/Desktop/auto_background_changer.scpt</string> 
请把这个自己的用户名改成自己的电脑用户名哦

2. auto_background_changer 文件里面
set change interval of every desktop to 300.0
这个300是自动更新墙纸的时间，你可以自己调整哦，300秒就是5分钟。

3. auto_background_changer 文件里面
set wallpaperFolder to "wallpapers"
set wallpaperPath to "~/Desktop/" & wallpaperFolder & "/"
这个默认会生成一个文件夹在桌面上，把从bing的下载的壁纸放入里面。

#### NOTE:你可以单独双击打开auto_background_changer文件，然后点击按钮执行，
