## MIUI第三方主题

## 说明
Miui14第三方主题，测试机型小米11。需要root破解系统主题导入，请自行root，按照magisk和LSPosed框架，再安装Muiu主题破解。
欢迎大家提交代码完善主题。

### 文件构造说明
1. boots                   开机logo
2. clock_2x4 时钟
3. com.android.contacts   联系人界面 
4. com.android.mms        短信界面
5. com.android.settings   设置界面
6. com.android.systemui   系统UI、下拉界面
7. com.android.updater    系统更新界面
8. com.android.providers.downloads.ui 系统下载界面
9. com.miui.home          桌面
10. com.miui.notification  通知界面
11. framework-miui-res    资源
12. framework-res         资源
13. icons                 图标
14. lockscreen            锁屏
15. miui.systemui.plugin  下面界面的图标
16. preview               预览图片
17. wallpaper             壁纸
18. com.miui.gallery      相册页面
19. com.android.thememanager 主题壁纸界面
20. aod                     息屏
21. videowallpaper         动态壁纸
22. com.miui.securitycenter 安全中心页面
23. com.android.calendar    日历
24. com.android.email       邮箱
25. com.android.phone       SIM界面
26. com.miui.cloudservice  设置-云服务
27. com.miui.packageinstaller  安装包界面
28. com.xiaomi.account      设置-账号
29. com.xiaomi.bluetooth    蓝牙
30. com.xiaomi.market       应用商城

## 
1. 主题部分模块可能没有适配好，夜间模式没有适配，一般就是制作一张带有暗色的图片（添加50%透明的的黑色遮罩）.

###
1. 界面图片显示不正确时，需要设置正确的分辨率和手拉.9图片，放在图片拉伸变形。系统一般图片先适配好宽度，再向高度拉伸图片。
2. 动态壁纸放在videowallpaper的文件夹里面，需要先主题下载动态壁纸，再用MT管理器找到data/caom.aodroid.thememanager/files/MIUI/.videowallpaper,替换文件即可。
3. 主题底包素材来源于互联网。
4. 开机动画压缩方式选择store。


