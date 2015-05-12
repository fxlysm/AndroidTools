# AndroidTools

AndroidDevTools简介
Android Dev Tools官网地址：www.androiddevtools.cn
收集整理Android开发所需的Android SDK、开发中用到的工具、Android开发教程、Android设计规范，免费的设计素材等。
欢迎大家推荐自己在Android开发过程中用的好用的工具、学习开发教程、用到设计素材，欢迎Star、Fork 。
如果你对翻译英文的Android开发技术文章感兴趣，欢迎Start和ForkAndroidWeekly中国文章翻译项目
Android Tools
Android SDK在线更新镜像服务器

中国科学院开源协会镜像站地址:

IPV4/IPV6: http://mirrors.opencas.cn 端口：80

IPV4/IPV6: http://mirrors.opencas.org 端口：80

IPV4/IPV6: http://mirrors.opencas.ac.cn 端口：80

上海GDG镜像服务器地址:

http://sdk.gdgshanghai.com 端口：8000

北京化工大学镜像服务器地址:

IPv4: http://ubuntu.buct.edu.cn/ 端口：80

IPv4: http://ubuntu.buct.cn/ 端口：80

IPv6: http://ubuntu.buct6.edu.cn/ 端口：80

大连东软信息学院镜像服务器地址:

http://mirrors.neusoft.edu.cn 端口：80

使用方法：

启动 Android SDK Manager ，打开主界面，依次选择『Tools』、『Options...』，弹出『Android SDK Manager - Settings』窗口；

在『Android SDK Manager - Settings』窗口中，在『HTTP Proxy Server」和「HTTP Proxy Port』输入框内填入上面镜像服务器地址(不包含http://，如下图)和端口，并且选中『Force https://... sources to be fetched using http://...』复选框。设置完成后单击『Close』按钮关闭『Android SDK Manager - Settings』窗口返回到主界面；

依次选择『Packages』、『Reload』。

SDK Manager Proxy Settings
Android Studio

版本号	Windows	Mac OSX	Linux
1.2 正式版	下载	下载	下载
1.2 RC3	下载	下载	下载
1.2 RC2	下载	下载	下载
1.2 RC	下载	下载	下载
1.2 Beta3	下载	下载	下载
1.2 Beta2	下载	下载	下载
1.2 Beta	下载	下载	下载
1.2 Preview 4	下载	下载	下载
1.2 Preview 3	下载	下载	下载
1.2 Preview 2	下载	下载	下载
1.2 Preview 1	下载	下载	下载
1.1 正式版	下载	下载	下载
1.1 RC1	下载	下载	下载
1.1 Beta4	下载	下载	下载
1.1 Beta3	下载	下载	下载
1.1 Beta2	下载	下载	下载
1.1 Beta	下载	下载	下载
1.1 Preview 2	下载	下载	下载
1.1 Preview 1	下载	下载	下载
1.0.2	下载	下载	下载
1.0.1	下载	下载	下载
1.0正式版	下载	下载	下载
1.0 RC4	下载	下载	下载
1.0 RC2	下载	下载	下载
1.0 RC1	下载	下载	下载
0.9.3	下载	下载	下载
0.9.2	下载	下载	下载
0.9.1	下载	下载	下载
0.9.0	下载	下载	下载
0.8.14	下载	下载	下载
0.8.13	下载	下载	下载
0.8.12	下载	下载	下载
0.8.11	下载	下载	下载
0.8.10	下载	下载	下载
0.8.9	下载	下载	下载
0.8.8	下载	下载	下载
0.8.7	下载	下载	下载
0.8.6	下载	下载	下载
0.8.5	下载	下载	下载
0.8.4	下载	下载	下载
0.8.3	下载	下载	下载
0.8.2	下载	下载	下载
0.8.1	下载	下载	下载
0.8 0	下载	下载	下载
0.6.1	下载	下载	下载
0.6.0	下载	下载	下载
0.5.9	下载	下载	下载
0.5.8	下载	下载	下载
SDK Tools

版本号	Windows	Mac OSX	Linux
sdk-tools-r24.1.2	installer_r24.1.2-windows.exe android-sdk_r24.1.2-windows.zip	android-sdk_r24.1.2-macosx.zip	android-sdk_r24.1.2-linux.tgz
sdk-tools-r24.0.2	installer_r24.0.2-windows.exe android-sdk_r24.0.2-windows.zip	android-sdk_r24.0.2-macosx.zip	android-sdk_r24.0.2-linux.tgz
sdk-tools-r24.0.1	installer_r24.0.1-windows.exe android-sdk_r24.0.1-windows.zip	android-sdk_r24.0.1-macosx.zip	android-sdk_r24.0.1-linux.tgz
sdk-tools-r24	installer_r24-windows.exe android-sdk_r24-windows.zip	android-sdk_r24-macosx.zip	android-sdk_r24-linux.tgz
sdk-tools-r23.0.5	android-sdk_r23.0.5-windows(非官方版).zip	android-sdk_r23.0.5-macosx(非官方版).zip	
sdk-tools-r23.0.2	installer_r23.0.2-windows.exe android-sdk_r23.0.2-windows.zip	android-sdk_r23.0.2-macosx.zip	android-sdk_r23.0.2-linux.tgz
sdk-tools-r23	installer_r23-windows.exe android-sdk_r23-windows.zip	android-sdk_r23-macosx.zip	android-sdk_r23-linux.tgz
备注： 非官方版 是在 23.0.2 的基础上进行了在线更新包含了 Android 5.0 SDK ，SDK Tools 23.0.5 、Build Tools 21.0.1 、Support Library 21等。
SDK Platform-Tools

这是 adb, fastboot 等工具包。把解压出来的 platform-tools 文件夹放在 android sdk 根目录下，并把 adb所在的目录添加到系统 PATH 路径里，即可在命令行里直接访问了 adb, fastboot 等工具。

版本号	Windows	Mac OSX	Linux
platform-tools-r22	platform-tools_r22-windows.zip	platform-tools_r22-mac.zip	platform-tools_r22-linux.zip
platform-tools-r21	platform-tools_r21-windows.zip	platform-tools_r21-mac.zip	platform-tools_r21-linux.zip
platform-tools-r20	platform-tools_r20-windows.zip	platform-tools_r20-mac.zip	platform-tools_r20-linux.zip
Build-Tools

这是Android开发所需的Build-Tools，下载并解压后，将解压出的整个文件夹复制或者移动到 your sdk 路径/build-tools 文件夹即可。

版本号	Windows	Mac OSX	Linux
21.1.2	下载	下载	下载
21.1.2	下载	下载	
21.1.1	下载	下载	
21.1.0	下载	下载	
21.0.2	下载	下载	
21.0.1	下载	下载	
21.0.0	下载	下载	
20.0.0		下载	
19.1.0	下载	下载	
19.0.3	下载	下载	
19.0.2	下载	下载	
19.0.1	下载	下载	
19.0.0	下载	下载	
SDK

这是Android开发所需的sdk，下载并解压后，将解压出的整个文件夹复制或者移动到 your sdk 路径/platforms文件夹，然后打开SDK Manager，打开 Tools(工具)菜单选择 Options(选项)菜单项打开Android SDK Manager Setting对话框，点击 Clear Cache(清除缓存)按钮，然后重启Eclipse(或Android Studio)和SDK Manager。

系统版本号	Windows	Mac OSX	Linux
android 5.0	下载	下载	下载
android L Rev3	下载	下载	下载
android L	下载	下载	下载
android 4.4W	下载	下载	下载
android 4.4.2	下载	下载	下载
android 4.3	下载	下载	下载
android 4.2.2	下载	下载	下载
android 4.1.2	下载	下载	下载
android 4.0.3	下载	下载	下载
android 4.0	下载	下载	下载
android 3.2	下载	下载	下载
android 3.1	下载	下载	下载
android 3.0	下载	下载	下载
android 2.3.3	下载	下载	下载
android 2.2	下载	下载	下载
SDK System images

这是在创建模拟器时需要的system image，也就是在创建模拟器时 CPU/ABI项需要选择的，下载并解压后，将解压出的整个文件夹复制或者移动到 your sdk 路径/system-images文件夹下即可， 如果没有 system-images目录就先创建此文件夹，然后打开SDK Manager，打开 Tools(工具)菜单选择 Options(选项)菜单项打开Android SDK Manager Setting对话框，点击 Clear Cache(清除缓存)按钮，然后重启Eclipse(或Android Studio)和SDK Manager。

系统版本号	Windows	Mac OSX	Linux
android 5.0	下载	下载	下载
android L	下载	下载	下载
android 4.4W	下载	下载	下载
android 4.4.2	下载	下载	下载
android 4.3	下载	下载	下载
android 4.2.2	下载	下载	下载
android 4.1.2	下载	下载	下载
android 4.0.3	下载	下载	下载
android 4.0	下载	下载	下载
GoogleMap APIs SDK

这是GoogleMap APIs SDK，下载并解压后，将解压出的整个文件夹复制或者移动到 your sdk 路径/add-ons文件夹下，然后打开SDK Manager，打开 Tools(工具)菜单选择 Options(选项)菜单项打开Android SDK Manager Setting对话框，点击 Clear Cache(清除缓存)按钮，然后重启Eclipse(或Android Studio)和SDK Manager。

系统版本号	Windows	Mac OSX	Linux
android 4.4.2	下载ARM版 下载x86版	下载ARM版 下载x86版	下载ARM版 下载x86版
android 4.3	下载	下载	下载
android 4.2.2	下载	下载	下载
android 4.1.2	下载	下载	下载
android 4.0.3	下载	下载	下载
android 4.0	下载	下载	下载
android 3.2	下载	下载	下载
android 3.1	下载	下载	下载
android 3.0	下载	下载	下载
android 2.3.3	下载	下载	下载
android 2.2	下载	下载	下载
Google Glass SDK

这是GDK，下载并解压后，将解压出的整个文件夹复制或者移动到 your sdk 路径/add-ons文件夹下，然后打开SDK Manager，打开 Tools(工具)菜单选择 Options(选项)菜单项打开Android SDK Manager Setting对话框，点击 Clear Cache(清除缓存)按钮，然后重启Eclipse(或Android Studio)和SDK Manager。

系统版本	Windows	Mac OSX	Linux
android 4.4.2	下载	下载	下载
android 4.0.3		下载	
Google TV Addon

这是Google TV Addon，下载并解压后，将解压出的整个文件夹复制或者移动到 your sdk 路径/add-ons文件夹，然后打开SDK Manager，打开 Tools(工具)菜单选择 Options(选项)菜单项打开Android SDK Manager Setting对话框，点击 Clear Cache(清除缓存)按钮，然后重启Eclipse(或Android Studio)和SDK Manager。

系统版本	Windows	Mac OSX	Linux
android 3.2	下载	下载	下载
Android Framework Source Code

这是Android Framework Source Code，下载并解压后，将解压出的整个文件夹复制或者移动到 your sdk 路径/sources文件夹下，然后重启Eclipse(或Android Studio)，这样当你在Eclipse里面按住 Ctrl键点击某个系统类时就可以打开该类的源码文件查看源码了。

系统版本
android 5.0
android 4.4W
android 4.4.2
android 4.3
android 4.2.2
android 4.1.2
android 4.0.3
android 4.0
android 3.0
android 2.3.3
android 2.2
Android SDK Extras

包含 Android Support Library、 Google Cloud Messaging for Android Library、 Google Play services、 Google Play services for fit preview、 Google Play services for Froyo、 Google Play APK Expansion Library、 Google Play Billing Library、 Google Play Licensing Library等，下载解压后将解压出的整个文件夹复制或者移动到 your sdk根目录下下，如果已经存在 extras文件夹就替换掉。

版本号
21.0.3
21.0.2
21
20
Support Library

包含supportive、v7和v13，下载解压后将解压出的整个文件夹复制或者移动到 your sdk 路径/extras下，然后打开SDK Manager，打开 Tools(工具)菜单选择 Options(选项)菜单项打开Android SDK Manager Setting对话框，点击 Clear Cache(清除缓存)按钮，然后重启Eclipse(或Android Studio)和SDK Manager。

版本号
21.0.3
21.0.2
21
20
SDK Samples

这是Android SDK自带的示例代码，下载并解压后，将解压出的整个文件夹复制或者移动到 your sdk 路径/samples文件夹下，然后重启Eclipse(或Android Studio)。 。

系统版本
android 21
android L
android 4.4W
android 4.4.2
android 4.3
android 4.2.2
android 4.1.2
android 4.0.3
android 4.0
android 3.2
android 3.1
android 3.0
android 2.3.3
android 2.2
NDK

C/C++开发Android应用工具包,Linux/Mac OS X 下NDK r10c的安装方法请戳[这里](https://github.com/inferjay/AndroidDevTools/wiki/Installing-the-NDK-On-Linux-and-Mac-OS-X-(Darwin)

版本号	Windows	Mac OSX	Linux
ndk-r10d	32位 64位	32位 64位	32位 64位
ndk-r10c	32位 64位	32位 64位	32位 64位
ndk64-r10	32位 64位	32位 64位	32位 64位
ndk32-r10	32位 64位	32位 64位	32位 64位
ndk-r9d	32位 64位	32位 64位	32位 64位
Additional Download (32-, 64-bit)	Package
r10 STL debug info	android-ndk-r10-cxx-stl-libs-with-debug-info.zip
r9 STL debug info	android-ndk-r9-cxx-stl-libs-with-debug-info.zip
Android L Preview System Image

这个是Android L Preview系统的刷机镜像。

设备	下载
Nexus 5 (GSM/LTE) "hammerhead"	hammerhead-lpv79-preview-ac1d8a8e.tgz
Nexus 7 (Wifi) "razor"	razor-lpv79-preview-d0ddf8ce.tgz
JDK

版本号	Windows	Mac OSX	Linux
1.8 u5	32位 64位	64位	32位 64位
1.7 u60	32位 64位	64位	32位 64位
1.6 u45	32位 64位	64位	32位 64位
ADT Bundle

ADT Bundle包含了Eclipse、ADT插件和SDK Tools，是已经集成好的IDE，只需安装好Jdk即可开始开发，推荐初学者下载ADT Bundle，不用再折腾开发环境。

版本号	Windows	Mac OSX	Linux
23.0.2	32位 64位	64位	32位 64位
23.0.0	32位 64位	64位	32位 64位
ADT Plugin

离线安装ADT插件请戳 项目wiki

版本号
ADT-23.0.6
ADT-23.0.4
ADT-23.0.3
ADT-23.0.2
ADT-23.0.0
ADT-22.6.3
AdT-22.6.1
Gradle

版本号
gradle-2.2.1-all.zip
gradle-2.2-all.zip
gradle-2.1-all.zip
gradle-2.0-all.zip
gradle-1.12-all.zip
gradle-1.11-all.zip
gradle-1.10-all.zip
gradle-1.9-all.zip
gradle-1.8-all.zip
gradle-1.7-all.zip
Gradle Dependencies Configuration Generator

Gradle, please

版本控制工具

Git

版本号	Windows	Mac OSX	Linux
Git-2.0.1		下载	下载
Git-1.9.4	下载		下载
Git-1.8.5.2	下载	下载	下载
SVN Plugin For Eclipse

版本号
1.10.5
1.8.22
1.6.18
Apk反编译工具

名称	简介	下载地址	使用教程
JEB Android Decompiler		下载	
Virtuous Ten Studio		下载	
Apk文件修改工具Root Tools		下载	
Dex文件反编译工具Dedexer		下载	
APK+Dex文件反编译及回编译工具		下载	
android-apktool		下载	
Onekey Decompile Apk]		下载	
Baksmali		下载	
Smali		下载	
AXMLPrinter2		下载	
JAD Java Decompiler		下载	
JD-GUI Decompiler		下载	
XJad V2.2		下载	
Android APK Decompiler	在线反编译工具	下载	
SmaliViewer	
是一款免费的APK分析软件，无论从分析的深

度还是广度来看，都是一款能够满足用户需求

的产品，使您在APK分析的过程中，更加得心应手。

下载	使用指南
Android逆向助手	
Android逆向助手是一功能强大的逆向辅助软件。

该软件可以帮助用户来进行apk反编译打包签名；

dex/jar互转替换提取修复；so反编译；

xml、txt加密；字符串编码等等，操作简单，

只需要直接将文件拖放到源和目标文件。

下载	使用指南
Android Killer	集Apk反编译、Apk打包、Apk签名，编码互转，
ADB通信（应用安装-卸载-运行-设备文件管理）等特色
功能于一 身，支持logcat日志输出，语法高亮，
基于关键字（支持单行代码或多行代码段）项目内搜索，
可自定义外部工具；吸收融汇多种工具功能与特点，
打造一站 式逆向工具操作体验，大大简化了用户在
安卓应用/游戏修改过程中的各类繁琐工作。	下载1
下载2	使用指南
安全工具

名称	下载地址	使用教程
APKfuscator	下载	
ApkAnalyser	下载	
AppXplore	下载	
Android analysis framework	下载	
Androguard	下载	
Droidbox	下载	
dsploit	下载	
Androwarn	下载	
Anubis	下载	
Drozer	下载	
VirusTotal	下载	
GDB for Android	下载	
VisualGDB	下载	
搜索工具

名称	简介	下载地址	使用教程
Structural Java Exception Search	Java异常搜索工具	下载	
Debug调试工具

名称	简介	下载地址	使用教程
Stetho	Stetho 是Facebook推出的Android 调试平台，基于 
Chrome Developer Tools ，调试网络请求方面特别方便。	下载	教程
Augmented Traffic Control	Facebook宣布开源移动网络测试工具ATC，该工具支持利用
Wi-Fi网络模拟2G、2.5G、3G以及LTE 4G移动网络
环境，让测试工程师们能够快速对智能手机和App在
不同国家地区和应用环境下的性能表现进行测试。	下载	
Api测试工具

名称	简介	下载地址	使用教程
bat	一个用Go写的命令行API测试利器，支持文件下载，
文件上传，支持Linux的pipe方式，总之就是炫酷。	下载	教程
Eclipse/Android Studio/IDEA插件

Eclipse插件

名称	下载地址	使用教程
SVN	下载	
Genymobile模拟器	下载	
Memory-Analyzer-Tools	下载	
Droidinspector	下载	
SQLiteManager	下载	
Color Theme	下载	
RoboVM	下载	
Newrelic	下载	
Android Studio/IDEA插件

名称	下载地址	使用教程
Android Resource Resizer Plugin	下载	
Gradle Dependencies Helper Plugin	下载	
Android Parcelable code generation Plugin	下载	
Android Holo Colors IDEA Plugin	下载	
Android Toolbox Plugin	下载	
Android Gradle Sign Plugin	下载	
Android Permissions Usage Plugin	下载	
Android Helper Plugin	下载	
Android Studio Prettify Plugin	下载	
IDEA ADB Plugin	下载	
Otto Intellij Plugin	下载	
Dagger intellij Plugin	下载	
Gradle Gui Plugin	下载	
Android Studio Unit Test Plugin	下载	
Android Layout ID Converter Plugin	下载	
IDEA protobuf Plugin	下载	
Simple Team Code Reviewer Plugin	下载	
Android XML Plugin	下载	
ADF Plugin	下载	
Java2smali Plugin	下载	
IDEA gitignore Plugin	下载	
IDEA Background Image Plugin	下载	
IDEA Maven Plugin	下载	
Gradle GooglePlay Publisher Plugin	下载	
Drawable Selectors Generates Plugin	下载	
Android Drawable Importer	下载	
Android资源/Themes/Style生成工具

名称	简介	下载地址	使用教程
Android Asset Studio		下载	
Android Drawable Factory		下载	
Android Action Bar Style Generator		下载	
Android Holo Colors Generator		下载	
Android Simple Nine-patch Generator		下载	
Android Device Frame Generator		下载	
Android资源分析工具

名称	简介	下载地址	使用教程
Android Assets Viewer		下载	
Android Layout Parser工具

名称	简介	下载地址	使用教程
Android Layout Binder		下载	
Android Content Provider代码生成工具

名称	简介	下载地址	使用教程
Content Provider Code Generator		下载	
Android Fragment Code Generator代码生成工具

名称	简介	下载地址	使用教程
Android Fragment Code Generator		下载	
代码生成工具

名称	简介	下载地址	使用教程
Android KickstartR	AndroidKickstartR帮助您快速创建 
Android应用程序并使用最流行的库进行配置。 
它创建和配置你的项目给你。只专注于代码!	下载	
Android Button Maker	Android Button Maker是一个在线生成Android应用按钮代码的工具。 
Android的API提供可绘制资源，其中的XML文件定义的几何形状，包括颜色，边框和梯度。 
这些按钮是在shape drawable XML代码基础上产生的相比通常的PNG按钮加载速度更快。 
您可以在设置面板中自定义按钮的属性和获得源代码。	下载	
DroidDraw		下载	
Android SVG to VectorDrawable	一个可以将SVG图片转换为Vector Drawable xml文件的在线工具。	下载	
Android Native开发工具

名称	简介	下载地址	使用教程
Android++		下载	
Android测试工具

名称	简介	下载地址	使用教程
Appurify		下载	
Monkey		下载	
Testin		下载	
Spoon		下载	
Little Eye		下载	
易测云		下载	
Emmagee		下载	
Apk View Tracer		下载	
APT	APT是一个Android平台高效性能测试组件， 
提供丰富实用的功能，适用于开发自测、 
定位性能瓶颈； 
测试人员完成性能基准测试、竞品对比测试。	下载	教程
GT	GT（随身调）是APP的随身调测平台，它是直接运行在手机上的“集成调测环境”(IDTE, Integrated Debug&Test Environment)。	下载	教程
Stetho	Stetho 是Facebook推出的Android 调试平台，基于 Chrome Developer Tools ，调试网络请求方面特别方便。	下载	教程
Android多渠道打包工具

名称	简介	下载地址	使用教程
Umeng多渠道打包工具		下载	
AppTools具		下载	
package_tool		下载	
RyApkTool		下载	
Android Bug日志收集工具

名称	简介	下载地址	使用教程
Crashlytics		下载	
ACRA		下载	
ChkBugReport		下载	
Log Collector		下载	
Android Crash Catcher		下载	
其他语言开发Android应用工具

名称	简介	下载地址	使用教程
Xamarin		下载	
Basic4android		下载	
Scripting Layer		下载	
Ruby Rhodes	移动设备上的Ruby	下载	
PHP for Android		下载	
Codename One		下载	
Touchqode		下载	
App Inventor		下载	
传感器模拟工具

名称	简介	下载地址	使用教程
Sensor Simulator	独立的Java应用程序，它模拟传感器 
的数据并将它们传送到Android模拟器。	下载	
Android串口开发工具

名称	简介	下载地址	使用教程
Android Serialport Api		下载	
图片尺寸处理工具

名称	简介	下载地址	使用教程
9-Patch Resizer		下载	
图片压缩工具

名称	简介	下载地址	使用教程
OptiPNG		下载	
Pngcrush		下载	
ImageOptim		下载	
资源清理工具

名称	简介	下载地址	使用教程
Android Lint		下载	
Android Resource Cleaner		下载	
Android Unused Resources		下载	
Android Resource Remover		下载	
px和dp转换/计算工具

名称	简介	下载地址	使用教程
Android dp px Calculator		下载	
dp px converter		下载	
pixelcalc		下载	
androidpixels		下载	
android dpi calculator		下载	
DPI Calculator		下载	
Java To iOS

名称	简介	下载地址	使用教程
j2Objc		下载	
RoboVM		下载	
JSON/XML转换为POJO Class工具

名称	简介	下载地址	使用教程
jsonschema2pojo		下载	
Convert XML or JSON to Java Pojo		下载	
Java DAO Generate工具

名称	简介	下载地址	使用教程
Generate Java DAO for relational data table		下载	
Chrome插件

Android插件

名称	简介	下载地址	使用教程
Android SDK Search		下载	
Android Resource Navigator		下载	
ADB Plugin for remote 
debugging Chrome on Android		下载	
Mobile/RWD Tester		下载	
ExtensionAndroid SDK Samples Search		下载	
Android Developer Improvements		下载	
Android downloader		下载	
JSON/XML格式化插件

名称	简介	下载地址	使用教程
JSONView		下载	
JSON Formatter		下载	
JSON Viewer		下载	
JSON Finder		下载	
Encode/Decode插件

名称	简介	下载地址	使用教程
Base64 Encode and Decode		下载	
Git Plugin

名称	简介	下载地址	使用教程
Git Cheat Sheet		下载	
Android Dev Guides
Google Java编程风格指南中文版

英文地址：http://google-styleguide.googlecode.com/svn/trunk/javaguide.html

地址0：http://hawstein.com/posts/google-java-style.html

地址1：https://github.com/codeset/google-java-styleguide

Android Api中文版

地址：http://wikidroid.sinaapp.com/Android中文API)

Android API指南中文版

地址：http://wiki.eoeandroid.com/Android_API_Guides

Android Proguard混淆配置指南

地址：https://github.com/inferjay/AndroidProguardGuide/

Gradle插件使用指南中文版

地址：http://avatarqing.github.io/Gradle-Plugin-User-Guide-Chinese-Verision

Gradle User Guide

Gradle 1.12用户指南：http://pan.baidu.com/s/1dD7sC2d

Android Dev Tutorials
Android学习之路

地址：http://stormzhang.github.io/android/2014/07/07/learn-android-from-rookie/

Google Android官方培训课程中文版

地址：http://hukai.me/android-training-course-in-chinese/index.html

Developing Android Apps

地址：https://www.udacity.com/course/ud853

Java Design Patterns Samples in Java.

Java Design Patterns

Design Tools
Photoshop插件

名称	简介	下载地址	使用教程
Cut&Slice	切图神器	下载	
DevRocket	切图神器	下载	
Cutterman	最好用的切图工具	下载	
Ink		下载	
Corner Editor	路径圆角编辑工具	下载1 
下载1	
GuideGuide	辅助线工具	下载	
Assistor PS		下载	
Skeuomorphism.it		下载	
QuickGuide		下载	
Long Shadow Generator	长投影效果生成插件	下载	
android_resizer_toolkit		下载	
android-ps-tools	一些方便Android UI设计的PhototShop插件。	下载	
LayerCraft	A Photoshop plugin to export UI assets from layers	下载	
矢量图设计工具

名称	简介	下载地址	使用教程
Sketch 3		下载	
Affinity Designer		下载	
Gravit		下载	
Adobe Illustrator		下载	
切图工具

名称	简介	下载地址	使用教程
Slicy		下载	
设计稿尺寸标注工具

名称	简介	下载地址	使用教程
马克鳗		下载	
PxCook像素大厨	UI设计师效率提升利器，让你专注于设计本质，
不再为标注切图而烦恼，从设计到实现一气呵成	下载	使用教程
原型设计工具

名称	简介	下载地址	使用教程
Axure		下载	
Fluid UI		下载	
Briefs		下载	
Flinto		下载	
Balsamiq Mockups		下载	
AppCooker		下载	
Proto.io		下载	
UXPin		下载	
InVision		下载	
POP		下载	
快现		下载	
Composite		下载	
OmniGraffle		下载	
Marvelapp		下载	
Justinmind		下载	
Form		下载	
Prott		下载	
Composite		下载	
交互设计工具

名称	简介	下载地址	使用教程
Framer Studio		下载	
Quartz Composer		下载	
Origami		下载	
jQC		下载	
Avocado		下载	
Pixate		下载	
UI效果预览工具

名称	简介	下载地址	使用教程
Android Design Preview		下载	
PS Play		下载	
Pixl Preview		下载	
Skala Preview		下载	
LiveView		下载	
配色工具

名称	简介	下载地址	使用教程
Android Material Design可视化调色板		下载	
Android Material Design Colours.xml		下载	
Colorube配色神器		下载	
Adobe Kuler		下载	
ColorSchemer Studio		下载	
Piknik		下载	
设计稿版本控制工具

名称	简介	下载地址	使用教程
LayerVault		下载	
图标处理工具

名称	简介	下载地址	使用教程
Icon Slate		下载	
在线Icon库

名称	简介	下载地址	使用教程
IconFont		下载	
NounProject		下载	
取色工具

名称	简介	下载地址	使用教程
ColorSnapper		下载	
不透明度16进制值

不透明度	16进制值
100%	FF
95%	F2
90%	E6
85%	D9
80%	CC
75%	BF
70%	B3
65%	A6
60%	99
55%	8C
50%	80
45%	73
40%	66
35%	59
30%	4D
25%	40
20%	33
15%	26
10%	1A
5%	0D
0%	00
出自：http://stackoverflow.com/questions/5445085/understanding-colors-in-android-6-chars

手机To电脑同步预览工具

名称	简介	下载地址	使用教程
Reflector		下载	
x-Mirage		下载	
AirServer		下载	
BBQScreen		下载	
Gif图片录制工具

名称	简介	下载地址	使用教程
LICEcap		下载	
GifCam		下载	
UI Programming Language
UILang

Design Tutorials
HackDesign

Design Games
The Bezier Game

一个帮助你练习PS里钢笔工具的小游戏。

Design Guides
Android设计指南非官方简体中文版

Topfun镜像地址：http://www.topfun.us/adchs/index.html

Github镜像地址：http://adchs.github.io

ApkBus镜像地址：http://www.apkbus.com/design/

Segmentfault镜像地址：http://mirrors.segmentfault.com/adchs/

多看阅读镜像地址：http://www.duokan.com/book/47790

Android Cheatsheet for Graphic Designers

地址:http://petrnohejl.github.io/Android-Cheatsheet-For-Graphic-Designers/

Google Material Design 中文版

地址：http://design.1sters.com

地址： http://www.ui.cn/Material/

Designer's Guide To dpi

地址：http://sebastien-gabriel.com/designers-guide-to-dpi/home

Email Design Guide

地址：http://mailchimp.com/resources/email-design-guide/

Free Design Resources
Google Material Design 素材(感谢 @SanityD)

Material Design Icon Templates

Material Design的图标集

Material Design UI Kit for Sketch

Nexus 5 template for Sketch

Free Design Resources

434 SVG icons

UI Cloun

161个国内外社交网站矢量图标

250 free icons in 5 sizes and 14 colors

MINIMALISTIC EVERYDAY ICONS

Books
Free Programming Books

一堆免费的Android开发相关的电子书。

50 Android Hacks

50 Android Hacks这本书分12个部分介绍了50个Android开发的小技巧。

免费的编程中文书籍索引
