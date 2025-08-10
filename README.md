# trilium-enhancement-Lazy-Pack
零代码基础的小三月，下载体验了大佬们整合的多数体验增强主体插件后，最终整合的懒人实用插件。

部分插件在原版的基础上略微修改了一些配色。

另外附加自己基于Blue theme及云遥修改版改色的VOCALOID歌姬应援色主题，希望您能喜欢(❁´◡`❁)

VOCALOID歌姬应援色主题CSS文件中附有详细的注释，方便您进行二次修改。

因为中文翻译和一些操作习惯的原因，我更喜欢使用Trilium Notes，这些插件我都是用Trilium Notes v0.63.7进行测试过的，在Trilium next上部分插件可能不适用。


插件按照这2类进行整理：颜色增强和操作体验，最后总结了一些使用注意事项。

1  Color Enhancements | 颜色增强
使用后对比原版主题，在视觉上会有更好的体验

1.1  VOCALOID歌姬应援色主题
使用方法：导入插件整合包后，在外观设置中启用 VOCALOID歌姬应援色主题

2025810新增修改以下内容：
取消标题背景框的外框线、手动调整了部分标题居中的样式，使得在卡片上预览的标题显示更加居中。
主题内对todo的方框在卡片上显示的位置进行控制，让其在卡片上更加美观，避免口太靠左侧边缘。
配合主题加入优化右侧导航页面的插件，详见下方2.9和2.10，主要功能有目录导航关闭后可以重新用按钮打开，目录导航会显示当前页面浏览所在位置。
使用deepseek优化了无序项的折叠功能，使得笔记可以在编辑和只读模式下都能实现折叠，折叠图标偶尔仍存在可能不渲染的问题，但不影响折叠功能，通常切换一次其他标签页后即可显示。
集成chat机器人，并自己汉化了部分菜单，您可能会用到。
集成trilium-simple-mind-map思维导图，可以关联笔记到思维导图上
增加参考设置建议及trilium笔记中会常用到的markdown写法
界面展示:

主界面

标题 配色，目录考虑简约取消使用对应标题背景色

搜索页面

设置页面：在外观设置中启用 VOCALOID歌姬应援色主题
VOCALOID歌姬应援色主题应援色
初音ミク #39C5BB(苍绿色)	镜音リン #FFA500(橘黄)	镜音レン #FFE211(明黄)	巡音ルカ #FAAFBE(粉)
MEIKO #D80000(酒红)	KAITO #0000FF(蓝)	洛天依 #66CCFF(天蓝)	GUMI #CCFF00(亮绿)
 

1.2  calendar | 日历显示优化 颜色修改 

原版暗色主题

增强版本，色彩对比更加突出，当日显示为红色
 

1.3  @ option highlight | at选项高亮

默认

增强，背景更为突出
 

1.4  note path | 笔记路径 添加间隔线 加深当前路径颜色

默认

增强，更为突出
 

1.5  edited note list | 编辑过的笔记列表

默认

增强，日历页面下编辑过的笔记，每一个编辑过的文件会单独在一行展示
 

1.6  change clone icon | 修改克隆标记图标

默认

增强，用DNA图标表示克隆页面，颜色突出
 

 

2  Action Enhancements | 操作增强
使用后对比原版界面，在操作、视觉上会有更好的体验

2.1  wide quick search | 取消快速搜索框的宽度限制

默认

增强，无限宽度的快速搜索。现在你可以看到所有内容。
 

2.2  horizontal scrollbar for note | 使左侧面板和目录显示水平滚动条

默认

增强，且鼠标悬停会显示完整的名称
 

2.3  new note button to front| 新增笔记按钮移动至前方

默认，由于搭配了2.2插件：显示水平滚动条，添加按钮将会默认在文件名称末尾显示，导致操作不便。

增强，将添加笔记按钮移动到前面，更突出的色彩表现，避免折叠误触。减少了误点击新建笔记按钮的可能性。
 

2.4  openfilepath| 双击可打开斜体显示的文件或文件夹路径

双击斜体路径任意位置就可以打开对应的文件夹，便于管理本地文件。


 

2.5  Trilium Breadcrumbs| 显示笔记的面包屑导航

脚本界面，可设置导航的显示位置和宽度等等

鼠标悬停会显示缩略信息
 

2.6  Collapsable bullets| 无序标题可以折叠（2025/08/10使用deepseek优化，处于只读状态下折叠也可用）

无序展开

无序，部分折叠，管理长文本和图片好用，暂未找到 ' 有序 ' 的折叠插件，另外注意有些时候折叠符号会延迟显示或不显示，折叠功能不会受到影响。遇到不显示可以尝试刷新。
 

2.7  Image Zoom| 在 Trilium 中缩放、拖动和预览图片
单击图像以缩放它们。您可以使用鼠标滚轮放大和缩小图像，拖动图像，并通过单击图像外部或按 Esc关闭预览。右键单击缩放图像进行下载或您可以将图像数据复制到剪贴板并粘贴。此小部件使您能够复制图像并将其粘贴到 Microsoft Word、WPS Office 等应用程序中。大图像将自动缩小以适合屏幕。使用这个插件后，您需要通过右键单击才能访问原始图像编辑弹出菜单。
image zoom
左键单击查看，鼠标滚轮缩放，右键弹出下载功能
 

2.8  hide note attributes| 隐藏子笔记列表中显示的属性

默认

增强，更加简洁
 

2.9  remember-right-pane| 关闭右侧目录后可以重新打开


若关闭右侧目录或高亮列表后，下次重新刷新页面会记录住关闭状态，不会再强制刷新显示
 

2.10  show-position-in-toc| 在右侧目录中以标记当前页面浏览位置

默认

增强，原版是以红字显示，修改为Gumi背景色
 

2.11  trilium-chat.js| AI机器人
这个聊天插件与 Trilium 高度集成，允许您直接在 Trilium 中访问 ChatGPT！个人汉化了部分菜单。

Alt+q 是切换chat - UI 的默认快捷键，或者您可以单击右上角的聊天图标进行切换。


注意：开始使用前，您需要在选项注释中配置您的 ChatGPT API 密钥并重新加载，或者配置使用自己本地托管的 Ollama。。


 

使用本地大模型设置教程

 

2.12  trilium-simple-mind-map| 思维导图  （使用的是V1.2.0版本，最新的1.3版本超链接笔记可能有问题）

在插入子笔记的菜单中可以看到simple-mind-map选项

左上角菜单展开，退出全标签页就可以修改笔记名了，全屏按钮慎用，很卡！
trilium-simple-mind-map详细使用说明介绍

缺点没得放大缩小，优势是支持链接笔记，相比自带集成的美人鱼图，这个思维导图交互要方便许多，就基本功能完全够用啦。

 

3  Trilium快速上手精简技巧
创建笔记	编辑文字	保存笔记和历史版本	快速定位常用笔记
标题	目录功能	TODO 列表	数学公式
引用文字, 段落和代码块	笔记链接, 双链笔记	克隆笔记	插入图片
日记	使用模板创建笔记	Trilium 主题 theme	 

 

3.1  其他参考设置建议：
修改强制保存当前笔记/创建笔记历史记录快捷键为Ctrl+S（参考 保存笔记和历史版本）
当笔记具有超过3个标题时, 目录将出现在文本笔记中；高亮列表只✔带有背景的字体(设置页面： 文字笔记）
取消默认✔的图像压缩（设置页面： 图片）
一次性复制多张图片到笔记时，图片往往不能正常载入。建议编辑笔记时要一张一张的粘贴哦。
视频、音频附件直接上传到笔记里时，需要保证音频或视频名称不能有中文，否则会有未知bug，会造成无法在笔记中播放预览、一直卡加载使笔记卡顿，最终造成笔记崩溃。
windows环境下使用trilium.exe 运行程序，默认的笔记数据库会在C盘生成，使用trilium-portable.bat运行程序,默认的数据库会在程序的安装路径下生成。你也可以修改trilium-portable.bat中的数据库路径，使其放在你想要的磁盘下。例如我把数据文件放到G盘里，修改的bat参考如下。
双击trilium.exe 运行程序	默认访问数据库文件路径：C:\Users\admin\AppData\Roaming\trilium-data	

双击trilium-portable.bat运行程序	未修改的情况下，默认访问数据库文件路径：是程序安装路径；例如我的是：D:\User\Program Files (x86)\trilium-0.63.7.0\trilium-data；修改后，以修改后指向的地址路径为准。
我把数据文件放到G盘里，启动用的的bat如下，下方标记部分都要改，否则运行trilium-portable.bat也不会正确使用修改后的路径数据库。
@echo off
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

除了以上方式修改默认数据库存放位置外，还可以修改环境变量来实现，这里不作展开。
 

3.2  常用Markdown格式：
粗体 – **text** 或者__text__
斜体 – *text* 或者 _text_
删除线 – ~~text~~
无序符号列表 – *后面加空格 或者 -后面加空格
编号列表 – 1.后面加空格 或者 1)后面加空格  ( 使用1)创建时）要在英文字符下创建，推荐用前者1.创建）
待办事项列表 – [ ]后面加空格 或者 [x]后面加空格 (只能在行开头使用创建）
块引号 – >后面加空格(只能在行开头使用创建），也可以用``` 引用文字, 段落和代码块的方式创建，这两者背景颜色和右上角标识略有区别，参考如下:
>后面加空格创建

```方式创建
文字引用 – 输入 `文字` 会变成 文字）(这个 ` 字符是键盘上左上角的波浪号，在英文字符下创建）
标题 – 输入##后面加空格可以创建H2标题，###后面加空格可以创建H3标题，以此类推最多可创建H6标题 (只能在行开头使用创建）
水平线– 输入---可创建水平分割线 (只能在行开头使用创建,下面这个分割线就是用这种方式创建的）
 
