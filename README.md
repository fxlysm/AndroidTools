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




<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>AndroidDevTools</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="无需翻墙下载最新版Android开发工具 ADT Bundle Android Studio SDK Tools">
    <meta name="ujianVerification" content="ee5a6c5854f1826b3123039d726496c9" />
    <link href="static/css/bootstrap-combined.min.css" rel="stylesheet">
    <link href="static/css/app.css" rel="stylesheet">
    <link href="static/css/app-theme.css" rel="stylesheet">
    <link href="static/css/google-roboto-font-face.css" rel="stylesheet" type="text/css">
    <!--[if lt IE 9]><script src="static/html5shiv.min.js"></script><![endif]-->
  </head>
  <body data-target=".content-nav">
    <header>
      <div class="container">
        <div class="row">
          <div class="span2">
            <h1 id="nav-title">AndroidDevTools</h1>
          </div>
          <div class="span10">
            <menu>
		            <ul class="nav navbar-nav">
		            <ul class="nav nav-pills" role="tablist">
		            		
										<!--  Android SDK Tools	-->
							      <li role="presentation" class="dropdown">
							        <a id="drop-sdk-tools" href="#" class="dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false"><span>Android SDK Tools</span></a>
							        <ul id="menu-sdl-tools" class="dropdown-menu" role="menu" aria-labelledby="drop-sdk-tools">
							          <li role="presentation"><a role="menuitem" tabindex="0" href="#android-studio">Android Studio</a></li>							          
							          <li role="presentation"><a role="menuitem" tabindex="2" href="#sdk-tools">SDK Tools</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="2" href="#sdk-platform-tools">Platform-tools</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="2" href="#build-tools">Build Tools</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="3" href="#sdk-list">SDK</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#ndk">NDK</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#jdk">JDK</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#adt-bundle">ADT Bundle</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="1" href="#adt-plugin">ADT Plugin</a></li>  
							          <li role="presentation"><a role="menuitem" tabindex="4" href="#sdk-system-images">SDK System images</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#googlemap-apis-sdk">GoogleMap APIs SDK</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#google-glass-sdk">Google Glass SDK</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#google-tv-addon">Google TV Addon</a></li>       
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#android-sdk-extras">Android SDK Extras</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#support-library">Support Library</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#sdk-samples">SDK Samples</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#android-framework-source-code">Android Framework Source Code</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#android-l-preview-system-image">Android L Preview System Image</a></li>							                
							        </ul>
							      </li>
							      
							      <!--  Android Dev Tools	-->
							      <li role="presentation" class="dropdown">
							        <a id="drop-dev-tools" href="#" class="dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">Android Dev Tools</a>
							        <ul id="menu-dev-tool" class="dropdown-menu" role="menu" aria-labelledby="drop-dev-tools">
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#gradle">Gradle</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#version-control-tools">版本控制工具</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#apk-decompile-tools">Apk反编译工具</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#security-tools">安全工具</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#search-tools">搜索工具</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#debug-tools">Debug调试工具</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#api-test-tools">Api测试工具</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#eclipse-android-studio-idea-plugin">IDE插件</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#android-res-themes-style-generator-tools">Themes/Style生成工具</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#android-res-analysis-tools">资源分析工具</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#android-layout-parser-tools">Layout Parser工具</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#android-content-provider-generator-tools">Content Provider代码生成工具</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#android-fragment-code-generator-tools">Fragment代码生成工具</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#android-code-generator-tools">代码生成工具</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#android-native-dev-tools">Native开发工具</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#android-test-tools">测试工具</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#multi-channel-apk-genterator-tools">Apk多渠道打包工具</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#android-log-collection-tools">日志收集工具</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#android-other-language-dev-tools">其他语言开发Android应用工具</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#adroid-sensors-simulate-tools">传感器模拟工具</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#android-serial-dev-tools">串口开发工具</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#img-size-handle-tools">图片尺寸处理工具</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#img-compress-tools">图片压缩工具</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#android-res-clean-tools">资源清理工具</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#px-to-dp-convert-tools">px和dp转换/计算工具</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#java-to-ios">Java To iOS</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#json-xml-to-pojo-class-tools">JSON/XML转换为POJO Class工具</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#java-dao-generate-tools">Java DAO Generate工具</a></li>
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#books-list">Books</a></li>
							        </ul>
							      </li>      
										
										<!--  Android Dev Guides	-->
							      <li role="presentation" class="dropdown">
							        <a id="drop-dev-guides" href="#" class="dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
							          Android Dev Guides
							        </a>
							        <ul id="menu-dev-guides" class="dropdown-menu" role="menu" aria-labelledby="drop-dev-guides">
							          <li role="presentation"><a role="menuitem" tabindex="-1" href="#google-java-program-guide-cn">Google Java编程风格指南中文版</a></li>
												<li role="presentation"><a role="menuitem" tabindex="-1" href="#android-api-doc-cn">Android Api中文版</a></li>
												<li role="presentation"><a role="menuitem" tabindex="-1" href="#android-api-guide-cn">Android API指南中文版</a></li>
												<li role="presentation"><a role="menuitem" tabindex="-1" href="#proguard-config-guide">Proguard混淆配置指南</a></li>
												<li role="presentation"><a role="menuitem" tabindex="-1" href="#gradle-plugin-guide-cn">Gradle插件使用指南中文版</a></li>
												<li role="presentation"><a role="menuitem" tabindex="-1" href="#gradle-user-guide">Gradle User Guide</a></li>
							        </ul>
							      </li>
										
										<!--  Android Dev Tutorials	-->
							      <li role="presentation" class="dropdown">
							        <a id="drop-dev-tutorials" href="#" class="dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
							          Android Dev Tutorials
							        </a>
							        <ul id="menu3" class="dropdown-menu" role="menu" aria-labelledby="drop-dev-tutorials">
												<li role="presentation"><a role="menuitem" tabindex="-1" href="#android-learning-way">Android学习之路</a></li>
												<li role="presentation"><a role="menuitem" tabindex="-1" href="#google-androidtraining-tutorials">Android官方培训课程中文版</a></li>
												<li role="presentation"><a role="menuitem" tabindex="-1" href="#developing-android-apps">Developing Android Apps</a></li>
												<li role="presentation"><a role="menuitem" tabindex="-1" href="#java-design-patterns-samples-in-java">Java Design Patterns Samples</a></li>
							        </ul>
							      </li>
							
										<!--  Design Tools	-->
							      <li role="presentation" class="dropdown">
							        <a id="drop-design-tools" href="#" class="dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
							          Design Tools
							        </a>
							        <ul id="menu4" class="dropdown-menu" role="menu" aria-labelledby="drop-design-tools">
													<li role="presentation"><a role="menuitem" tabindex="-1" href="#photoshop-plugin">Photoshop插件</a></li>
					                <li role="presentation"><a role="menuitem" tabindex="-1" href="#vector-img-design-tools">矢量图设计工具</a></li>					
					                <li role="presentation"><a role="menuitem" tabindex="-1" href="#ui-icon-export-ools">切图工具</a></li>					
					                <li role="presentation"><a role="menuitem" tabindex="-1" href="#desgin-size-mark-tools">设计稿尺寸标注工具</a></li>					
					                <li role="presentation"><a role="menuitem" tabindex="-1" href="#prototype-design-tools">原型设计工具</a></li>					
					                <li role="presentation"><a role="menuitem" tabindex="-1" href="#interaction-desgin-tools">交互设计工具</a></li>					
					                <li role="presentation"><a role="menuitem" tabindex="-1" href="#ui-effect-preview-tools">UI效果预览工具</a></li>					
					                <li role="presentation"><a role="menuitem" tabindex="-1" href="#harmonize-colors-tools">配色工具</a></li>					
					                <li role="presentation"><a role="menuitem" tabindex="-1" href="#design-cvs-tools">设计稿版本控制工具</a></li>					
					                <li role="presentation"><a role="menuitem" tabindex="-1" href="#icon-handle-tools">图标处理工具</a></li>					
					                <li role="presentation"><a role="menuitem" tabindex="-1" href="#online-icon-library">在线Icon库</a></li>				
					                <li role="presentation"><a role="menuitem" tabindex="-1" href="#take-color-tools">取色工具</a></li>				
					                <li role="presentation"><a role="menuitem" tabindex="-1" href="#hex-opacity-list">不透明度16进制值</a></li>					
					                <li role="presentation"><a role="menuitem" tabindex="-1" href="#phone-to-computer-preview-tools">同步预览工具</a></li>					
					                <li role="presentation"><a role="menuitem" tabindex="-1" href="#gif-record-tools">Gif图片录制工具</a></li>				
													<li role="presentation"><a role="menuitem" tabindex="-1" href="#design-tutorials">Design Tutorials</a></li>					
													<li role="presentation"><a role="menuitem" tabindex="-1" href="#design-guides">Design Guides</a></li>									
													<li role="presentation"><a role="menuitem" tabindex="-1" href="#free-design-resources">Design Resources</a></li>				
							        </ul>
							      </li>
							      
							      <!--  View GitHub Project	-->
										<!-- <li><a href="https://github.com/inferjay/AndroidDevTools" data-title="View GitHub Project" class="menu github"><img src="static/image/icon-github.png" alt="GitHub"/></a></li> -->
														     
								</ul>                
            </menu>
          </div>
      </div>
    </header>

    <section id="body">
      <div id="body-container" class="container">
        <div class="row">
        	<div class="span1"></div>
          <div class="span10">       
          
            <h1 id="introduction">AndroidDevTools简介</h1>
            <blockquote>
		            <p>
		                <strong>Android Dev Tools官网地址：<a href="http://www.androiddevtools.cn">www.androiddevtools.cn</a></strong>
		            </p>
		
		            <p>收集整理Android开发所需的Android SDK、开发中用到的工具、Android开发教程、Android设计规范，免费的设计素材等。</p>
		
		            <p>欢迎大家推荐自己在Android开发过程中用的好用的工具、学习开发教程、用到设计素材，欢迎Star、Fork
		                <g-emoji alias="smile" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f604.png"></g-emoji>。</p>
		            <p>如果你对翻译英文的Android开发技术文章感兴趣，欢迎Start和Fork<a href="https://github.com/AWCNTT/ArticleTranslateProject">AndroidWeekly中国文章翻译项目</a></p>
            </blockquote>
            
            <h1 id="android-dev-tools">
                <a name="android-tools" class="anchor" href="#android-tools">
                    <span class="octicon octicon-link"></span>
                </a>Android Tools</h1>
             
            <h4>
<a id="android-sdk-online-server" class="anchor" href="#android-sdk%E5%9C%A8%E7%BA%BF%E6%9B%B4%E6%96%B0%E9%95%9C%E5%83%8F%E6%9C%8D%E5%8A%A1%E5%99%A8" aria-hidden="true"><span class="octicon octicon-link"></span></a>Android SDK在线更新镜像服务器</h4>
            <ol>
            		<li>
									<p>中国科学院开源协会镜像站地址:</p>
									<ul>
									<li><p>IPV4/IPV6: <code>http://mirrors.opencas.cn</code> 端口：80</p></li>
									<li><p>IPV4/IPV6: <code>http://mirrors.opencas.org</code> 端口：80</p></li>
									<li><p>IPV4/IPV6: <code>http://mirrors.opencas.ac.cn</code> 端口：80</p></li>
									</ul>
								</li>
            		<li>
									<p>上海GDG镜像服务器地址:</p>								
									<p><code>http://sdk.gdgshanghai.com</code>  端口：8000</p>
								</li>								
								<li>
								<p>北京化工大学镜像服务器地址: </p>								
								<ul>
								<li><p>IPv4: <code>http://ubuntu.buct.edu.cn/</code> 端口：80</p></li>
								<li><p>IPv4: <code>http://ubuntu.buct.cn/</code>   端口：80</p></li>
								<li><p>IPv6: <code>http://ubuntu.buct6.edu.cn/</code>  端口：80</p></li>
								</ul>
								</li>
								<li>
								<p>大连东软信息学院镜像服务器地址: </p>								
								<p><code>http://mirrors.neusoft.edu.cn</code> 端口：80</p>
								</li>
						</ol>
            <p><strong>使用方法</strong>：</p>
            <ol>
								<li><p>启动 Android SDK Manager ，打开主界面，依次选择『<strong>Tools</strong>』、『<strong>Options...</strong>』，弹出『<strong>Android SDK Manager - Settings</strong>』窗口；</p></li>
								<li><p>在『<strong>Android SDK Manager - Settings</strong>』窗口中，在『<strong>HTTP Proxy Server」和「HTTP Proxy Port</strong>』输入框内填入上面镜像服务器地址(<strong>不包含http://</strong>，如下图)和端口，并且选中『<strong>Force https://... sources to be fetched using http://...</strong>』复选框。设置完成后单击『<strong>Close</strong>』按钮关闭『<strong>Android SDK Manager - Settings</strong>』窗口返回到主界面；</p></li>
								<li><p>依次选择『<strong>Packages</strong>』、『<strong>Reload</strong>』。</p></li>
						</ol>
            <img src="static/image/sdk-manager-proxy-settings.png" width="40%" height="20%" alt="SDK Manager Proxy Settings"/>
            
            <h4 id="android-studio">
                <a name="android-studio" class="anchor" href="#android-studio">
                    <span class="octicon octicon-link"></span>
                </a>Android Studio</h4>

            <table>
                <thead>
                    <tr>
                        <th align="center">版本号</th>
                        <th align="center">Windows</th>
                        <th align="center">Mac OSX</th>
                        <th align="center">Linux</th>
                    </tr>
                </thead>
                <tbody>
                	<tr>
										<td align="center">1.2 正式版</td>
										<td align="center"><a href="http://pan.baidu.com/s/1mgKehW8">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1sj0rdF3">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1dD0F5b7">下载</a></td>
									</tr>
                	<tr>
										<td align="center">1.2 RC3</td>
										<td align="center"><a href="http://pan.baidu.com/s/1mgrDRvU">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1mgMfXuK">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1ntuZ61V">下载</a></td>
									</tr>
                	<tr>
										<td align="center">1.2 RC2</td>
										<td align="center"><a href="http://pan.baidu.com/s/1wHTMm">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1dDiyDe5">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1i3CcG7N">下载</a></td>
									</tr>
                	<tr>
										<td align="center">1.2 RC</td>
										<td align="center"><a href="http://pan.baidu.com/s/1eQdCBC2">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1dDztuMH">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1nt20Pvj">下载</a></td>
									</tr>
                	<tr>
										<td align="center">1.2 Beta3</td>
										<td align="center"><a href="http://pan.baidu.com/s/1i3gT9Rn">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1eQnLwhO">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/154yIE">下载</a></td>
									</tr>
                	<tr>
										<td align="center">1.2 Beta2</td>
										<td align="center"><a href="http://pan.baidu.com/s/1ntyww5r">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1sjHRbi9">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1jGzOx0M">下载</a></td>
									</tr>
                	<tr>
										<td align="center">1.2 Beta</td>
										<td align="center"><a href="http://pan.baidu.com/s/1c0cZHXu">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1bnrUSBd">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1kTpCFTt">下载</a></td>
									</tr>
                	<tr>
										<td align="center">1.2 Preview 4</td>
										<td align="center"><a href="http://pan.baidu.com/s/1pJ0ZHij">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1i3kqZ9j">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1i3w2nNv">下载</a></td>
									</tr>
                	<tr>
										<td align="center">1.2 Preview 3</td>
										<td align="center"><a href="http://pan.baidu.com/s/1qWx97pa">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1i3BuYFz">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1c0B5qdM">下载</a></td>
									</tr>
                	<tr>
										<td align="center">1.2 Preview 2</td>
										<td align="center"><a href="http://pan.baidu.com/s/1qWn0bqk">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1jGEaFII">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1o6Fo0iu">下载</a></td>
									</tr>
                	<tr>
										<td align="center">1.2 Preview 1</td>
										<td align="center"><a href="http://pan.baidu.com/s/1sj6uAfz">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1mgIGdio">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1mgsrAXU">下载</a></td>
									</tr>
                	<tr>
                    <td align="center">1.1 正式版</td>
                    <td align="center"><a href="http://pan.baidu.com/s/1sjr1dpj">下载</a></td>
                    <td align="center"><a href="http://pan.baidu.com/s/1mg0yHi4">下载</a></td>
                    <td align="center"><a href="http://pan.baidu.com/s/1jGDubg6">下载</a></td>
                  </tr>
                	<tr>
                    <td align="center">1.1 RC1</td>
                    <td align="center"><a href="http://pan.baidu.com/s/1jG3QuV0">下载</a></td>
                    <td align="center"><a href="http://pan.baidu.com/s/1eQhDPPw">下载</a></td>
                    <td align="center"><a href="http://pan.baidu.com/s/1o6smUng">下载</a></td>
                  </tr>
                	<tr>
										<td align="center">1.1 Beta4</td>
										<td align="center"><a href="http://pan.baidu.com/s/1ntMaSA1">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1bn2IyMN">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1qWPs9dy">下载</a></td>
									</tr>
									<tr>
										<td align="center">1.1 Beta3</td>
										<td align="center"><a href="http://pan.baidu.com/s/1pJoMNSf">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1qWyoku4">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1jG24kv0">下载</a></td>
									</tr>
                	<tr>
										<td align="center">1.1 Beta2</td>
										<td align="center"><a href="http://pan.baidu.com/s/1gdCJ4H1">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1hqpaWa4">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1i3w0vT7">下载</a></td>
									</tr>
                  <tr>
										<td align="center">1.1 Beta</td>
										<td align="center"><a href="http://pan.baidu.com/s/1dDo1b9Z">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1kT21VQv">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1gdrKGsb">下载</a></td>
									</tr>
                  <tr>
										<td align="center">1.1 Preview 2</td>
										<td align="center"><a href="http://pan.baidu.com/s/1pJMCx79">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1eQd901k">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1sjuiarb">下载</a></td>
									</tr>
                	<tr>
										<td align="center">1.1 Preview 1</td>
										<td align="center"><a href="http://pan.baidu.com/s/1kTFsJ9H">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1o6p4j8I">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1pJJouDl">下载</a></td>
									</tr>
                	<tr>
										<td align="center">1.0.2</td>
										<td align="center"><a href="http://pan.baidu.com/s/1pJA0b0n">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1jGuvmuU">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1qWCzSjM">下载</a></td>
									</tr>
                	<tr>
										<td align="center">1.0.1</td>
										<td align="center"><a href="http://pan.baidu.com/s/1cu76m">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1hqoZCDe">下载</a></td>
										<td align="center"><a href="http://pan.baidu.com/s/1c0nLN6g">下载</a></td>
									</tr>
                	<tr>
                     <td align="center">1.0正式版</td>
                     <td align="center"><a href="http://pan.baidu.com/s/1eQzmQDO">下载</a></td>
                     <td align="center"><a href="http://pan.baidu.com/s/1dDitUFJ">下载</a></td>
                     <td align="center"><a href="http://pan.baidu.com/s/1kTn7wLx">下载</a></td>
                  </tr>
                	<tr>
                     <td align="center">1.0 RC4</td>
                      <td align="center"><a href="http://pan.baidu.com/s/1pJkbwin">下载</a></td>
                      <td align="center"><a href="http://pan.baidu.com/s/1hq1QBVQ">下载</a></td>
                      <td align="center"><a href="http://pan.baidu.com/s/1eQBygj4">下载</a>
                      </td>
                   </tr>
                   <tr>
                        <td align="center">1.0 RC2</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1sjx4rNJ">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1eQpJmqI">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1ntuUBvN">下载</a>
                        </td>
                   </tr>
                   <tr>
                        <td align="center">1.0 RC1</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1sjsKtIl">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1gdrcRfX">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1sjO82st">下载</a>
                        </td>
                   </tr>
                   <tr>
                        <td align="center">0.9.3</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1o6JoLzc">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1o69LsOq">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1c0B1Gju">下载</a>
                        </td>
                   </tr>
                   <tr>
                        <td align="center">0.9.2</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1gdzkjgn">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1sj17AJN">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1c0hFuDi">下载</a>
                        </td>
                   </tr>
                   <tr>
                        <td align="center">0.9.1</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1gdgTnqF">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1qW3B0Ck">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1dDitjW1">下载</a>
                        </td>
                   </tr>
                   <tr>
                        <td align="center">0.9.0</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1eQ3VNMi">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1bnCPy5x">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1tUA5o">下载</a>
                        </td>
                   </tr>
                   <tr>
                        <td align="center">0.8.14</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1kT1d5JL">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1jGj4Eu6">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1gdgmYiR">下载</a>
                        </td>
                   </tr>
                   <tr>
                        <td align="center">0.8.13</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1mgE85Pu">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1jGBoOiq">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1hqJ0xhi">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center">0.8.12</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1eQ3ps2I">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1o6uR15g">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1i3uvHid">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center">0.8.11</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1c0lbPEK">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1sjpveBN">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1gdCGfgn">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center">0.8.10</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1o6NWZuq">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1o6E36um">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1i3iPGtn">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center">0.8.9</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1mggH8P6">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1bnrjr0F">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1c0ozyz2">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center">0.8.8</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1o6hZneE">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1gdh77nt">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1dDgVDxn">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center">0.8.7</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1ntt61xn">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1eQCHAV4">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1eQcPIcq">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center">0.8.6</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1mg6zsGK">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1nt5b0F3">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1hq674bU">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center">0.8.5</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1dDxQfh3">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1bn6HEwR">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1dDkYOMH">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center">0.8.4</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1qWqbWyo">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1i3Ia7Nv">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1ntwTDqx">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center">0.8.3</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1eQioNrs">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1o6v5E6Q">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1bnb9uiz">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center">0.8.2</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1eQ1ln14">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1pJkDQHl">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1c0ncknA">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center">0.8.1</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1o6LTxVG">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1dD5qHjF">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1kTqlzxH">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center">0.8 0</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1eQ5oGaI">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1kTHpLyR">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1c0qzDao">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center">0.6.1</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1hqqX2ba">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1qWjpB9y">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1qWBFTiG">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center">0.6.0</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1sjJf0Pf">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1jcixK">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1hqpB7As">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center">0.5.9</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1dDw3oYl">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1c08a8y0">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1hqeMmVU">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center">0.5.8</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1qWLPqd2">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1i3ECc9f">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1i37QxBf">下载</a>
                        </td>
                    </tr>
                </tbody>
            </table>

            <h4 id="sdk-tools">
                <a name="sdk-tools" class="anchor" href="#sdk-tools">
                    <span class="octicon octicon-link"></span>
                </a>SDK Tools</h4>

            <table>
                <thead>
                    <tr>
                        <th align="center">版本号</th>
                        <th align="center">Windows</th>
                        <th align="center">Mac OSX</th>
                        <th align="center">Linux</th>
                    </tr>
                </thead>
                <tbody>
                <tr>
                        <td align="center">sdk-tools-r24.1.2</td>
                        <td align="center">
                            <a href="http://pan.baidu.com/s/1pJwVClt">installer_r24.1.2-windows.exe</a>  
                            <a href="http://pan.baidu.com/s/1ntOefLf">android-sdk_r24.1.2-windows.zip</a>
                        </td>
                        <td align="center">
                        	<a href="http://pan.baidu.com/s/1qWv7Jpq">android-sdk_r24.1.2-macosx.zip</a>
                        </td>
                        <td align="center">
                        	<a href="http://pan.baidu.com/s/1ntzbACp">android-sdk_r24.1.2-linux.tgz</a>
                        </td>
                    </tr>
                	<tr>
                        <td align="center">sdk-tools-r24.0.2</td>
                        <td align="center">
                            <a href="http://pan.baidu.com/s/1eQH3ZOI">installer_r24.0.2-windows.exe</a>  
                            <a href="http://pan.baidu.com/s/1c0vnzMC">android-sdk_r24.0.2-windows.zip</a>
                        </td>
                        <td align="center">
                        	<a href="http://pan.baidu.com/s/1mgDnXMw">android-sdk_r24.0.2-macosx.zip</a>
                        </td>
                        <td align="center">
                        	<a href="http://pan.baidu.com/s/1eQEglTS">android-sdk_r24.0.2-linux.tgz</a>
                        </td>
                    </tr>
                	<tr>
                        <td align="center">sdk-tools-r24.0.1</td>
                        <td align="center">
                            <a href="http://pan.baidu.com/s/1gdgojhp">installer_r24.0.1-windows.exe</a>  
                            <a href="http://pan.baidu.com/s/1gdEKclP">android-sdk_r24.0.1-windows.zip</a>
                        </td>
                        <td align="center">
                        	<a href="http://pan.baidu.com/s/1i3467DN">android-sdk_r24.0.1-macosx.zip</a>
                        </td>
                        <td align="center">
                        	<a href="http://pan.baidu.com/s/1gdvNj83">android-sdk_r24.0.1-linux.tgz</a>
                        </td>
                    </tr>
                	<tr>
                        <td align="center">sdk-tools-r24</td>
                        <td align="center">
                            <a href="http://pan.baidu.com/s/1jG5ks7c">installer_r24-windows.exe</a>  
                            <a href="http://pan.baidu.com/s/1pJ4uk4r">android-sdk_r24-windows.zip</a>
                        </td>
                        <td align="center">
                        	<a href="http://pan.baidu.com/s/1pJ8xUgN">android-sdk_r24-macosx.zip</a>
                        </td>
                        <td align="center">
                        	<a href="http://pan.baidu.com/s/1pJ4uk47">android-sdk_r24-linux.tgz</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center">sdk-tools-r23.0.5</td>
                        <td align="center">
                            <a href="http://pan.baidu.com/s/1bntmoqV">android-sdk_r23.0.5-windows(非官方版).zip</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1o6LWg10">android-sdk_r23.0.5-macosx(非官方版).zip</a>
                        </td>
                        <td align="center">
                        </td>
                    </tr>
                    <tr>
                        <td align="center">sdk-tools-r23.0.2</td>
                        <td align="center">
                            <a href="http://pan.baidu.com/s/1jGj2xIA">installer_r23.0.2-windows.exe</a>  
                            <a href="http://pan.baidu.com/s/1CiWSu">android-sdk_r23.0.2-windows.zip</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1bny9Mk3">android-sdk_r23.0.2-macosx.zip</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1qWAu4o8">android-sdk_r23.0.2-linux.tgz</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center">sdk-tools-r23</td>
                        <td align="center">
                            <a href="http://pan.baidu.com/s/1nt5Gwhb">installer_r23-windows.exe</a>  <a href="http://pan.baidu.com/s/1kTC6akZ">android-sdk_r23-windows.zip</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1gdj7X3l">android-sdk_r23-macosx.zip</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1yBnSa">android-sdk_r23-linux.tgz</a>
                        </td>
                    </tr>
                </tbody>
            </table>
	    
	    <blockquote>
		  <p>
		     <strong>备注：</strong> <code>非官方版</code> 是在 <code>23.0.2</code> 的基础上进行了在线更新包含了 <code>Android 5.0 SDK</code> ，<code>SDK Tools 23.0.5</code> 、<code>Build Tools 21.0.1</code> 、<code>Support Library 21</code>等。
		  </p>
	    </blockquote>
	    
	    <h4><a id="sdk-platform-tools" class="anchor" href="#sdk-platform-tools" aria-hidden="true"><span class="octicon octicon-link"></span></a>SDK Platform-Tools</h4>
			<p>这是 adb, fastboot 等工具包。把解压出来的 <code>platform-tools</code> 文件夹放在 android sdk 根目录下，并把 <code>adb</code>所在的目录添加到系统 <code>PATH</code> 路径里，即可在命令行里直接访问了 adb, fastboot 等工具。</p>
	    <table>
				<thead>
					<tr>
					<th align="left">版本号</th>
					<th align="center">Windows</th>
					<th align="left">Mac OSX</th>
					<th align="center">Linux</th>
					</tr>
				</thead>
				<tbody>
				<tr>
					<td align="left">platform-tools-r22</td>
					<td align="center"><a href="http://pan.baidu.com/s/1sj4ZfTb">platform-tools_r22-windows.zip</a></td>
					<td align="left"><a href="http://pan.baidu.com/s/1jG3l6Ea">platform-tools_r22-mac.zip</a></td>
					<td align="center"><a href="http://pan.baidu.com/s/1c0GUTxA">platform-tools_r22-linux.zip</a></td>
					</tr>
					<tr>
					<td align="left">platform-tools-r21</td>
					<td align="center"><a href="http://pan.baidu.com/s/1gdF1fkZ">platform-tools_r21-windows.zip</a></td>
					<td align="left"><a href="http://pan.baidu.com/s/1dDu6xC9">platform-tools_r21-mac.zip</a></td>
					<td align="center"><a href="http://pan.baidu.com/s/1dDAL25j">platform-tools_r21-linux.zip</a></td>
					</tr>
					<tr>
					<td align="left">platform-tools-r20</td>
					<td align="center"><a href="http://pan.baidu.com/s/1ntHqLZj">platform-tools_r20-windows.zip</a></td>
					<td align="left"><a href="http://pan.baidu.com/s/1gdy6fzP">platform-tools_r20-mac.zip</a></td>
					<td align="center"><a href="http://pan.baidu.com/s/173KQi">platform-tools_r20-linux.zip</a></td>
					</tr>
				</tbody>
			</table>
	    
	    <h4>
		<a id="build-tools" class="anchor" href="#build-tools" aria-hidden="true"><span class="octicon octicon-link"></span></a>Build-Tools</h4>
		<p>这是Android开发所需的Build-Tools，下载并解压后，将解压出的整个文件夹复制或者移动到 <code>your sdk 路径/build-tools</code> 文件夹即可。</p>
		<table>
		<thead>
		<tr>
		<th align="center">版本号</th>
		<th align="center">Windows</th>
		<th align="center">Mac OSX</th>
		<th align="center">Linux</th>
		</tr>
		</thead>
		<tbody>
				<tr>
					<td align="center">21.1.2</td>
					<td align="center"><a href="http://pan.baidu.com/s/1i3kqFHV">下载</a></td>
					<td align="center"><a href="http://pan.baidu.com/s/1jGquuqU">下载</a></td>
					<td align="center"><a href="http://pan.baidu.com/s/1dDdDne5">下载</a></td>
				</tr>
				<tr>
					<td align="center">21.1.2</td>
					<td align="center"><a href="http://pan.baidu.com/s/1hqH1pZY">下载</a></td>
					<td align="center"><a href="http://pan.baidu.com/s/1hq1mml2">下载</a></td>
					<td align="center"></td>
				</tr>
				<tr>
					<td align="center">21.1.1</td>
					<td align="center"><a href="http://pan.baidu.com/s/1mgzFXW0">下载</a></td>
					<td align="center"><a href="http://pan.baidu.com/s/1i367FTz">下载</a></td>
					<td align="center"></td>
				</tr>
				<tr>
				<td align="center">21.1.0</td>
				<td align="center"><a href="http://pan.baidu.com/s/1pJ3DCGN">下载</a></td>
				<td align="center"><a href="http://pan.baidu.com/s/1hqIfeCW">下载</a></td>
				<td align="center"></td>
				</tr>
				<tr>
				<td align="center">21.0.2</td>
				<td align="center"><a href="http://pan.baidu.com/s/1kTDpnt9">下载</a></td>
				<td align="center"><a href="http://pan.baidu.com/s/1dDCf9TZ">下载</a></td>
				<td align="center"></td>
				</tr>
				<tr>
				<td align="center">21.0.1</td>
				<td align="center"><a href="http://pan.baidu.com/s/1eQreI6A">下载</a></td>
				<td align="center"><a href="http://pan.baidu.com/s/1eQCd5YE">下载</a></td>
				<td align="center"></td>
				</tr>
				<tr>
				<td align="center">21.0.0</td>
				<td align="center"><a href="http://pan.baidu.com/s/1i3y0mKd">下载</a></td>
				<td align="center"><a href="http://pan.baidu.com/s/1i3oWM01">下载</a></td>
				<td align="center"></td>
				</tr>
				<tr>
				<td align="center">20.0.0</td>
				<td align="center"></td>
				<td align="center"><a href="http://pan.baidu.com/s/1c0AfIOK">下载</a></td>
				<td align="center"></td>
				</tr>
				<tr>
				<td align="center">19.1.0</td>
				<td align="center"><a href="http://pan.baidu.com/s/1nttAyhV">下载</a></td>
				<td align="center"><a href="http://pan.baidu.com/s/1nt2vM21">下载</a></td>
				<td align="center"></td>
				</tr>
				<tr>
				<td align="center">19.0.3</td>
				<td align="center"><a href="http://pan.baidu.com/s/1qWCzdwC">下载</a></td>
				<td align="center"><a href="http://pan.baidu.com/s/1hq7VIgG">下载</a></td>
				<td align="center"></td>
				</tr>
				<tr>
				<td align="center">19.0.2</td>
				<td align="center"><a href="http://pan.baidu.com/s/1ntl0Qnf">下载</a></td>
				<td align="center"><a href="http://pan.baidu.com/s/1xY7PO">下载</a></td>
				<td align="center"></td>
				</tr>
				<tr>
				<td align="center">19.0.1</td>
				<td align="center"><a href="http://pan.baidu.com/s/1pJ1BJrt">下载</a></td>
				<td align="center"><a href="http://pan.baidu.com/s/1o65bAwa">下载</a></td>
				<td align="center"></td>
				</tr>
				<tr>
				<td align="center">19.0.0</td>
				<td align="center"><a href="http://pan.baidu.com/s/1o6I8NBs">下载</a></td>
				<td align="center"><a href="http://pan.baidu.com/s/1c0dBDvE">下载</a></td>
				<td align="center"></td>
				</tr>
		</tbody>
		</table>

            <h4 id="sdk-list">
                <a name="sdk" class="anchor" href="#sdk-list">
                    <span class="octicon octicon-link"></span>
                </a>SDK</h4>

            <p>这是Android开发所需的sdk，下载并解压后，将解压出的整个文件夹复制或者移动到
                <code>your sdk 路径/platforms</code>文件夹，然后打开SDK Manager，打开
                <code>Tools(工具)</code>菜单选择
                <code>Options(选项)</code>菜单项打开Android SDK Manager Setting对话框，点击
                <code>Clear Cache(清除缓存)</code>按钮，然后重启Eclipse(或Android Studio)和SDK Manager。</p>

            <table>
                <thead>
                    <tr>
                        <th align="left">系统版本号</th>
                        <th align="center">Windows</th>
                        <th align="center">Mac OSX</th>
                        <th align="center">Linux</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">android 5.0</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1i33Puo1">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1o6v7E2I">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1o6v7E2I">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android L Rev3</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1u8dhc">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1jG1duN8">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1jG1duN8">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android L</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1i3tDDvZ">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1ntHmhYx">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1ntHmhYx">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android 4.4W</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1eYPGE">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1nt5GKWh">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1nt5GKWh">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android 4.4.2</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1eQf8ZgI">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1jeRGM">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1jeRGM">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android 4.3</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1o65bfV8">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1bn1tNm3">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1bn1tNm3">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android 4.2.2</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1mgICw9E">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1pJJSlfl">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1pJJSlfl">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android 4.1.2</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1nt3bpI5">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1kTA6V8z">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1kTA6V8z">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android 4.0.3</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1pJoegpd">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1jGzdDxc">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1jGzdDxc">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android 4.0</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1c0H6Ld2">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1hqwzPTa">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1hqwzPTa">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android 3.2</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1jGLvX6A">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1qWqH9Q8">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1qWqH9Q8">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android 3.1</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1pJ0naTP">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1jG62PSy">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1jG62PSy">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android 3.0</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1pJ0naTP">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1bn2Duub">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1bn2Duub">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android 2.3.3</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1ngubc">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1jGge2bk">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1jGge2bk">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android 2.2</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1qW8YzY8">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1ntmJVmD">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1ntmJVmD">下载</a>
                        </td>
                    </tr>
                </tbody>
            </table>

            <h4 id="sdk-system-images">
                <a name="sdk-system-images" class="anchor" href="#sdk-system-images">
                    <span class="octicon octicon-link"></span>
                </a>SDK System images</h4>

            <p>这是在创建模拟器时需要的system image，也就是在创建模拟器时
                <code>CPU/ABI</code>项需要选择的，下载并解压后，将解压出的整个文件夹复制或者移动到
                <code>your sdk 路径/system-images</code>文件夹下即可， 如果没有
                <code>system-images</code>目录就先创建此文件夹，然后打开SDK Manager，打开
                <code>Tools(工具)</code>菜单选择
                <code>Options(选项)</code>菜单项打开Android SDK Manager Setting对话框，点击
                <code>Clear Cache(清除缓存)</code>按钮，然后重启Eclipse(或Android Studio)和SDK Manager。</p>

            <table>
                <thead>
                    <tr>
                        <th align="left">系统版本号</th>
                        <th align="center">Windows</th>
                        <th align="center">Mac OSX</th>
                        <th align="center">Linux</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">android 5.0</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1ntwpDQL">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1D7glC">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1D7glC">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android L</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1hqIcqhA">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1ntFQlRV">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1ntFQlRV">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android 4.4W</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1mgJVZfE">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1GmAE6">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1GmAE6">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android 4.4.2</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1i3Jwhed">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1qW0QWdm">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1qW0QWdm">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android 4.3</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1guLaQ">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1pJPp6dX">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1pJPp6dX">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android 4.2.2</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1pJO99hD">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1kTyZo27">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1kTyZo27">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android 4.1.2</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1nMr4E">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1kT2xdxd">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1kT2xdxd">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android 4.0.3</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1i3Fsx6H">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1gdnCh2b">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1gdnCh2b">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android 4.0</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1gd3lhYF">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1hqoWcNM">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1hqoWcNM">下载</a>
                        </td>
                    </tr>
                </tbody>
            </table>

            <h4 id="googlemap-apis-sdk">
                <a name="googlemap-apis-sdk" class="anchor" href="#googlemap-apis-sdk">
                    <span class="octicon octicon-link"></span>
                </a>GoogleMap APIs SDK</h4>

            <p>这是GoogleMap APIs SDK，下载并解压后，将解压出的整个文件夹复制或者移动到
                <code>your sdk 路径/add-ons</code>文件夹下，然后打开SDK Manager，打开
                <code>Tools(工具)</code>菜单选择
                <code>Options(选项)</code>菜单项打开Android SDK Manager Setting对话框，点击
                <code>Clear Cache(清除缓存)</code>按钮，然后重启Eclipse(或Android Studio)和SDK Manager。</p>

            <table>
                <thead>
                    <tr>
                        <th align="left">系统版本号</th>
                        <th align="center">Windows</th>
                        <th align="center">Mac OSX</th>
                        <th align="center">Linux</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">android 4.4.2</td>
                        <td align="center">
                            <a href="http://pan.baidu.com/s/1bno0mFt">下载ARM版</a>  <a href="http://pan.baidu.com/s/1jGgKyZc">下载x86版</a>
                        </td>
                        <td align="center">
                            <a href="http://pan.baidu.com/s/1bngsIkB">下载ARM版</a>  <a href="http://pan.baidu.com/s/1eQDwCpG">下载x86版</a>
                        </td>
                        <td align="center">
                            <a href="http://pan.baidu.com/s/1bngsIkB">下载ARM版</a>  <a href="http://pan.baidu.com/s/1eQDwCpG">下载x86版</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android 4.3</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1bnb9at5">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1gdJ0mqR">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1gdJ0mqR">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android 4.2.2</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1jGl4hZw">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1dDmurr7">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1dDmurr7">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android 4.1.2</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1ntK9Urf">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1mgIAcpa">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1mgIAcpa">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android 4.0.3</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1bnEiHiB">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1hqBWAIo">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1hqBWAIo">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android 4.0</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1gd68WtP">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1hqBWAIo">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1hqBWAIo">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android 3.2</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1o6Dgtse">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1gdf49Jt">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1gdf49Jt">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android 3.1</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1o6Dgtse">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1jGBS4rO">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1jGBS4rO">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android 3.0</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1c0CKIFA">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1c0iY68w">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1c0iY68w">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android 2.3.3</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1hqHwsHA">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1dDvhHOt">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1dDvhHOt">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android 2.2</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1qWJNPyk">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1eQEc8SU">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1eQEc8SU">下载</a>
                        </td>
                    </tr>
                </tbody>
            </table>

            <h4 id="google-glass-sdk">
                <a name="google-glass-sdk" class="anchor" href="#google-glass-sdk">
                    <span class="octicon octicon-link"></span>
                </a>Google Glass SDK</h4>

            <p>这是GDK，下载并解压后，将解压出的整个文件夹复制或者移动到
                <code>your sdk 路径/add-ons</code>文件夹下，然后打开SDK Manager，打开
                <code>Tools(工具)</code>菜单选择
                <code>Options(选项)</code>菜单项打开Android SDK Manager Setting对话框，点击
                <code>Clear Cache(清除缓存)</code>按钮，然后重启Eclipse(或Android Studio)和SDK Manager。</p>

            <table>
                <thead>
                    <tr>
                        <th align="left">系统版本</th>
                        <th align="center">Windows</th>
                        <th align="center">Mac OSX</th>
                        <th align="center">Linux</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">android 4.4.2</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1fENeu">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1eQpGaA2">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1eQpGaA2">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">android 4.0.3</td>
                        <td align="center"></td>
                        <td align="center"><a href="http://pan.baidu.com/s/1hqikzUs">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="google-tv-addon">
                <a name="google-tv-addon" class="anchor" href="#google-tv-addon">
                    <span class="octicon octicon-link"></span>
                </a>Google TV Addon</h4>

            <p>这是Google TV Addon，下载并解压后，将解压出的整个文件夹复制或者移动到
                <code>your sdk 路径/add-ons</code>文件夹，然后打开SDK Manager，打开
                <code>Tools(工具)</code>菜单选择
                <code>Options(选项)</code>菜单项打开Android SDK Manager Setting对话框，点击
                <code>Clear Cache(清除缓存)</code>按钮，然后重启Eclipse(或Android Studio)和SDK Manager。</p>

            <table>
                <thead>
                    <tr>
                        <th align="left">系统版本</th>
                        <th align="center">Windows</th>
                        <th align="center">Mac OSX</th>
                        <th align="center">Linux</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">android 3.2</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1qWLPFfm">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1eQFy1KA">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1eQFy1KA">下载</a>
                        </td>
                    </tr>
                </tbody>
            </table>

            <h4 id="android-framework-source-code">
                <a name="android-framework-source-code" class="anchor" href="#android-framework-source-code">
                    <span class="octicon octicon-link"></span>
                </a>Android Framework Source Code</h4>

            <p>这是Android Framework Source Code，下载并解压后，将解压出的整个文件夹复制或者移动到
                <code>your sdk 路径/sources</code>文件夹下，然后重启Eclipse(或Android Studio)，这样当你在Eclipse里面按住
                <code>Ctrl</code>键点击某个系统类时就可以打开该类的源码文件查看源码了。</p>

            <table>
                <thead>
                    <tr>
                        <th align="left">系统版本</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1dD5Z1Hf">android 5.0</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1eQf6F0Q">android 4.4W</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1hqGGrVA">android 4.4.2</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1pJI3YrD">android 4.3</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1qWlXS9u">android 4.2.2</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1qWv1spm">android 4.1.2</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1jGGCpuu">android 4.0.3</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1o61AZwQ">android 4.0</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1pJt14En">android 3.0</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1eQekIPW">android 2.3.3</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1bny9E2b">android 2.2</a>
                        </td>
                    </tr>
                </tbody>
            </table>

            <h4 id="android-sdk-extras">
                <a name="android-sdk-extras" class="anchor" href="#android-sdk-extras">
                    <span class="octicon octicon-link"></span>
                </a>Android SDK Extras</h4>

            <p>包含
                <code>Android Support Library</code>、
                <code>Google Cloud Messaging for Android Library</code>、
                <code>Google Play services</code>、
                <code>Google Play services for fit preview</code>、
                <code>Google Play services for Froyo</code>、
                <code>Google Play APK Expansion Library</code>、
                <code>Google Play Billing Library</code>、
                <code>Google Play Licensing Library</code>等，下载解压后将解压出的整个文件夹复制或者移动到
                <code>your sdk</code>根目录下下，如果已经存在
                <code>extras</code>文件夹就替换掉。</p>

            <table>
                <thead>
                    <tr>
                        <th align="center">版本号</th>
                    </tr>
                </thead>
                <tbody>
                	<tr>
                        <td align="center"><a href="http://pan.baidu.com/s/1kTmlB9d">21.0.3</a>
                        </td>
                    </tr>
                	<tr>
                        <td align="center"><a href="http://pan.baidu.com/s/1mgso8Y0">21.0.2</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center"><a href="http://pan.baidu.com/s/1o6v78Lk">21</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center"><a href="http://pan.baidu.com/s/1eQIMXMy">20</a>
                        </td>
                    </tr>
                </tbody>
            </table>

            <h4 id="support-library">
                <a name="support-library" class="anchor" href="#support-library">
                    <span class="octicon octicon-link"></span>
                </a>Support Library</h4>

            <p>包含supportive、v7和v13，下载解压后将解压出的整个文件夹复制或者移动到
                <code>your sdk 路径/extras</code>下，然后打开SDK Manager，打开
                <code>Tools(工具)</code>菜单选择
                <code>Options(选项)</code>菜单项打开Android SDK Manager Setting对话框，点击
                <code>Clear Cache(清除缓存)</code>按钮，然后重启Eclipse(或Android Studio)和SDK Manager。</p>

            <table>
                <thead>
                    <tr>
                        <th align="center">版本号</th>
                    </tr>
                </thead>
                <tbody>
                	<tr>
                        <td align="center"><a href="http://pan.baidu.com/s/1ntsoeE1">21.0.3</a>
                        </td>
                    </tr>
                	<tr>
                        <td align="center"><a href="http://pan.baidu.com/s/1kTzIkYV">21.0.2</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center"><a href="http://pan.baidu.com/s/1o6MBWIu">21</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center"><a href="http://pan.baidu.com/s/1o6OBlR8">20</a>
                        </td>
                    </tr>
                </tbody>
            </table>

            <h4 id="sdk-samples">
                <a name="sdk-samples" class="anchor" href="#sdk-samples">
                    <span class="octicon octicon-link"></span>
                </a>SDK Samples</h4>

            <p>这是Android SDK自带的示例代码，下载并解压后，将解压出的整个文件夹复制或者移动到
                <code>your sdk 路径/samples</code>文件夹下，然后重启Eclipse(或Android Studio)。 。
            </p>

            <table>
                <thead>
                    <tr>
                        <th align="left">系统版本</th>
                    </tr>
                </thead>
                <tbody>
                	<tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1dDD19XB">android 21</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1gdpEan5">android L</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1ntLVN9B">android 4.4W</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1dDeSKt7">android 4.4.2</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1pJHicjx">android 4.3</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1hqGavMc">android 4.2.2</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1eYPL8">android 4.1.2</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1i3mScXv">android 4.0.3</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1kTiKqZP">android 4.0</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1eQpafgI">android 3.2</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1haIPw">android 3.1</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1ntx9qFR">android 3.0</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1hqiQw1Q">android 2.3.3</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1ntv7wut">android 2.2</a>
                        </td>
                    </tr>
                </tbody>
            </table>

            <h4 id="ndk">
                <a name="ndk" class="anchor" href="#ndk">
                    <span class="octicon octicon-link"></span>
                </a>NDK</h4>
			<p>C/C++开发Android应用工具包,<code>Linux/Mac OS X 下NDK r10c</code>的安装方法请戳[这里](<a href="https://github.com/inferjay/AndroidDevTools/wiki/Installing-the-NDK-On-Linux-and-Mac-OS-X-(Darwin)">https://github.com/inferjay/AndroidDevTools/wiki/Installing-the-NDK-On-Linux-and-Mac-OS-X-(Darwin)</a></p>
            
			<table>
			    <thead>
			        <tr>
			            <th align="left">版本号</th>
			            <th align="center">Windows</th>
			            <th align="center">Mac OSX</th>
			            <th align="center">Linux</th>
			        </tr>
			    </thead>
			    <tbody>
			    		<tr>
			            <td align="left">ndk-r10d</td>
			            <td align="center">
			                <a href="http://pan.baidu.com/s/1yc9BK">32位</a> <a href="http://pan.baidu.com/s/1dDGTrk1">64位</a>
			            </td>
			            <td align="center">
			                <a href="http://pan.baidu.com/s/1hqtg8Qg">32位</a> <a href="http://pan.baidu.com/s/1c0En1Uo">64位</a>
			            </td>
			            <td align="center">
			                <a href="http://pan.baidu.com/s/1ntkOWEP">32位</a> <a href="http://pan.baidu.com/s/1cxPFK">64位</a>
			            </td>
			        </tr>
			        <tr>
			            <td align="left">ndk-r10c</td>
			            <td align="center">
			                <a href="http://pan.baidu.com/s/1bnGnKkB">32位</a> <a href="http://pan.baidu.com/s/1ntmhjUL">64位</a>
			            </td>
			            <td align="center">
			                <a href="http://pan.baidu.com/s/1i37Ud8L">32位</a> <a href="http://pan.baidu.com/s/1eQ08GOa">64位</a>
			            </td>
			            <td align="center">
			                <a href="http://pan.baidu.com/s/1c0o11wk">32位</a> <a href="http://pan.baidu.com/s/1c0tljk0">64位</a>
			            </td>
			        </tr>
			        <tr>
			            <td align="left">ndk64-r10</td>
			            <td align="center">
			                <a href="http://pan.baidu.com/s/1qW0RtzI">32位</a> <a href="http://pan.baidu.com/s/1ntypDpf">64位</a>
			            </td>
			            <td align="center">
			                <a href="http://pan.baidu.com/s/1o6G44Eu">32位</a> <a href="http://pan.baidu.com/s/1gd7pvJ9">64位</a>
			            </td>
			            <td align="center">
			                <a href="http://pan.baidu.com/s/1hql8AIo">32位</a> <a href="http://pan.baidu.com/s/1dDreuPz">64位</a>
			            </td>
			        </tr>
			        <tr>
			            <td align="left">ndk32-r10</td>
			            <td align="center">
			                <a href="http://pan.baidu.com/s/1bnB1o1T">32位</a> <a href="http://pan.baidu.com/s/1gdmW6cj">64位</a>
			            </td>
			            <td align="center">
			                <a href="http://pan.baidu.com/s/1jGtBYyq">32位</a> <a href="http://pan.baidu.com/s/1gdADfaF">64位</a>
			            </td>
			            <td align="center">
			                <a href="http://pan.baidu.com/s/1V2Tg">32位</a> <a href="http://pan.baidu.com/s/1pJJQokV">64位</a>
			            </td>
			        </tr>
			        <tr>
			            <td align="left">ndk-r9d</td>
			            <td align="center">
			                <a href="http://pan.baidu.com/s/1dDxjl8t">32位</a> <a href="http://pan.baidu.com/s/1jGgecXw">64位</a>
			            </td>
			            <td align="center">
			                <a href="http://pan.baidu.com/s/1eQnDNEE">32位</a> <a href="http://pan.baidu.com/s/1i3l5L8T">64位</a>
			            </td>
			            <td align="center">
			                <a href="http://pan.baidu.com/s/1jGr9w4A">32位</a> <a href="http://pan.baidu.com/s/1sjAXS41">64位</a>
			            </td>
			        </tr>
			    </tbody>
			</table>
			<table>
			    <thead>
			        <tr>
			            <th align="left">Additional Download (32-, 64-bit)</th>
			            <th align="left">Package</th>
			        </tr>
			    </thead>
			    <tbody>
			        <tr>
			            <td align="left">r10 STL debug info</td>
			            <td align="left"><a href="http://pan.baidu.com/s/1xWgUE">android-ndk-r10-cxx-stl-libs-with-debug-info.zip</a>
			            </td>
			        </tr>
			        <tr>
			            <td align="left">r9 STL debug info</td>
			            <td align="left"><a href="http://pan.baidu.com/s/1c0EMn8O">android-ndk-r9-cxx-stl-libs-with-debug-info.zip</a>
			            </td>
			        </tr>
			    </tbody>
			</table>

            <h4 id="android-l-preview-system-image">
                <a name="android-l-preview-system-image" class="anchor" href="#android-l-preview-system-image">
                    <span class="octicon octicon-link"></span>
                </a>Android L Preview System Image</h4>

            <p>这个是Android L Preview系统的刷机镜像。</p>

            <table>
                <thead>
                    <tr>
                        <th align="center">设备</th>
                        <th align="center">下载</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="center">Nexus 5 (GSM/LTE) "hammerhead"</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1kTsnxsF">hammerhead-lpv79-preview-ac1d8a8e.tgz</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center">Nexus 7 (Wifi) "razor"</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1mgn1CyG">razor-lpv79-preview-d0ddf8ce.tgz</a>
                        </td>
                    </tr>
                </tbody>
            </table>

            <h4 id="jdk">
                <a name="jdk" class="anchor" href="#jdk">
                    <span class="octicon octicon-link"></span>
                </a>JDK</h4>

            <table>
                <thead>
                    <tr>
                        <th align="center">版本号</th>
                        <th align="center">Windows</th>
                        <th align="center">Mac OSX</th>
                        <th align="center">Linux</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="center">1.8 u5</td>
                        <td align="center">
                            <a href="http://pan.baidu.com/s/1bn2CVIB">32位</a>  <a href="http://pan.baidu.com/s/1eQtJyGq">64位</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1pJkD78R">64位</a>
                        </td>
                        <td align="center">
                            <a href="http://pan.baidu.com/s/1o64s0pc">32位</a>  <a href="http://pan.baidu.com/s/1jG3KBjg">64位</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center">1.7 u60</td>
                        <td align="center">
                            <a href="http://pan.baidu.com/s/1nt5a3jj">32位</a>  <a href="http://pan.baidu.com/s/1o61AAHc">64位</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1nt0qGfn">64位</a>
                        </td>
                        <td align="center">
                            <a href="http://pan.baidu.com/s/1eQd4wVK">32位</a>  <a href="http://pan.baidu.com/s/1jGzGQLw">64位</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center">1.6 u45</td>
                        <td align="center">
                            <a href="http://pan.baidu.com/s/1o67aooM">32位</a>  <a href="http://pan.baidu.com/s/1dDmtSZJ">64位</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1hqpB7Nm">64位</a>
                        </td>
                        <td align="center">
                            <a href="http://pan.baidu.com/s/1pJJj5Ib">32位</a>  <a href="http://pan.baidu.com/s/1dDck3O9">64位</a>
                        </td>
                    </tr>
                </tbody>
            </table>
						<h4 id="adt-bundle">
                <a name="adt-bundle" class="anchor" href="#adt-bundle">
                    <span class="octicon octicon-link"></span>
                </a>ADT Bundle</h4>

            <p>ADT Bundle包含了Eclipse、ADT插件和SDK Tools，是已经集成好的IDE，只需安装好Jdk即可开始开发，推荐初学者下载ADT Bundle，不用再折腾开发环境。</p>

            <table>
                <thead>
                    <tr>
                        <th align="center">版本号</th>
                        <th align="center">Windows</th>
                        <th align="center">Mac OSX</th>
                        <th align="center">Linux</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="center">23.0.2</td>
                        <td align="center">
                            <a href="http://pan.baidu.com/s/1dDGM8oD">32位</a>  <a href="http://pan.baidu.com/s/1mgn2dOs">64位</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1o6OBIHG">64位</a>
                        </td>
                        <td align="center">
                            <a href="http://pan.baidu.com/s/1GmIsQ">32位</a>  <a href="http://pan.baidu.com/s/1EQMT4">64位</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center">23.0.0</td>
                        <td align="center">
                            <a href="http://pan.baidu.com/s/1i39mvY1">32位</a>  <a href="http://pan.baidu.com/s/1o65ExPS">64位</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1hqvHkry">64位</a>
                        </td>
                        <td align="center">
                            <a href="http://pan.baidu.com/s/1mgoh41q">32位</a>  <a href="http://pan.baidu.com/s/1qWJh4wk">64位</a>
                        </td>
                    </tr>
                </tbody>
            </table>
            
            <h4 id="adt-plugin">
                <a name="adt-plugin" class="anchor" href="#adt-plugin">
                    <span class="octicon octicon-link"></span>
                </a>ADT Plugin</h4>

            <p>离线安装ADT插件请戳
                <a href="https://github.com/inferjay/AndroidDevTools/wiki/%E9%A6%96%E9%A1%B5">
                    <strong>项目wiki</strong>
                </a>
            </p>

            <table>
                <thead>
                    <tr>
                        <th align="center">版本号</th>
                    </tr>
                </thead>
                <tbody>
                		<tr>
                        <td align="center"><a href="http://pan.baidu.com/s/1jGraNEQ">ADT-23.0.6</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center"><a href="http://pan.baidu.com/s/1i39UM7j">ADT-23.0.4</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center"><a href="http://pan.baidu.com/s/1hqJyLTi">ADT-23.0.3</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center"><a href="http://pan.baidu.com/s/1bnGkEvX">ADT-23.0.2</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center"><a href="http://pan.baidu.com/s/1sjArX7J">ADT-23.0.0</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center"><a href="http://pan.baidu.com/s/1jGMb5yQ">ADT-22.6.3</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="center"><a href="http://pan.baidu.com/s/1pJ185Rl">AdT-22.6.1</a>
                        </td>
                    </tr>
                </tbody>
            </table>

            <h4 id="gradle">
                <a name="gradle" class="anchor" href="#gradle">
                    <span class="octicon octicon-link"></span>
                </a>Gradle</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">版本号</th>
                    </tr>
                </thead>
                <tbody>
                	<tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1nt9jd25">gradle-2.2.1-all.zip</a>
                        </td>
                    </tr>
                	<tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1CTrBK">gradle-2.2-all.zip</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1bnF6jV5">gradle-2.1-all.zip</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1mgFTN7a">gradle-2.0-all.zip</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1Gmlx8">gradle-1.12-all.zip</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1c0hCmdE">gradle-1.11-all.zip</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1qWtzaGW">gradle-1.10-all.zip</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1dDeSuXV">gradle-1.9-all.zip</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1o6Npqqe">gradle-1.8-all.zip</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1pJnvyWz">gradle-1.7-all.zip</a>
                        </td>
                    </tr>
                </tbody>
            </table>

            <h4 id="gradle-dependencies-configuration-generator">
                <a name="gradle-dependencies-configuration-generator" class="anchor" href="#gradle-dependencies-configuration-generator">
                    <span class="octicon octicon-link"></span>
                </a>Gradle Dependencies Configuration Generator</h4>

            <p><a href="http://gradleplease.appspot.com">Gradle, please</a>
            </p>
			
			<h4 id="version-control-tools">
                <a name="version-control-tools" class="anchor" href="#version-control-tools">
                    <span class="octicon octicon-link"></span>
                </a>版本控制工具</h4>

			<h5 id="git">
                <a name="git" class="anchor" href="#git">
                    <span class="octicon octicon-link"></span>
                </a>Git</h5>

            <table>
                <thead>
                    <tr>
                        <th align="center">版本号</th>
                        <th align="center">Windows</th>
                        <th align="center">Mac OSX</th>
                        <th align="center">Linux</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">Git-2.0.1</td>
                        <td align="center">
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1mgkM9BE">下载</a>
                        </td>
                        <td align="center"><a href="https://github.com/inferjay/AndroidDevTools/wiki/Download-for-Linux-and-Unix">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">Git-1.9.4</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1ntjy9N7">下载</a>
                        </td>
                        <td align="center">
                        </td>
                        <td align="center"><a href="https://github.com/inferjay/AndroidDevTools/wiki/Download-for-Linux-and-Unix">下载</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">Git-1.8.5.2</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1ntJWxeD">下载</a>
                        </td>
                        <td align="center"><a href="http://pan.baidu.com/s/1bncr1pX">下载</a>
                        </td>
                        <td align="center"><a href="https://github.com/inferjay/AndroidDevTools/wiki/Download-for-Linux-and-Unix">下载</a>
                        </td>
                    </tr>
                </tbody>
            </table>

			<h4 id="svn-plugin-for-eclipse">
                <a name="svn-plugin-for-eclipse" class="anchor" href="#svn-plugin-for-eclipse">
                    <span class="octicon octicon-link"></span>
                </a>SVN Plugin For Eclipse</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">版本号</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1mg2x4Xq">1.10.5</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1hqswoGs">1.8.22</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left"><a href="http://pan.baidu.com/s/1o60r6UA">1.6.18</a>
                        </td>
                    </tr>
                </tbody>
            </table>

            <h4 id="apk-decompile-tools">
                <a name="%E5%8F%8D%E7%BC%96%E8%AF%91%E5%B7%A5%E5%85%B7" class="anchor" href="#apk-decompile-tools">
                    <span class="octicon octicon-link"></span>
                </a>Apk反编译工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th align="center">简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">JEB Android Decompiler</td>
                        <td align="center"></td>
                        <td align="center"><a href="http://www.android-decompiler.com/index.php">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Virtuous Ten Studio</td>
                        <td align="center"></td>
                        <td align="center"><a href="http://virtuous-ten-studio.com">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Apk文件修改工具Root Tools</td>
                        <td align="center"></td>
                        <td align="center"><a href="https://github.com/Stericson/RootTools">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Dex文件反编译工具Dedexer</td>
                        <td align="center"></td>
                        <td align="center"><a href="http://dedexer.sourceforge.net">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">APK+Dex文件反编译及回编译工具</td>
                        <td align="center"></td>
                        <td align="center"><a href="http://idoog.me">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">android-apktool</td>
                        <td align="center"></td>
                        <td align="center"><a href="http://ibotpeaches.github.io/Apktool/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Onekey Decompile Apk]</td>
                        <td align="center"></td>
                        <td align="center"><a href="https://code.google.com/p/onekey-decompile-apk/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Baksmali</td>
                        <td align="center"></td>
                        <td align="center"><a href="https://code.google.com/p/smali/downloads/detail?name=baksmali">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Smali</td>
                        <td align="center"></td>
                        <td align="center"><a href="https://code.google.com/p/smali/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">AXMLPrinter2</td>
                        <td align="center"></td>
                        <td align="center"><a href="https://android4me.googlecode.com/files/AXMLPrinter2.jar">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">JAD Java Decompiler</td>
                        <td align="center"></td>
                        <td align="center"><a href="http://varaneckas.com/jad/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">JD-GUI Decompiler</td>
                        <td align="center"></td>
                        <td align="center"><a href="http://">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">XJad V2.2</td>
                        <td align="center"></td>
                        <td align="center"><a href="http://files.cnblogs.com/arix04/XJad_V2.2.rar">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Android APK Decompiler</td>
                        <td align="center">在线反编译工具</td>
                        <td align="center"><a href="http://www.decompileandroid.com/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">SmaliViewer</td>
                        <td align="center"><p>是一款免费的APK分析软件，无论从分析的深</p><p>度还是广度来看，都是一款能够满足用户需求</p><p>的产品，使您在APK分析的过程中，更加得心应手。</p></td>
                        <td align="center"><a href="http://blog.avlyun.com/wp-content/uploads/2014/04/SmaliViewer.zip">下载</a>
                        </td>
                        <td align="center"><a href="http://blog.avlyun.com/show/《sv用户指南》/">使用指南</a></td>
                    </tr>
                    <tr>
                        <td align="left">Android逆向助手</td>
                        <td align="center"><p>Android逆向助手是一功能强大的逆向辅助软件。</p><p>该软件可以帮助用户来进行apk反编译打包签名；</p><p>dex/jar互转替换提取修复；so反编译；</p><p>xml、txt加密；字符串编码等等，操作简单，</p><p>只需要直接将文件拖放到源和目标文件。</p></td>
                        <td align="center"><a href="http://enjoycode.info/uploads/Androidnxzs.zip">下载</a>
                        </td>
                        <td align="center"><a href="http://www.sanwho.com/620.html">使用指南</a></td>
                    </tr>
                    <tr>
                        <td align="left">Android Killer</td>
                        <td align="center"><Android Killer 是一款可视化的安卓应用逆向工具，<br/>集Apk反编译、Apk打包、Apk签名，编码互转，<br/>ADB通信（应用安装-卸载-运行-设备文件管理）等特色<br/>功能于一 身，支持logcat日志输出，语法高亮，<br/>基于关键字（支持单行代码或多行代码段）项目内搜索，<br/>可自定义外部工具；吸收融汇多种工具功能与特点，<br/>打造一站 式逆向工具操作体验，大大简化了用户在<br/>安卓应用/游戏修改过程中的各类繁琐工作。</td>
                        <td align="center"><a href="http://www.pd521.com/thread-136-1-1.html">下载1</a><br/><a href="http://pan.baidu.com/share/home?uk=4099707276#category/type=6">下载2</a>
                        </td>
                        <td align="center"><a href="http://www.pd521.com/thread-509-1-1.html">使用指南</a></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="security-tools">
                <a name="%E5%AE%89%E5%85%A8%E5%B7%A5%E5%85%B7" class="anchor" href="#security-tools">
                    <span class="octicon octicon-link"></span>
                </a>安全工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">APKfuscator</td>
                        <td align="center"><a href="https://github.com/strazzere/APKfuscator">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">ApkAnalyser</td>
                        <td align="center"><a href="https://github.com/sonyxperiadev/ApkAnalyser/downloads">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">AppXplore</td>
                        <td align="center"><a href="https://play.google.com/store/apps/details?id=com.sonyericsson.androidapp.AppExplore&amp;feature=search_result#?t=W251bGwsMSwxLDEsImNvbS5zb255ZXJpY3Nzb24uYW5kcm9pZGFwcC5BcHBFeHBsb3JlIl0.">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Android analysis framework</td>
                        <td align="center"><a href="http://www.dexlabs.org">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Androguard</td>
                        <td align="center"><a href="https://code.google.com/p/androguard/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Droidbox</td>
                        <td align="center"><a href="https://code.google.com/p/droidbox/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">dsploit</td>
                        <td align="center"><a href="https://github.com/evilsocket/dsploit">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Androwarn</td>
                        <td align="center"><a href="https://github.com/maaaaz/androwarn">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Anubis</td>
                        <td align="center"><a href="http://anubis.iseclab.org">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Drozer</td>
                        <td align="center"><a href="https://www.mwrinfosecurity.com/products/drozer/community-edition/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">VirusTotal</td>
                        <td align="center"><a href="https://www.virustotal.com">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">GDB for Android</td>
                        <td align="center"><a href="http://gnutoolchains.com/android/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">VisualGDB</td>
                        <td align="center"><a href="http://visualgdb.com/?features=android">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>
						<h4>
								<a id="search-tools" class="anchor" href="#%E6%90%9C%E7%B4%A2%E5%B7%A5%E5%85%B7" aria-hidden="true">
									<span class="octicon octicon-link"></span></a>搜索工具
						</h4>
						<table>
							<thead>
								<tr>
								<th align="left">名称</th>
								<th align="left">简介</th>
								<th align="center">下载地址</th>
								<th align="center">使用教程</th>
								</tr>
							</thead>
							<tbody>
								<tr>
								<td align="left">Structural Java Exception Search</td>
								<td align="left">Java异常搜索工具</td>
								<td align="center"><a href="http://www.brainleg.com/search">下载</a></td>
								<td align="center"></td>
								</tr>
							</tbody>
						</table>
						<h4>
							<a id="debug-tools" class="anchor" href="#debug%E8%B0%83%E8%AF%95%E5%B7%A5%E5%85%B7" aria-hidden="true">
								<span class="octicon octicon-link"></span>
							</a>Debug调试工具
						</h4>
						<table>
								<thead>
									<tr>
									<th align="left">名称</th>
									<th align="left">简介</th>
									<th align="center">下载地址</th>
									<th align="center">使用教程</th>
									</tr>
								</thead>
								<tbody>
									<tr>
									<td align="left">Stetho</td>
									<td align="left">Stetho 是Facebook推出的Android 调试平台，基于 </br>Chrome Developer Tools ，调试网络请求方面特别方便。</td>
									<td align="center"><a href="https://github.com/facebook/stetho">下载</a></td>
									<td align="center"><a href="http://facebook.github.io/stetho/">教程</a></td>
									</tr>
									<tr>
									<td align="left">Augmented Traffic Control</td>
									<td align="left">Facebook宣布开源移动网络测试工具ATC，该工具支持利用</br>Wi-Fi网络模拟2G、2.5G、3G以及LTE 4G移动网络</br>环境，让测试工程师们能够快速对智能手机和App在</br>不同国家地区和应用环境下的性能表现进行测试。</td>
									<td align="center"><a href="https://github.com/facebook/augmented-traffic-control">下载</a></td>
									<td align="center"></td>
									</tr>
								</tbody>
						</table>
						<h4 id="api-test-tools">
                <a name="" class="anchor" href="#api-test-tools">
                    <span class="octicon octicon-link"></span>
                </a>Api测试工具</h4>
						<table>
								<thead>
									<tr>
									<th align="left">名称</th>
									<th align="left">简介</th>
									<th align="center">下载地址</th>
									<th align="center">使用教程</th>
									</tr>
								</thead>
								<tbody>
									<tr>
									<td align="left">bat</td>
									<td align="left">一个用Go写的命令行API测试利器，支持文件下载，<br/>文件上传，支持Linux的pipe方式，总之就是炫酷。</td>
									<td align="center"><a href="https://github.com/astaxie/bat">下载</a></td>
									<td align="center"><a href="https://github.com/astaxie/bat#installation">教程</a></td>
								</tbody>
						</table>
						
            <h4 id="eclipse-android-studio-idea-plugin">
                <a name="eclipseandroid-studioidea%E6%8F%92%E4%BB%B6" class="anchor" href="#eclipse-android-studio-idea-plugin">
                    <span class="octicon octicon-link"></span>
                </a>Eclipse/Android Studio/IDEA插件</h4>

            <h5 id="eclipse-plugin">
                <a name="eclipse" class="anchor" href="#eclipse-plugin">
                    <span class="octicon octicon-link"></span>
                </a>Eclipse插件</h5>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">SVN</td>
                        <td align="center"><a href="http://pan.baidu.com/s/1sjqamOP">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Genymobile模拟器</td>
                        <td align="center"><a href="http://genymotion.com/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Memory-Analyzer-Tools</td>
                        <td align="center"><a href="http://download.eclipse.org/mat/1.4/update-site/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Droidinspector</td>
                        <td align="center"><a href="http://www.sriramramani.com/droidinspector/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">SQLiteManager</td>
                        <td align="center"><a href="https://dl.dropboxusercontent.com/u/91846918/sqlite%20manager/com.questoid.sqlitemanager_1.0.0.jar">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Color Theme</td>
                        <td align="center"><a href="http://eclipsecolorthemes.org/?view=plugin">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">RoboVM</td>
                        <td align="center"><a href="http://www.robovm.org">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Newrelic</td>
                        <td align="center"><a href="https://download.newrelic.com/android_agent/eclipse">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h5 id="android-studio-idea-plugin">
                <a name="android-studioidea" class="anchor" href="#android-studio-idea-plugin">
                    <span class="octicon octicon-link"></span>
                </a>Android Studio/IDEA插件</h5>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">Android Resource Resizer Plugin</td>
                        <td align="center"><a href="https://github.com/walmyrcarvalho/android-resource-resizer">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Gradle Dependencies Helper Plugin</td>
                        <td align="center"><a href="https://github.com/ligi/GradleDependenciesHelperPlugin">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Android Parcelable code generation Plugin</td>
                        <td align="center"><a href="https://github.com/mcharmas/android-parcelable-intellij-plugin">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Android Holo Colors IDEA Plugin</td>
                        <td align="center"><a href="http://www.sriramramani.com/droidinspector/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Android Toolbox Plugin</td>
                        <td align="center"><a href="https://github.com/idamobile/android-toolbox-plugin">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Android Gradle Sign Plugin</td>
                        <td align="center"><a href="https://github.com/alexvasilkov/AndroidGradleSignPlugin">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Android Permissions Usage Plugin</td>
                        <td align="center"><a href="https://github.com/RomainPiel/AndroidPermissionsUsage">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Android Helper Plugin</td>
                        <td align="center"><a href="https://github.com/eunjae-lee/AndroidHelper">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Android Studio Prettify Plugin</td>
                        <td align="center"><a href="https://github.com/Haehnchen/idea-android-studio-plugin">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">IDEA ADB Plugin</td>
                        <td align="center"><a href="https://github.com/pbreault/adb-idea">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Otto Intellij Plugin</td>
                        <td align="center"><a href="https://github.com/square/otto-intellij-plugin">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Dagger intellij Plugin</td>
                        <td align="center"><a href="https://github.com/square/dagger-intellij-plugin">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Gradle Gui Plugin</td>
                        <td align="center"><a href="https://github.com/gradle-archive/gradle-intellij-gui">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Android Studio Unit Test Plugin</td>
                        <td align="center"><a href="https://github.com/evant/android-studio-unit-test-plugin">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Android Layout ID Converter Plugin</td>
                        <td align="center"><a href="https://github.com/funnything/OffingHarbor">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">IDEA protobuf Plugin</td>
                        <td align="center"><a href="https://github.com/nnmatveev/idea-plugin-protobuf">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Simple Team Code Reviewer Plugin</td>
                        <td align="center"><a href="https://github.com/syllant/idea-plugin-revu">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Android XML Plugin</td>
                        <td align="center"><a href="https://github.com/mironov-nsk/AndroidXML">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">ADF Plugin</td>
                        <td align="center"><a href="https://github.com/tizionario/adf-intellijPlugin">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Java2smali Plugin</td>
                        <td align="center"><a href="https://github.com/ollide/intellij-java2smali">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">IDEA gitignore Plugin</td>
                        <td align="center"><a href="https://github.com/hsz/idea-gitignore">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">IDEA Background Image Plugin</td>
                        <td align="center"><a href="https://github.com/kimptoc/Intellij-IDEA-Plugin-Background-Image">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">IDEA Maven Plugin</td>
                        <td align="center"><a href="https://github.com/born2snipe/idea-plugin-maven-plugin">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Gradle GooglePlay Publisher Plugin</td>
                        <td align="center"><a href="https://github.com/Triple-T/gradle-play-publisher">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Drawable Selectors Generates Plugin</td>
                        <td align="center"><a href="https://github.com/inmite/android-selector-chapek">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Android Drawable Importer</td>
                        <td align="center"><a href="https://github.com/winterDroid/android-drawable-importer-intellij-plugin">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="android-res-themes-style-generator-tools">
                <a name="android%E8%B5%84%E6%BA%90themesstyle%E7%94%9F%E6%88%90%E5%B7%A5%E5%85%B7" class="anchor" href="#android-res-themes-style-generator-tools">
                    <span class="octicon octicon-link"></span>
                </a>Android资源/Themes/Style生成工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th align="left">简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">Android Asset Studio</td>
                        <td align="left"></td>
                        <td align="center"><a href="http://romannurik.github.io/AndroidAssetStudio/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Android Drawable Factory</td>
                        <td align="left"></td>
                        <td align="center"><a href="https://github.com/tizionario/AndroidDrawableFactory">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Android Action Bar Style Generator</td>
                        <td align="left"></td>
                        <td align="center"><a href="http://jgilfelt.github.io/android-actionbarstylegenerator">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Android Holo Colors Generator</td>
                        <td align="left"></td>
                        <td align="center"><a href="http://android-holo-colors.com">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Android Simple Nine-patch Generator</td>
                        <td align="left"></td>
                        <td align="center"><a href="http://romannurik.github.io/AndroidAssetStudio/nine-patches.html">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Android Device Frame Generator</td>
                        <td align="left"></td>
                        <td align="center"><a href="http://f2prateek.com/android-device-frame-generator/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="android-res-analysis-tools">
                <a name="android%E8%B5%84%E6%BA%90%E5%88%86%E6%9E%90%E5%B7%A5%E5%85%B7" class="anchor" href="#android-res-analysis-tools">
                    <span class="octicon octicon-link"></span>
                </a>Android资源分析工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th align="left">简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">Android Assets Viewer</td>
                        <td align="left"></td>
                        <td align="center"><a href="http://www.cellebellum.net/AndroidAssetsViewer/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="android-layout-parser-tools">
                <a name="android-layout-parser%E5%B7%A5%E5%85%B7" class="anchor" href="#android-layout-parser-tools">
                    <span class="octicon octicon-link"></span>
                </a>Android Layout Parser工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th align="left">简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">Android Layout Binder</td>
                        <td align="left"></td>
                        <td align="center"><a href="http://android.lineten.net/layout.php">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="android-content-provider-generator-tools">
                <a name="android-content-provider%E4%BB%A3%E7%A0%81%E7%94%9F%E6%88%90%E5%B7%A5%E5%85%B7" class="anchor" href="#android-content-provider-generator-tools">
                    <span class="octicon octicon-link"></span>
                </a>Android Content Provider代码生成工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th align="left">简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">Content Provider Code Generator</td>
                        <td align="left"></td>
                        <td align="center"><a href="https://github.com/BoD/android-contentprovider-generator">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="android-fragment-code-generator-tools">
                <a name="android-fragment-code-generator%E4%BB%A3%E7%A0%81%E7%94%9F%E6%88%90%E5%B7%A5%E5%85%B7" class="anchor" href="#android-fragment-code-generator-tools">
                    <span class="octicon octicon-link"></span>
                </a>Android Fragment Code Generator代码生成工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th align="left">简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">Android Fragment Code Generator</td>
                        <td align="left"></td>
                        <td align="center"><a href="http://techisfun.github.io/pages/android-fragment-generator/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="android-code-generator-tools">
                <a name="%E4%BB%A3%E7%A0%81%E7%94%9F%E6%88%90%E5%B7%A5%E5%85%B7" class="anchor" href="#android-code-generator-tools">
                    <span class="octicon octicon-link"></span>
                </a>代码生成工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th align="left">简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">Android KickstartR</td>
                        <td align="left">AndroidKickstartR帮助您快速创建
                            <br>Android应用程序并使用最流行的库进行配置。
                            <br>它创建和配置你的项目给你。只专注于代码!</td>
                        <td align="center"><a href="http://androidkickstartr.com">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Android Button Maker</td>
                        <td align="left">Android Button Maker是一个在线生成Android应用按钮代码的工具。
                            <br>Android的API提供可绘制资源，其中的XML文件定义的几何形状，包括颜色，边框和梯度。
                            <br>这些按钮是在shape drawable XML代码基础上产生的相比通常的PNG按钮加载速度更快。
                            <br>您可以在设置面板中自定义按钮的属性和获得源代码。</td>
                        <td align="center"><a href="http://angrytools.com/android/button/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">DroidDraw</td>
                        <td align="left"></td>
                        <td align="center"><a href="https://code.google.com/p/droiddraw/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
												<td align="left">Android SVG to VectorDrawable</td>
												<td align="left">一个可以将SVG图片转换为Vector Drawable xml文件的在线工具。</td>
												<td align="center"><a href="http://inloop.github.io/svg2android/">下载</a></td>
												<td align="center"></td>
										</tr>
                </tbody>
            </table>

            <h4 id="android-native-dev-tools">
                <a name="android-native%E5%BC%80%E5%8F%91%E5%B7%A5%E5%85%B7" class="anchor" href="#android-native-dev-tools">
                    <span class="octicon octicon-link"></span>
                </a>Android Native开发工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">Android++</td>
                        <td></td>
                        <td align="center"><a href="http://android-plus-plus.com">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="android-test-tools">
                <a name="android%E6%B5%8B%E8%AF%95%E5%B7%A5%E5%85%B7" class="anchor" href="#android-test-tools">
                    <span class="octicon octicon-link"></span>
                </a>Android测试工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">Appurify</td>
                        <td></td>
                        <td align="center"><a href="http://appurify.com">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Monkey</td>
                        <td></td>
                        <td align="center"><a href="http://developer.android.com/intl/zh-cn/tools/help/monkey.html">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Testin</td>
                        <td></td>
                        <td align="center"><a href="http://testin.cn">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Spoon</td>
                        <td></td>
                        <td align="center"><a href="http://square.github.io/spoon/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Little Eye</td>
                        <td></td>
                        <td align="center"><a href="http://www.littleeye.co">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">易测云</td>
                        <td></td>
                        <td align="center"><a href="http://www.yiceyun.com">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Emmagee</td>
                        <td></td>
                        <td align="center"><a href="https://code.google.com/p/emmagee/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Apk View Tracer</td>
                        <td></td>
                        <td align="center"><a href="https://code.google.com/p/apk-view-tracer/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">APT</td>
                        <td>APT是一个Android平台高效性能测试组件，
                            <br>提供丰富实用的功能，适用于开发自测、
                            <br>定位性能瓶颈；
                            <br>测试人员完成性能基准测试、竞品对比测试。</td>
                        <td align="center"><a href="https://code.csdn.net/Tencent/apt">下载</a>
                        </td>
                        <td align="center"><a href="http://www.eoeandroid.com/thread-497380-1-1.html">教程</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">GT</td>
                        <td>GT（随身调）是APP的随身调测平台，它是直接运行在手机上的“集成调测环境”(IDTE, Integrated Debug&amp;Test Environment)。</td>
                        <td align="center"><a href="http://gt.tencent.com/index.html">下载</a>
                        </td>
                        <td align="center"><a href="http://gt.tencent.com/docs.html">教程</a>
                        </td>
                    </tr>
                    <tr>
                        <td align="left">Stetho</td>
                        <td>Stetho 是Facebook推出的Android 调试平台，基于 Chrome Developer Tools ，调试网络请求方面特别方便。</td>
                        <td align="center"><a href="http://facebook.github.io/stetho/">下载</a>
                        </td>
                        <td align="center"><a href="http://stormzhang.com/android/2015/03/05/android-debug-use-chrome/">教程</a>
                        </td>
                    </tr>
                </tbody>
            </table>

            <h4 id="multi-channel-apk-genterator-tools">
                <a name="android%E5%A4%9A%E6%B8%A0%E9%81%93%E6%89%93%E5%8C%85%E5%B7%A5%E5%85%B7" class="anchor" href="#multi-channel-apk-genterator-tools">
                    <span class="octicon octicon-link"></span>
                </a>Android多渠道打包工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">Umeng多渠道打包工具</td>
                        <td></td>
                        <td align="center"><a href="https://github.com/umeng/umeng-muti-channel-build-tool">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">AppTools具</td>
                        <td></td>
                        <td align="center"><a href="https://github.com/wubo/apptools">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">package_tool</td>
                        <td></td>
                        <td align="center"><a href="https://github.com/ahui2823/package_tool">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">RyApkTool</td>
                        <td></td>
                        <td align="center"><a href="http://blog.csdn.net/rydiy/article/details/7901564">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="android-log-collection-tools">
                <a name="android-bug%E6%97%A5%E5%BF%97%E6%94%B6%E9%9B%86%E5%B7%A5%E5%85%B7" class="anchor" href="#android-log-collection-tools">
                    <span class="octicon octicon-link"></span>
                </a>Android Bug日志收集工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">Crashlytics</td>
                        <td></td>
                        <td align="center"><a href="http://try.crashlytics.com">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">ACRA</td>
                        <td></td>
                        <td align="center"><a href="https://github.com/ACRA/acra">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">ChkBugReport</td>
                        <td></td>
                        <td align="center"><a href="https://github.com/sonyxperiadev/ChkBugReport">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Log Collector</td>
                        <td></td>
                        <td align="center"><a href="https://code.google.com/p/android-log-collector/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Android Crash Catcher</td>
                        <td></td>
                        <td align="center"><a href="https://github.com/netcook/crash-catcher">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="android-other-language-dev-tools">
                <a name="%E5%85%B6%E4%BB%96%E8%AF%AD%E8%A8%80%E5%BC%80%E5%8F%91android%E5%BA%94%E7%94%A8%E5%B7%A5%E5%85%B7" class="anchor" href="#android-other-language-dev-tools">
                    <span class="octicon octicon-link"></span>
                </a>其他语言开发Android应用工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">Xamarin</td>
                        <td></td>
                        <td align="center"><a href="http://xamarin.com">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Basic4android</td>
                        <td></td>
                        <td align="center"><a href="http://www.basic4ppc.com/index.html">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Scripting Layer</td>
                        <td></td>
                        <td align="center"><a href="https://code.google.com/p/android-scripting/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Ruby Rhodes</td>
                        <td>移动设备上的Ruby</td>
                        <td align="center"><a href="http://rhomobile.com">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">PHP for Android</td>
                        <td></td>
                        <td align="center"><a href="http://www.phpforandroid.net/doku.php">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Codename One</td>
                        <td></td>
                        <td align="center"><a href="http://www.codenameone.com/index.html">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Touchqode</td>
                        <td></td>
                        <td align="center"><a href="http://www.codenameone.com/index.html">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">App Inventor</td>
                        <td></td>
                        <td align="center"><a href="http://www.codenameone.com/index.html">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="adroid-sensors-simulate-tools">
                <a name="%E4%BC%A0%E6%84%9F%E5%99%A8%E6%A8%A1%E6%8B%9F%E5%B7%A5%E5%85%B7" class="anchor" href="#adroid-sensors-simulate-tools">
                    <span class="octicon octicon-link"></span>
                </a>传感器模拟工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">Sensor Simulator</td>
                        <td>独立的Java应用程序，它模拟传感器
                            <br>的数据并将它们传送到Android模拟器。</td>
                        <td align="center"><a href="http://www.openintents.org/en/node/23)">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="android-serial-dev-tools">
                <a name="android%E4%B8%B2%E5%8F%A3%E5%BC%80%E5%8F%91%E5%B7%A5%E5%85%B7" class="anchor" href="#android-serial-dev-tools">
                    <span class="octicon octicon-link"></span>
                </a>Android串口开发工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">Android Serialport Api</td>
                        <td></td>
                        <td align="center"><a href="https://code.google.com/p/android-serialport-api/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="img-size-handle-tools">
                <a name="%E5%9B%BE%E7%89%87%E5%B0%BA%E5%AF%B8%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7" class="anchor" href="#img-size-handle-tools">
                    <span class="octicon octicon-link"></span>
                </a>图片尺寸处理工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">9-Patch Resizer</td>
                        <td></td>
                        <td align="center"><a href="https://github.com/redwarp/9-Patch-Resizer">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="img-compress-tools">
                <a name="%E5%9B%BE%E7%89%87%E5%8E%8B%E7%BC%A9%E5%B7%A5%E5%85%B7" class="anchor" href="#img-compress-tools">
                    <span class="octicon octicon-link"></span>
                </a>图片压缩工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">OptiPNG</td>
                        <td></td>
                        <td align="center"><a href="http://optipng.sourceforge.net/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Pngcrush</td>
                        <td></td>
                        <td align="center"><a href="http://pmt.sourceforge.net/pngcrush/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">ImageOptim</td>
                        <td></td>
                        <td align="center"><a href="http://xamarin.com">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="android-res-clean-tools">
                <a name="%E8%B5%84%E6%BA%90%E6%B8%85%E7%90%86%E5%B7%A5%E5%85%B7" class="anchor" href="#android-res-clean-tools">
                    <span class="octicon octicon-link"></span>
                </a>资源清理工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">Android Lint</td>
                        <td></td>
                        <td align="center"><a href="http://tools.android.com/tips/lint">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Android Resource Cleaner</td>
                        <td></td>
                        <td align="center"><a href="https://code.google.com/p/android-resource-cleaner/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Android Unused Resources</td>
                        <td></td>
                        <td align="center"><a href="https://code.google.com/p/android-unused-resources/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Android Resource Remover</td>
                        <td></td>
                        <td align="center"><a href="https://github.com/KeepSafe/android-resource-remover">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="px-to-dp-convert-tools">
                <a name="px%E5%92%8Cdp%E8%BD%AC%E6%8D%A2%E8%AE%A1%E7%AE%97%E5%B7%A5%E5%85%B7" class="anchor" href="#px-to-dp-convert-tools">
                    <span class="octicon octicon-link"></span>
                </a>px和dp转换/计算工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">Android dp px Calculator</td>
                        <td></td>
                        <td align="center"><a href="http://labs.rampinteractive.co.uk/android_dp_px_calculator/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">dp px converter</td>
                        <td></td>
                        <td align="center"><a href="http://pixplicity.com/dp-px-converter/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">pixelcalc</td>
                        <td></td>
                        <td align="center"><a href="http://angrytools.com/android/pixelcalc/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">androidpixels</td>
                        <td></td>
                        <td align="center"><a href="http://androidpixels.net">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">android dpi calculator</td>
                        <td></td>
                        <td align="center"><a href="http://coh.io/adpi/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">DPI Calculator</td>
                        <td></td>
                        <td align="center"><a href="https://chrome.google.com/webstore/detail/dpi-calculator/dldofgjemhkpilajnlenfijjpkabilcg?hl=en">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="java-to-ios">
                <a name="java-to-ios" class="anchor" href="#java-to-ios">
                    <span class="octicon octicon-link"></span>
                </a>Java To iOS</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">j2Objc</td>
                        <td></td>
                        <td align="center"><a href="https://github.com/google/j2objc">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">RoboVM</td>
                        <td></td>
                        <td align="center"><a href="http://www.robovm.org">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="json-xml-to-pojo-class-tools">
                <a name="jsonxml%E8%BD%AC%E6%8D%A2%E4%B8%BApojo-class%E5%B7%A5%E5%85%B7" class="anchor" href="#json-xml-to-pojo-class-tools">
                    <span class="octicon octicon-link"></span>
                </a>JSON/XML转换为POJO Class工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">jsonschema2pojo</td>
                        <td></td>
                        <td align="center"><a href="http://www.jsonschema2pojo.org">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Convert XML or JSON to Java Pojo</td>
                        <td></td>
                        <td align="center"><a href="http://pojo.sodhanalibrary.com">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="java-dao-generate-tools">
                <a name="java-dao-generate%E5%B7%A5%E5%85%B7" class="anchor" href="#java-dao-generate-tools">
                    <span class="octicon octicon-link"></span>
                </a>Java DAO Generate工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">Generate Java DAO for relational data table</td>
                        <td></td>
                        <td align="center"><a href="http://pojo.sodhanalibrary.com/GenerateDAO.html">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="chrome-plugin">
                <a name="chrome%E6%8F%92%E4%BB%B6" class="anchor" href="#chrome-plugin">
                    <span class="octicon octicon-link"></span>
                </a>Chrome插件</h4>

            <h5 id="chrome-android-plugin">
                <a name="android%E6%8F%92%E4%BB%B6" class="anchor" href="#chrome-android-plugin">
                    <span class="octicon octicon-link"></span>
                </a>Android插件</h5>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">Android SDK Search</td>
                        <td></td>
                        <td align="center"><a href="https://chrome.google.com/webstore/detail/android-sdk-search/hgcbffeicehlpmgmnhnkjbjoldkfhoin">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Android Resource Navigator</td>
                        <td></td>
                        <td align="center"><a href="https://chrome.google.com/webstore/detail/android-resource-navigato/agoomkionjjbejegcejiefodgbckeebo?hl=en">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">ADB Plugin for remote
                            <br>debugging Chrome on Android</td>
                        <td></td>
                        <td align="center"><a href="https://chrome.google.com/webstore/detail/adb/dpngiggdglpdnjdoaefidgiigpemgage?hl=en">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Mobile/RWD Tester</td>
                        <td></td>
                        <td align="center"><a href="https://chrome.google.com/webstore/detail/mobilerwd-tester/elmekokodcohlommfikpmojheggnbelo?hl=en">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">ExtensionAndroid SDK Samples Search</td>
                        <td></td>
                        <td align="center"><a href="https://chrome.google.com/webstore/detail/android-sdk-samples-searc/mbiobcenjhldinmnbpjihaemkfofnmgf?hl=en">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Android Developer Improvements</td>
                        <td></td>
                        <td align="center"><a href="https://chrome.google.com/webstore/detail/android-developer-improve/omakkdelnjjgfmohpfkejgfcckpkbhbj?hl=en">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Android downloader</td>
                        <td></td>
                        <td align="center"><a href="https://chrome.google.com/webstore/detail/android-downloader/pkffcfhlacdchhpahlgcajjiiljobbbb?hl=en">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h5 id="json-xml-format-plugin">
                <a name="jsonxml%E6%A0%BC%E5%BC%8F%E5%8C%96%E6%8F%92%E4%BB%B6" class="anchor" href="#json-xml-format-plugin">
                    <span class="octicon octicon-link"></span>
                </a>JSON/XML格式化插件</h5>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">JSONView</td>
                        <td></td>
                        <td align="center"><a href="https://chrome.google.com/webstore/detail/jsonview/chklaanhfefbnpoihckbnefhakgolnmc?hl=en">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">JSON Formatter</td>
                        <td></td>
                        <td align="center"><a href="https://chrome.google.com/webstore/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa?hl=en">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">JSON Viewer</td>
                        <td></td>
                        <td align="center"><a href="https://chrome.google.com/webstore/detail/json-viewer/gbmdgpbipfallnflgajpaliibnhdgobh?hl=en">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">JSON Finder</td>
                        <td></td>
                        <td align="center"><a href="https://chrome.google.com/webstore/detail/json-finder/flhdcaebggmmpnnaljiajhihdfconkbj?hl=en">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h5 id="encode-decode-plugin">
                <a name="encodedecode%E6%8F%92%E4%BB%B6" class="anchor" href="#encode-decode-plugin">
                    <span class="octicon octicon-link"></span>
                </a>Encode/Decode插件</h5>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">Base64 Encode and Decode</td>
                        <td></td>
                        <td align="center"><a href="https://chrome.google.com/webstore/detail/base64-encode-and-decode/kcafoaahiffdjffagoegkdiabclnkbha?hl=en">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h5 id="chrome-git-plugin">
                <a name="git" class="anchor" href="#chrome-git-plugin">
                    <span class="octicon octicon-link"></span>
                </a>Git Plugin</h5>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">Git Cheat Sheet</td>
                        <td></td>
                        <td align="center"><a href="https://chrome.google.com/webstore/detail/git-cheat-sheet/mjdmgoiobnbkfcfjcceaodlcodhpokgn?hl=en">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h2 id="android-dev-guides">
                <a name="guides" class="anchor" href="#android-dev-guides">
                    <span class="octicon octicon-link"></span>
                </a>Android Dev Guides</h2>

            <h4 id="google-java-program-guide-cn">
                <a name="google-java-program-guide-cn" class="anchor" href="#google-java-program-guide-cn">
                    <span class="octicon octicon-link"></span>
                </a>Google Java编程风格指南中文版</h4>

            <p>英文地址：<a href="http://google-styleguide.googlecode.com/svn/trunk/javaguide.html">http://google-styleguide.googlecode.com/svn/trunk/javaguide.html</a>
            </p>

            <p>地址0：<a href="http://hawstein.com/posts/google-java-style.html">http://hawstein.com/posts/google-java-style.html</a>
            </p>

            <p>地址1：<a href="https://github.com/codeset/google-java-styleguide">https://github.com/codeset/google-java-styleguide</a>
            </p>

            <h4 id="android-api-doc-cn">
                <a name="android-api%E4%B8%AD%E6%96%87%E7%89%88" class="anchor" href="#android-api-doc-cn">
                    <span class="octicon octicon-link"></span>
                </a>Android Api中文版</h4>

            <p>地址：<a href="http://wikidroid.sinaapp.com/Android%E4%B8%AD%E6%96%87API">http://wikidroid.sinaapp.com/Android中文API</a>)</p>

            <h4 id="android-api-guide-cn">
                <a name="android-api-guide-cn" class="anchor" href="#android-api-guide-cn">
                    <span class="octicon octicon-link"></span>
                </a>Android API指南中文版</h4>

            <p>地址：<a href="http://wiki.eoeandroid.com/Android_API_Guides">http://wiki.eoeandroid.com/Android_API_Guides</a>
            </p>

            <h4 id="proguard-config-guide">
                <a name="proguard-config-guide" class="anchor" href="#proguard-config-guide">
                    <span class="octicon octicon-link"></span>
                </a>Android Proguard混淆配置指南</h4>

            <p>地址：<a href="https://github.com/inferjay/AndroidProguardGuide/">https://github.com/inferjay/AndroidProguardGuide/</a>
            </p>

            <h4 id="gradle-plugin-guide-cn">
                <a name="gradle-plugin-guide-cn" class="anchor" href="#gradle-plugin-guide-cn">
                    <span class="octicon octicon-link"></span>
                </a>Gradle插件使用指南中文版</h4>

            <p>地址：<a href="http://avatarqing.github.io/Gradle-Plugin-User-Guide-Chinese-Verision">http://avatarqing.github.io/Gradle-Plugin-User-Guide-Chinese-Verision</a>
            </p>

            <h4 id="gradle-user-guide">
                <a name="gradle-user-guide" class="anchor" href="#gradle-user-guide">
                    <span class="octicon octicon-link"></span>
                </a>Gradle User Guide</h4>

            <p>Gradle 1.12用户指南：<a href="http://pan.baidu.com/s/1dD7sC2d">http://pan.baidu.com/s/1dD7sC2d</a>
            </p>

            <h2 id="android-dev-tutorials">
                <a name="tutorials" class="anchor" href="#android-dev-tutorials">
                    <span class="octicon octicon-link"></span>
                </a>Android Dev Tutorials</h2>

            <h4 id="android-learning-way">
                <a name="android%E5%AD%A6%E4%B9%A0%E4%B9%8B%E8%B7%AF" class="anchor" href="#android-learning-way">
                    <span class="octicon octicon-link"></span>
                </a>Android学习之路</h4>

            <p>地址：<a href="http://stormzhang.github.io/android/2014/07/07/learn-android-from-rookie/">http://stormzhang.github.io/android/2014/07/07/learn-android-from-rookie/</a>
            </p>

            <h4 id="google-androidtraining-tutorials">
                <a name="google-android%E5%AE%98%E6%96%B9%E5%9F%B9%E8%AE%AD%E8%AF%BE%E7%A8%8B%E4%B8%AD%E6%96%87%E7%89%88" class="anchor" href="#google-androidtraining-tutorials">
                    <span class="octicon octicon-link"></span>
                </a>Google Android官方培训课程中文版</h4>

            <p>地址：<a href="http://hukai.me/android-training-course-in-chinese/index.html">http://hukai.me/android-training-course-in-chinese/index.html</a>
            </p>

            <h4 id="developing-android-apps">
                <a name="developing-android-apps" class="anchor" href="#developing-android-apps">
                    <span class="octicon octicon-link"></span>
                </a>Developing Android Apps</h4>

            <p>地址：<a href="https://www.udacity.com/course/ud853">https://www.udacity.com/course/ud853</a>
            </p>

            <h4 id="java-design-patterns-samples-in-java">
                <a name="java-design-patterns-samples-in-java" class="anchor" href="#java-design-patterns-samples-in-java">
                    <span class="octicon octicon-link"></span>
                </a>Java Design Patterns Samples in Java.</h4>

            <p><a href="https://github.com/iluwatar/java-design-patterns">Java Design Patterns</a>
            </p>

            <h1 id="design-tools">
                <a name="design-tools" class="anchor" href="#design-tools">
                    <span class="octicon octicon-link"></span>
                </a>Design Tools</h1>

            <h4 id="photoshop-plugin">
                <a name="photoshop%E6%8F%92%E4%BB%B6" class="anchor" href="#photoshop-plugin">
                    <span class="octicon octicon-link"></span>
                </a>Photoshop插件</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">Cut&amp;Slice</td>
                        <td>切图神器</td>
                        <td align="center"><a href="http://www.cutandslice.me">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">DevRocket</td>
                        <td>切图神器</td>
                        <td align="center"><a href="http://www.robovm.org">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Cutterman</td>
                        <td>最好用的切图工具</td>
                        <td align="center"><a href="http://www.cutterman.cn">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Ink</td>
                        <td></td>
                        <td align="center"><a href="http://ink.chrometaphore.com">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Corner Editor</td>
                        <td>路径圆角编辑工具</td>
                        <td align="center">
                            <a href="http://photoshopscripts.wordpress.com">下载1</a> 
                            <br><a href="http://sourceforge.net/projects/cornereditor/">下载1</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">GuideGuide</td>
                        <td>辅助线工具</td>
                        <td align="center"><a href="http://guideguide.me">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Assistor PS</td>
                        <td></td>
                        <td align="center"><a href="http://assistor.net/en/assistor">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Skeuomorphism.it</td>
                        <td></td>
                        <td align="center"><a href="http://skeuomorphism.it">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">QuickGuide</td>
                        <td></td>
                        <td align="center"><a href="http://guchitaka.com/project-view/quickguidepro/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Long Shadow Generator</td>
                        <td>长投影效果生成插件</td>
                        <td align="center"><a href="http://lab.rayps.com/lsg2/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">android_resizer_toolkit</td>
                        <td></td>
                        <td align="center"><a href="https://github.com/marcosecchi/android_resizer_toolkit">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">android-ps-tools</td>
                        <td>一些方便Android UI设计的PhototShop插件。</td>
                        <td align="center"><a href="https://github.com/timroes/android-ps-tools">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">LayerCraft</td>
                        <td>A Photoshop plugin to export UI assets from layers</td>
                        <td align="center"><a href="http://lab.rayps.com/lc/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="vector-img-design-tools">
                <a name="%E7%9F%A2%E9%87%8F%E5%9B%BE%E8%AE%BE%E8%AE%A1%E5%B7%A5%E5%85%B7" class="anchor" href="#vector-img-design-tools">
                    <span class="octicon octicon-link"></span>
                </a>矢量图设计工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">Sketch 3</td>
                        <td></td>
                        <td align="center"><a href="http://bohemiancoding.com/sketch/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Affinity Designer</td>
                        <td></td>
                        <td align="center"><a href="https://affinity.serif.com">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Gravit</td>
                        <td></td>
                        <td align="center"><a href="http://gravit.io">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Adobe Illustrator</td>
                        <td></td>
                        <td align="center"><a href="https://www.adobe.com/cn/products/illustrator.html">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="ui-icon-cut-ools">
                <a name="%E5%88%87%E5%9B%BE%E5%B7%A5%E5%85%B7" class="anchor" href="#ui-icon-cut-ools">
                    <span class="octicon octicon-link"></span>
                </a>切图工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">Slicy</td>
                        <td></td>
                        <td align="center"><a href="http://macrabbit.com/slicy/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="desgin-size-mark-tools">
                <a name="desgin-size-mark-tools" class="anchor" href="#desgin-size-mark-tools">
                    <span class="octicon octicon-link"></span>
                </a>设计稿尺寸标注工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">马克鳗</td>
                        <td></td>
                        <td align="center"><a href="http://www.getmarkman.com">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">PxCook像素大厨</td>
                        <td>UI设计师效率提升利器，让你专注于设计本质，<br/>不再为标注切图而烦恼，从设计到实现一气呵成</td>
                        <td align="center"><a href="http://www.fancynode.com.cn/">下载</a>
                        </td>
                        <td align="center"><a href="http://www.fancynode.com.cn/tutorial">使用教程</a></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="prototype-design-tools">
                <a name="%E5%8E%9F%E5%9E%8B%E8%AE%BE%E8%AE%A1%E5%B7%A5%E5%85%B7" class="anchor" href="#prototype-design-tools">
                    <span class="octicon octicon-link"></span>
                </a>原型设计工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">Axure</td>
                        <td></td>
                        <td align="center"><a href="http://www.axure.com">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Fluid UI</td>
                        <td></td>
                        <td align="center"><a href="https://chrome.google.com/webstore/detail/fluid-ui/obgmmkbgpilmggfkhganmcmpemnhimgg?hl=en">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Briefs</td>
                        <td></td>
                        <td align="center"><a href="http://giveabrief.com">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Flinto</td>
                        <td></td>
                        <td align="center"><a href="https://www.flinto.com">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Balsamiq Mockups</td>
                        <td></td>
                        <td align="center"><a href="http://balsamiq.com/products/mockups/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">AppCooker</td>
                        <td></td>
                        <td align="center"><a href="http://www.appcooker.com">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Proto.io</td>
                        <td></td>
                        <td align="center"><a href="https://proto.io/en/signup/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">UXPin</td>
                        <td></td>
                        <td align="center"><a href="http://uxpin.com/#">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">InVision</td>
                        <td></td>
                        <td align="center"><a href="http://www.invisionapp.com">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">POP</td>
                        <td></td>
                        <td align="center"><a href="https://popapp.in">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">快现</td>
                        <td></td>
                        <td align="center"><a href="http://www.ikuaixian.com">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Composite</td>
                        <td></td>
                        <td align="center"><a href="http://www.getcomposite.com">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">OmniGraffle</td>
                        <td></td>
                        <td align="center"><a href="https://www.omnigroup.com/omnigraffle">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Marvelapp</td>
                        <td></td>
                        <td align="center"><a href="https://marvelapp.com">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Justinmind</td>
                        <td></td>
                        <td align="center"><a href="http://www.justinmind.com/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Form</td>
                        <td></td>
                        <td align="center"><a href="http://www.relativewave.com/form.html">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Prott</td>
                        <td></td>
                        <td align="center"><a href="https://prottapp.com">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Composite</td>
                        <td></td>
                        <td align="center"><a href="http://www.getcomposite.com/">下载</a>
                        </td>
                        <td align="center">td>
                    </tr>
                </tbody>
            </table>

            <h4 id="interaction-desgin-tools">
                <a name="%E4%BA%A4%E4%BA%92%E8%AE%BE%E8%AE%A1%E5%B7%A5%E5%85%B7" class="anchor" href="#interaction-desgin-tools">
                    <span class="octicon octicon-link"></span>
                </a>交互设计工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">Framer Studio</td>
                        <td></td>
                        <td align="center"><a href="http://framerjs.com">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Quartz Composer</td>
                        <td></td>
                        <td align="center"><a href="http://adcdownload.apple.com/Developer_Tools/graphics_tools_for_xcode__march_2014/graphics_tools_for_xcode_5.1__march_2014.dmg">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Origami</td>
                        <td></td>
                        <td align="center"><a href="http://facebook.github.io/origami/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">jQC</td>
                        <td></td>
                        <td align="center"><a href="http://qcdesigners.com/index.php/forums">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                                        <tr>
                        <td align="left">Avocado</td>
                        <td></td>
                        <td align="center"><a href="https://github.com/ideo/avocado">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Pixate</td>
                        <td></td>
                        <td align="center"><a href="http://www.pixate.com/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="ui-effect-preview-tools">
                <a name="ui%E6%95%88%E6%9E%9C%E9%A2%84%E8%A7%88%E5%B7%A5%E5%85%B7" class="anchor" href="#ui-effect-preview-tools">
                    <span class="octicon octicon-link"></span>
                </a>UI效果预览工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">Android Design Preview</td>
                        <td></td>
                        <td align="center"><a href="https://github.com/romannurik/AndroidDesignPreview/releases">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">PS Play</td>
                        <td></td>
                        <td align="center"><a href="http://isux.tencent.com/app/psplay">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Pixl Preview</td>
                        <td></td>
                        <td align="center"><a href="https://play.google.com/store/apps/details?id=at.markushi.pixl">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Skala Preview</td>
                        <td></td>
                        <td align="center"><a href="http://bjango.com/mac/skalapreview/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">LiveView</td>
                        <td></td>
                        <td align="center"><a href="http://www.zambetti.com/projects/liveview/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="harmonize-colors-tools">
                <a name="%E9%85%8D%E8%89%B2%E5%B7%A5%E5%85%B7" class="anchor" href="#harmonize-colors-tools">
                    <span class="octicon octicon-link"></span>
                </a>配色工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">Android Material Design可视化调色板</td>
                        <td></td>
                        <td align="center"><a href="https://github.com/HozakaN/MaterialDesignColorPalette">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Android Material Design Colours.xml</td>
                        <td></td>
                        <td align="center"><a href="https://gist.github.com/daniellevass/b0b8cfa773488e138037">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Colorube配色神器</td>
                        <td></td>
                        <td align="center"><a href="http://www.fancynode.com/colorcube/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Adobe Kuler</td>
                        <td></td>
                        <td align="center"><a href="https://kuler.adobe.com/zh/create/color-wheel/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">ColorSchemer Studio</td>
                        <td></td>
                        <td align="center"><a href="http://www.colorschemer.com">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">Piknik</td>
                        <td></td>
                        <td align="center"><a href="https://gist.github.com/daniellevass/b0b8cfa773488e138037">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="design-cvs-tools">
                <a name="design-cvs-tools" class="anchor" href="#design-cvs-tools">
                    <span class="octicon octicon-link"></span>
                </a>设计稿版本控制工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">LayerVault</td>
                        <td></td>
                        <td align="center"><a href="https://layervault.com">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="icon-handle-tools">
                <a name="icon-handle-tools" class="anchor" href="#icon-handle-tools">
                    <span class="octicon octicon-link"></span>
                </a>图标处理工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">Icon Slate</td>
                        <td></td>
                        <td align="center"><a href="http://www.kodlian.com/apps">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="online-icon-library">
                <a name="online-icon-library" class="anchor" href="#online-icon-library">
                    <span class="octicon octicon-link"></span>
                </a>在线Icon库</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">IconFont</td>
                        <td></td>
                        <td align="center"><a href="http://iconfont.cn">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">NounProject</td>
                        <td></td>
                        <td align="center"><a href="http://thenounproject.com">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="take-color-tools">
                <a name="take-color-tools" class="anchor" href="#take-color-tools">
                    <span class="octicon octicon-link"></span>
                </a>取色工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">ColorSnapper</td>
                        <td></td>
                        <td align="center"><a href="http://colorsnapper.com">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="hex-opacity-list">
                <a name="hex-opacity-list" class="anchor" href="#hex-opacity-list">
                    <span class="octicon octicon-link"></span>
                </a>不透明度16进制值</h4>

            <table>
                <thead>
                    <tr>
                        <th align="center">不透明度</th>
                        <th align="center">16进制值</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="center">100%</td>
                        <td align="center">FF</td>
                    </tr>
                    <tr>
                        <td align="center">95%</td>
                        <td align="center">F2</td>
                    </tr>
                    <tr>
                        <td align="center">90%</td>
                        <td align="center">E6</td>
                    </tr>
                    <tr>
                        <td align="center">85%</td>
                        <td align="center">D9</td>
                    </tr>
                    <tr>
                        <td align="center">80%</td>
                        <td align="center">CC</td>
                    </tr>
                    <tr>
                        <td align="center">75%</td>
                        <td align="center">BF</td>
                    </tr>
                    <tr>
                        <td align="center">70%</td>
                        <td align="center">B3</td>
                    </tr>
                    <tr>
                        <td align="center">65%</td>
                        <td align="center">A6</td>
                    </tr>
                    <tr>
                        <td align="center">60%</td>
                        <td align="center">99</td>
                    </tr>
                    <tr>
                        <td align="center">55%</td>
                        <td align="center">8C</td>
                    </tr>
                    <tr>
                        <td align="center">50%</td>
                        <td align="center">80</td>
                    </tr>
                    <tr>
                        <td align="center">45%</td>
                        <td align="center">73</td>
                    </tr>
                    <tr>
                        <td align="center">40%</td>
                        <td align="center">66</td>
                    </tr>
                    <tr>
                        <td align="center">35%</td>
                        <td align="center">59</td>
                    </tr>
                    <tr>
                        <td align="center">30%</td>
                        <td align="center">4D</td>
                    </tr>
                    <tr>
                        <td align="center">25%</td>
                        <td align="center">40</td>
                    </tr>
                    <tr>
                        <td align="center">20%</td>
                        <td align="center">33</td>
                    </tr>
                    <tr>
                        <td align="center">15%</td>
                        <td align="center">26</td>
                    </tr>
                    <tr>
                        <td align="center">10%</td>
                        <td align="center">1A</td>
                    </tr>
                    <tr>
                        <td align="center">5%</td>
                        <td align="center">0D</td>
                    </tr>
                    <tr>
                        <td align="center">0%</td>
                        <td align="center">00</td>
                    </tr>
                </tbody>
            </table>

            <p>出自：<a href="http://stackoverflow.com/questions/5445085/understanding-colors-in-android-6-chars">http://stackoverflow.com/questions/5445085/understanding-colors-in-android-6-chars</a>
            </p>

            <h4 id="phone-to-computer-preview-tools">
                <a name="phone-to-computer-preview-tools" class="anchor" href="#phone-to-computer-preview-tools">
                    <span class="octicon octicon-link"></span>
                </a>手机To电脑同步预览工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">Reflector</td>
                        <td></td>
                        <td align="center"><a href="http://www.airsquirrels.com/reflector/download/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">x-Mirage</td>
                        <td></td>
                        <td align="center"><a href="http://x-mirage.com/x-mirage/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">AirServer</td>
                        <td></td>
                        <td align="center"><a href="http://www.airserver.com">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">BBQScreen</td>
                        <td></td>
                        <td align="center"><a href="http://screen.bbqdroid.org">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h4 id="gif-record-tools">
                <a name="gif-record-tools" class="anchor" href="#gif-record-tools">
                    <span class="octicon octicon-link"></span>
                </a>Gif图片录制工具</h4>

            <table>
                <thead>
                    <tr>
                        <th align="left">名称</th>
                        <th>简介</th>
                        <th align="center">下载地址</th>
                        <th align="center">使用教程</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td align="left">LICEcap</td>
                        <td></td>
                        <td align="center"><a href="http://www.cockos.com/licecap/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                    <tr>
                        <td align="left">GifCam</td>
                        <td></td>
                        <td align="center"><a href="http://blog.bahraniapps.com/gifcam/">下载</a>
                        </td>
                        <td align="center"></td>
                    </tr>
                </tbody>
            </table>

            <h2 id="ui-programming-language">
                <a name="ui-programming-language" class="anchor" href="#ui-programming-language">
                    <span class="octicon octicon-link"></span>
                </a>UI Programming Language</h2>

            <p><a href="http://uilang.com">UILang</a>
            </p>

            <h2 id="design-tutorials">
                <a name="tutorials-1" class="anchor" href="#design-tutorials">
                    <span class="octicon octicon-link"></span>
                </a>Design Tutorials</h2>

            <p><a href="https://hackdesign.org/lessons">HackDesign</a>
            </p>

            <h2 id="design-games">
                <a name="games" class="anchor" href="#design-games">
                    <span class="octicon octicon-link"></span>
                </a>Design Games</h2>

            <p><a href="http://bezier.method.ac">The Bezier Game</a>
            </p>

            <p>一个帮助你练习PS里钢笔工具的小游戏。</p>

            <h2 id="design-guides">
                <a name="guides-1" class="anchor" href="#design-guides">
                    <span class="octicon octicon-link"></span>
                </a>Design Guides</h2>

            <h4 id="android-design-guides-cn">
                <a name="android-design-guides-cn" class="anchor" href="#android-design-guides-cn">
                    <span class="octicon octicon-link"></span>
                </a>Android设计指南非官方简体中文版</h4>

            <p>Topfun镜像地址：<a href="http://www.topfun.us/adchs/index.html">http://www.topfun.us/adchs/index.html</a>
            </p>

            <p>Github镜像地址：<a href="http://adchs.github.io">http://adchs.github.io</a>
            </p>

            <p>ApkBus镜像地址：<a href="http://www.apkbus.com/design/">http://www.apkbus.com/design/</a>
            </p>

            <p>Segmentfault镜像地址：<a href="http://mirrors.segmentfault.com/adchs/">http://mirrors.segmentfault.com/adchs/</a>
            </p>

            <p>多看阅读镜像地址：<a href="http://www.duokan.com/book/47790">http://www.duokan.com/book/47790</a>
            </p>

            <h4 id="android-cheatsheet-for-graphic-designers">
                <a name="android-cheatsheet-for-graphic-designers" class="anchor" href="#android-cheatsheet-for-graphic-designers">
                    <span class="octicon octicon-link"></span>
                </a>Android Cheatsheet for Graphic Designers</h4>

            <p>地址:<a href="http://petrnohejl.github.io/Android-Cheatsheet-For-Graphic-Designers/">http://petrnohejl.github.io/Android-Cheatsheet-For-Graphic-Designers/</a>
            </p>

            <h4 id="google-material-design-cn">
                <a name="google-material-design-cn" class="anchor" href="#google-material-design-cn">
                    <span class="octicon octicon-link"></span>
                </a>Google Material Design 中文版</h4>

            <p>地址：<a href="http://design.1sters.com">http://design.1sters.com</a>
            </p>

            <p>地址： <a href="http://www.ui.cn/Material/">http://www.ui.cn/Material/</a>
            </p>

            <h4 id="designers-guide-to-dpi">
                <a name="designers-guide-to-dpi" class="anchor" href="#designers-guide-to-dpi">
                    <span class="octicon octicon-link"></span>
                </a>Designer's Guide To dpi</h4>

            <p>地址：<a href="http://sebastien-gabriel.com/designers-guide-to-dpi/home#">http://sebastien-gabriel.com/designers-guide-to-dpi/home</a>
            </p>

            <h4>
                <a name="email-design-guide" class="anchor" href="#email-design-guide">
                    <span class="octicon octicon-link"></span>
                </a>Email Design Guide</h4>

            <p>地址：<a href="http://mailchimp.com/resources/email-design-guide/">http://mailchimp.com/resources/email-design-guide/</a>
            </p>

            <h2 id="free-design-resources">
                <a name="free-design-resources" class="anchor" href="#free-design-resources">
                    <span class="octicon octicon-link"></span>
                </a>Free Design Resources</h2>

            <p><a href="http://pan.baidu.com/s/1i35iBNv">Google Material Design 素材</a>(感谢 <a href="http://weibo.com/sanityd">@SanityD</a>)</p>

            <p><a href="https://dribbble.com/shots/1617724">Material Design Icon Templates</a>
            </p>

						<p><a href="https://github.com/google/material-design-icons">Material Design的图标集</a>
            </p>
            
            <p><a href="https://www.behance.net/gallery/20514895/Material-Design-UI-Kit">Material Design UI Kit for Sketch</a>
            </p>

            <p><a href="http://tristanremy.com/nexus-5/">Nexus 5 template for Sketch</a>
            </p>

            <p><a href="http://androiduiux.com/free-design-resources/?blogsub=confirming#blog_subscription-2">Free Design Resources</a>
            </p>

            <p><a href="https://dl.dropboxusercontent.com/u/8067075/System%20Icons.zip">434 SVG icons</a>
            </p>

            <p><a href="http://ui-cloud.com">UI Cloun</a>
            </p>
			
						<p><a href="https://github.com/nullice/NViconsLib_Silhouette">161个国内外社交网站矢量图标</a>
            </p>
				
						<p><a href="http://www.androidicons.com">250 free icons in 5 sizes and 14 colors</a>
            </p>
						<p><a href="http://matt-cooper.com/minimalistic-icons/">MINIMALISTIC EVERYDAY ICONS</a>
            </p>
            
            <h1 id="books-list">
                <a name="books" class="anchor" href="#books-list">
                    <span class="octicon octicon-link"></span>
                </a>Books</h1>

            <p><a href="https://github.com/vhf/free-programming-books/blob/master/free-programming-books.md#android">Free Programming Books</a>
            </p>

            <p>一堆免费的Android开发相关的电子书。</p>

            <p><a href="http://www.it-ebooks.info/book/2445/">50 Android Hacks</a>
            </p>

            <p>50 Android Hacks这本书分12个部分介绍了50个Android开发的小技巧。</p>

						<p><a href="http://siberiawolf.com/free_programming/index.html">免费的编程中文书籍索引</a>
            </p>
						

            <h1 id="license">
                <a name="license" class="anchor" href="#license">
                    <span class="octicon octicon-link"></span>
                </a>License</h1>

            <pre><code>Copyright 2014 inferjay (http://www.androiddevtools.cn)
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
</code></pre>
					
					<!-- JiaThis Button BEGIN -->
					<div id="jiathis-share-bar" class="jiathis_style">
					<span class="jiathis_txt">分享到：</span>
					<a class="jiathis_button_tsina">新浪微博</a>
					<a class="jiathis_button_weixin">微信</a>
					<a class="jiathis_button_qzone">QQ空间</a>
					<a class="jiathis_button_twitter">Twitter</a>
					<a class="jiathis_button_googleplus">Google+</a>
					<a class="jiathis_button_fb">Facebook</a>
					<a class="jiathis_button_qq">QQ收藏</a>
					
					<a href="http://www.jiathis.com/share?uid=1948353" class="jiathis jiathis_txt jiathis_separator jtico jtico_jiathis" target="_blank">更多</a>
					<a class="jiathis_counter_style"></a>
					</div>

		         <div id="uyan-comment" class="span9">
		            <!-- UY BEGIN
		            <div id="uyan_frame"></div>
		            <script type="text/javascript" src="http://v2.uyan.cc/code/uyan.js?uid=1948353"></script>
		            UY END -->
					
					<!-- 多说评论框 start -->
					<div class="ds-thread" data-thread-key="686835c9a9956696" data-title="AndroidDevTools" data-url="http://www.androiddevtools.cn"></div>
					<!-- 多说评论框 end -->

				</div>
          </div>
          
    </section>
        <!-- FOOTER  -->
    <div id="footer_wrap" class="outer">
        <footer class="inner">
            <p class="copyright">AndroidDevTools maintained by <a href="https://github.com/inferjay/AndroidDevTools">inferjay</a>
            </p>
            <p class="modified">Be modified based on <a href="http://square.github.io/picasso/">Picass</a></p>
            <p>Published with <a href="http://pages.github.com">GitHub Pages</a>
            </p>
        </footer>
    </div>
    	
    	<!-- 多说公共JS代码 start (一个网页只需插入一次) -->
		<script type="text/javascript">
		var duoshuoQuery = {short_name:"androiddevtools"};
			(function() {
				var ds = document.createElement('script');
				ds.type = 'text/javascript';ds.async = true;
				ds.src = (document.location.protocol == 'https:' ? 'https:' : 'http:') + '//static.duoshuo.com/embed.js';
				ds.charset = 'UTF-8';
				(document.getElementsByTagName('head')[0] 
				 || document.getElementsByTagName('body')[0]).appendChild(ds);
			})();
			</script>
		<!-- 多说公共JS代码 end -->
    
		<script type="text/javascript" >
		var jiathis_config={
			data_track_clickback:true,
			siteNum:12,
			sm:"tsina,weixin,qzone,twitter,googleplus,fb,evernote,pocket,instapaper,reddit,qq,tumblr",
			url:"http://www.androiddevtools.cn",
			summary:"",
			title:"无需翻墙下载最新版Android开发工具 ADT Bundle Android Studio SDK Tools #Android开发工具#",
			boldNum:6,
			pic:"http://ww1.sinaimg.cn/mw690/005GSHYzgw1el9z7zgqbtj31kw0yc45g.jpg",
			ralateuid:{
				"tsina":"androiddevtools"
			},
			shortUrl:false,
			hideMore:true
		}
		</script>
		<script type="text/javascript" src="http://v3.jiathis.com/code/jia.js?uid=1948353" charset="utf-8"></script>
		<!-- JiaThis Button END -->
    
    <script src="static/js/jquery.1.9.1.min.js"></script>
    <script src="static/js/bootstrap.min.js"></script>
    <script src="static/js/jquery.smooth-scroll.min.js"></script>
    <script src="static/js/jquery-maven-artifact.min.js"></script>
    <script src="static/js/prettify.js"></script>
    <script type="text/javascript">
      $(function() {
        // Syntax highlight code blocks.
        prettyPrint();

        // Spy on scroll position for real-time updating of current section.
        $('body').scrollspy();

        // Use smooth-scroll for internal links.
        $('a').smoothScroll();

        // Enable tooltips on the header nav image items.
        $('.menu').tooltip({
          placement: 'bottom',
          trigger: 'hover',
          container: 'body',
          delay: {
            show: 500,
            hide: 0
          }
        });
      });
    </script>

    <script type="text/javascript">
    var gaJsHost = (("https:" == document.location.protocol) ? "https://ssl." : "http://www.");
    document.write(unescape("%3Cscript src='" + gaJsHost + "google-analytics.com/ga.js' type='text/javascript'%3E%3C/script%3E"));
    </script>
    <script type="text/javascript">
    try {
        var pageTracker = _gat._getTracker("UA-52369435-2");
        pageTracker._trackPageview();
    } catch (err) {}
    </script>
  </body>
</html>

