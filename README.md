# trilium-enhancement-Lazy-Pack for Trilium Notes v0.63.7
## 前言

~\(≧▽≦)/~零代码基础的小三月，下载体验了大佬们整合的多数体验增强主体插件后，最终整合的懒人实用插件。

部分插件在原版的基础上略微修改了一些配色。

另外附加自己基于Blue theme及云遥修改版改色的VOCALOID歌姬应援色主题，希望您能喜欢(❁´◡`❁)

VOCALOID歌姬应援色主题CSS文件中附有详细的注释，方便您进行二次修改。


![这是图片](https://i1.hdslb.com/bfs/new_dyn/ca777a5e39d8e88b0e19dbc3c08f3f6320413499.png)

因为中文翻译和一些操作习惯的原因，我更喜欢使用Trilium Notes，这些插件我都是用Trilium Notes v0.63.7进行测试过的，在Trilium next上部分插件可能不适用。
---
**使用方法**
- [下载附件zip](https://github.com/march-7th-mini/trilium-enhancement-Lazy-Pack/releases/tag/Trilium-enhancement-Lazy-Pack)
- 然后打开Trilium，右键左侧树导航中Trilium 扩展，导入到笔记（取消勾选安全导入），按F5或ctrl+r刷新页面。
![这是图片](https://i1.hdslb.com/bfs/new_dyn/57bcf0ceb8114b5f9b8a4fe7efa78b6320413499.gif)
---



**插件按照这2类进行整理：颜色增强和操作体验，最后总结了一些使用注意事项。**

## 1  Color Enhancements | 颜色增强
使用后对比原版主题，在视觉上会有更好的体验，主要有如下几种

### 1.1  VOCALOID歌姬应援色主题
使用方法：导入插件整合包后，在外观设置中启用 VOCALOID歌姬应援色主题

**2025810新增修改以下内容：**
- 取消标题背景框的外框线、手动调整了部分标题居中的样式，使得在卡片上预览的标题显示更加居中。
- 主题内对todo的方框在卡片上显示的位置进行控制，让其在卡片上更加美观，避免口太靠左侧边缘。
- 配合主题加入优化右侧导航页面的插件，主要功能有目录导航关闭后可以重新用按钮打开，目录导航会显示当前页面浏览所在位置。
- 使用deepseek优化了无序项的折叠功能，使得笔记可以在编辑和只读模式下都能实现折叠，折叠图标偶尔仍存在可能不渲染的问题，但不影响折叠功能，通常切换一次其他标签页后即可显示。
- 集成chat机器人，并自己汉化了部分菜单，您可能会用到。
- 集成trilium-simple-mind-map思维导图，可以关联笔记到思维导图上
- 增加参考设置建议及trilium笔记中会常用到的markdown写法
![这是图片](https://i1.hdslb.com/bfs/new_dyn/bb5c231fa8b2852795c2a78b9249c50d20413499.gif)
 

### 1.2  calendar | 日历显示优化 颜色修改 
![这是图片](https://i1.hdslb.com/bfs/new_dyn/9b9d8337f2e62f016bc2d433f115021020413499.png)

 
### 1.3  @ option highlight | at选项高亮
![这是图片](https://i1.hdslb.com/bfs/new_dyn/2345a2b6919413a91088e149078c41ed20413499.png)

 

### 1.4  note path | 笔记路径 添加间隔线 加深当前路径颜色
![这是图片](https://i1.hdslb.com/bfs/new_dyn/9fc31ca74675682afb17d40a96781b7620413499.png)

 

### 1.5  edited note list | 编辑过的笔记列表

![这是图片](https://i1.hdslb.com/bfs/new_dyn/f0c422b44c3297287b2a8b2967bb7e4320413499.png)
 

### 1.6  change clone icon | 修改克隆标记图标

![这是图片](https://i1.hdslb.com/bfs/new_dyn/63cd608c173833480d7cf8648a9da78b20413499.png)
 

 

## 2  Action Enhancements | 操作增强
使用后对比原版界面，在操作上会有更好的体验,有更多的便利功能

### 2.1  wide quick search | 取消快速搜索框的宽度限制

![这是图片](https://i1.hdslb.com/bfs/new_dyn/be5471a018deb1a990738da1498a02ca20413499.png)
 

### 2.2  horizontal scrollbar for note | 使左侧面板和目录显示水平滚动条

![这是图片](https://i1.hdslb.com/bfs/new_dyn/4aed912a4e3b6cdbd309f974234a26c020413499.png)
 

### 2.3  new note button to front| 新增笔记按钮移动至前方

![这是图片](https://i1.hdslb.com/bfs/new_dyn/98b167560b4223927992f0c3bfa1338020413499.png)
 

### 2.4  openfilepath| 双击可打开斜体显示的文件或文件夹路径

![这是图片](https://i1.hdslb.com/bfs/new_dyn/5dc0ebd9065557ccccd6cca396ede1a920413499.png)

 

### 2.5  Trilium Breadcrumbs| 显示笔记的面包屑导航

![这是图片](https://i1.hdslb.com/bfs/new_dyn/946067a9983a494b251a6e99a4a13e2220413499.png)
 

### 2.6  Collapsable bullets| 无序标题可以折叠（2025/08/10使用deepseek优化，处于只读状态下折叠也可用）

![这是图片](https://i1.hdslb.com/bfs/new_dyn/68ced237e3970a3eb3c75a0c80dc48f220413499.png)
 

### 2.7  Image Zoom| 在 Trilium 中缩放、拖动和预览图片
![这是图片](https://i1.hdslb.com/bfs/new_dyn/0d9905dd6ab8ed16a96a04655bd3ca2920413499.png)
 

### 2.8  hide note attributes| 隐藏子笔记列表中显示的属性

![这是图片](https://i1.hdslb.com/bfs/new_dyn/85ac871b3746ed3c6eeab30c355a62e320413499.png)
 

### 2.9  remember-right-pane| 关闭右侧目录后可以重新打开
若关闭右侧目录或高亮列表后，下次重新刷新页面会记录住关闭状态，不会再强制刷新显示



### 2.10  show-position-in-toc| 在右侧目录中以标记当前页面浏览位置
增强，原版是以红字显示，修改为Gumi`#CCFF00(亮绿)`背景色

 

### 2.11  trilium-chat.js| AI机器人
这个聊天插件与 Trilium 高度集成，允许您直接在 Trilium 中访问 ChatGPT！个人汉化了部分菜单。

Alt+q 是切换chat - UI 的默认快捷键，或者您可以单击右上角的聊天图标进行切换。


注意：开始使用前，您需要在选项注释中配置您的 ChatGPT API 密钥并重新加载，或者配置使用自己本地托管的 Ollama。。


 

### 2.12  trilium-simple-mind-map| 思维导图  （使用的是V1.2.0版本，最新的1.3版本超链接笔记在Trilium Notes v0.63.7上可能有问题）

在插入子笔记的菜单中可以看到simple-mind-map选项

左上角菜单展开，退出全标签页就可以修改笔记名了，全屏按钮慎用，会很卡！

优势是支持链接笔记，。

 

## 3  Trilium快速上手精简技巧
一些自己常用设置
### 3.1  其他参考设置建议：
- 修改强制保存当前笔记/创建笔记历史记录快捷键为Ctrl+S
- 当笔记具有超过3个标题时, 目录将出现在文本笔记中；高亮列表只✔带有背景的字体
- 取消默认✔的图像压缩
- 一次性复制多张图片到笔记时，图片往往不能正常载入。建议编辑笔记时要一张一张的粘贴哦。
- 视频、音频附件直接上传到笔记里时，需要保证音频或视频名称不能有中文，否则会有未知bug，会造成无法在笔记中播放预览、一直卡加载使笔记卡顿，最终造成笔记崩溃。
- windows环境下使用trilium.exe 运行程序，默认的笔记数据库会在C盘生成，使用trilium-portable.bat运行程序,默认的数据库会在程序的安装路径下生成。你也可以修改trilium-portable.bat中的数据库路径，使其放在你想要的磁盘下。例如我把数据文件放到G盘里，修改的bat参考如下。
> 1. 双击trilium.exe 运行程序	默认访问数据库文件路径：C:\Users\admin\AppData\Roaming\trilium-data	

> 2. 双击trilium-portable.bat运行程序	未修改的情况下，默认访问数据库文件路径：是程序安装路径；例如我的是：D:\User\Program Files (x86)\trilium-0.63.7.0\trilium-data；修改后，以修改后指向的地址路径为准。
- 我把数据文件放到G盘里，启动用的的bat如下，下方标记部分都要改，否则运行trilium-portable.bat也不会正确使用修改后的路径数据库。
```@echo off
:: Try to get powershell to launch Trilium since it deals with UTF-8 characters in current path
:: If there's no powershell available, fallback to unicode enabled command interpreter

WHERE powershell.exe > NUL 2>&1
IF %ERRORLEVEL% NEQ 0 GOTO BATCH ELSE GOTO POWERSHELL

:POWERSHELL
powershell -ExecutionPolicy Bypass -NonInteractive -NoLogo "Set-Item -Path Env:TRILIUM_DATA_DIR -Value 'G:\trilium-data'; ./trilium.exe"
GOTO END

:BATCH
:: Make sure we support UTF-8 characters
chcp 65001

:: Get Current Trilium executable directory and compute data directory
SET DIR=%~dp0
SET TRILIUM_DATA_DIR=G:\trilium-data\
cd %DIR%
start trilium.exe
GOTO END

:END
```
- 除了以上方式修改默认数据库存放位置外，还可以修改环境变量来实现，这里不作展开。
 

### 3.2  常用Markdown格式：
详见附件
 
