# 微信
### 重要
[bug]升级之后消息，微信顶端会下沉

[bug]小视频无法播放

[bug]微信提醒消息与实际提醒消息不符

[bug]图片“保存“按钮不管用，右键保存图片可以；

### 一般
[bug]红包，时显示金额，时而不显示金额，有时候无法显示最佳手气。

[bug]消息无法撤回（有的版本是这样的，有的版本不这样）

[bug]视频聊天的时候，窗口显示不正常，有时候闪退

[bug]声音设置需要选择后才会生效

[bug]调整系统的音量不会改变微信提示音

[bug]朋友圈信息不能自动换行，信息被遮挡

[feature]朋友圈评论时，只能输入文字，插入表情点击不可用

[feature]点击联系人，右上角更多中的添加到桌面功能不可用

[feature]扫一扫不可用

[feature]勿扰模式不可用

# QQ
### 重要
[bug]聊天消息无法复制粘帖

### 一般
[bug]在群里群文件打开会崩溃

[bug]qq提示消息太长

[bug]qq打开链接（总是在内部打开，不是外链）

[bug]qq用二维码传送文件，点开二维码后退出qq崩溃

[bug]切换夜间模式，QQ退出

[bug]空间发过的动态无法删除

# MS office 目前存在的问题：
### 重要
[bug]给表格文字添加边框时，选择完表格，点击边框很难选中，光标经常会跳到fx的输入框中。(点击视图，去掉第一个编辑栏可以使操作正常很多）

[bug]excel\Word 快捷键ctrl + s 保存文件，没提示选择路径，无法知道保存到哪；

[bug]excel共享文件操作，以附件形式分享会出现崩溃退出。附log：[20170103excel](https://github.com/openthos/community-analysis/blob/master/daily-testresult/20170103excel)

[bug]绘图功能会导致excel无响应退出。

[bug]绘图功能导致word无响应退出。

[bug]excel 总是无缘无故自动退出；

### 一般
[bug]excel打印时左上角显示保存为pdf。

[bug]excel文档另存为，添加位置，选择任意一个后，无法返回。

[bug]powerpoint 添加图片等操作导致串口内显示不全（部分边界文字跑到屏幕外）

[bug]ctrl+鼠标滚轮，放大缩小不太灵敏；

[feature]excel无法进行替换功能

[feature]excel无格式刷功能

[feature]无法多文档同时打开，需要关掉一个再打开另一个；

[feature]excel 横的列表栏右键可以插入单元格，竖的列表栏右键没有插入列表功能；

[feature]打印快捷键ctrl+p 不支持；(word不支持，excel和ppt支持)

[feature]打印缺少“正在打印...“这种提示；

[feature]PPT右上角无“- 口 X“功能，导致无法对此功能进行操作；

# 文件管理器：
### 重要
[bug]文件／文档放入回收站中，依然可以正常编辑（需要商议以后是否为隐患）。

[bug]桌面文件不能重命名(解决方法：关闭所有应用，才可重命名)

[bug]地址栏经常显示“SD卡“，但是输入SD卡则提示地址错误

[bug]当光标在地址栏或者搜索栏时，ctrl+鼠标选择文件，光标仍在地址栏，且复制、删除等快捷键均无效

[bug]点击进入个人空间，右侧微信文件夹超出屏幕

[bug]在选中一个文件的情况下，右键点击另外一个文件时，焦点没有切换，弹出的菜单栏操作对选中的文件有效

[bug]选中一个文件长按，松开后，文件被移动到当前目录的第一个文件夹中

[bug]968 插入u盘及复制粘贴文件时，弹出的黑框提示太丑。需修改
### 一般
[bug]永久删除文件：复制或移动文件和文件夹(最下面一段话):

您不能将文件复制或移动到只读文件夹(系统文件)。有些文件是只读的以防止您更改其内容。您可以通过更改文件权限来更改文件的只读状态。

[bug]u盘卸载后，界面没有刷新

# 桌面：
### 重要
[bug] 983 桌面上不支持 ctrl+a 全选 20170112版本  

[bug] 984 桌面-新建文件（txt,doc,xls,ppt）,按enter打开时均提示“无法打开文件，此文件内容已被损坏”（默认用micro-office打开）。使用右键打开方式打开新建文档可使用WPS打开txt,doc,xls三类文档(ppt两种办公软件均无法打开)(高 -2017-1-12---王之旭 )  

### 一般
[bug] 

# Firefox ：
### 重要
[bug]光标还在，输入法以及删除操作均无效，需关闭浏览器并重新打开

[bug]点击地址栏，页面消失(待讨论)

[bug]github里用键盘上上下左右键控制光标，上和左键，一按会页面置顶，下和右键是没问题的，但是控制完光标后无法输入字，需要鼠标重新点一下才可输入

[bug]浏览器偶尔出现自动消失情况（待定）

[bug]浏览器中，在搜索框中输入几个文字，如在下面弹出的猜测信息中含有自己需要内容，按方向的上下键无法选择对应输入信息（只能鼠标点击）。

[bug]967 Fennec无右键菜单功能(对闭源软件可能都有此问题）
### 一般
[bug]支持触摸板放大缩小功能（设备相关）；

[bug]18项， 支持页面收藏功能，但收藏夹里的部分DEMO图无显示，只能看底下的文字；

[bug]33 项，支持页面手机 ＆ pc切换模式 (请点击设置窗口中 “request destop site “ 按钮进行手机和桌面的切换) （切换中会出现大小窗口不适配BUG）;

[feature]不支持邮箱图片放大，下载功能；   －－－－－－建议提高优先级

[feature]网页图片无法复制、无法保存，右键单击图片无任何反映（2016-1-5）

# WPS邮箱
### 重要

### 一般
[bug]wps邮箱，查看邮件时，当选择有几个回复的邮件时，左侧显示不再是邮件列表（变为登录背景）

[feature]附件有支持云文档的上传，但无法把文档上传至云文档，没选择上传的选项按钮；

[bug]浏览器中操作邮箱，偶尔弹出wps邮箱应用（原生浏览器， 126邮箱，个别机器出现，本地未能复现）

[faq] 遇到无法登录时：
WPS邮箱初次登录对于有的邮箱是登录不上的，需要去Web网页版邮箱进行开通设置，步骤如下：网页版邮 —— > 设置 —— > 左侧列表中点击“POP3／SMTP／IMAP“—— > 在中间面板中√的地方都打上√ —— > 保存 —— > 再在左侧列表中点击 “客户端授权密码“ —— > 在中间面板设置“开启“  —— > 自行设置授权密码 —— > 完成后重新登录即可。

[feature]给自己发送邮件收不到；

# 谷歌输入法
### 重要
[bug]不同应用进行切换时，中英文切换失效。（如WPS正常输入中文，此时切到任务栏其他应用，如APPSTORE，下载一应用。返回到WPS后发珊中英文失效） 发现时间:（bugId:851-高 -2016-12-12---李兵）

[bug]多应用交互后，输入法默认英文输入，需要每次shift切换（2016-1-04）；

[bug]firefox经常会出现切换不了中文，需要关闭重开才可切换（2016-1-04）；

[bug]微信聊天使用@符号，不弹出联系人信息。无法选择要@的人员---------（bugid:650 -高--2016-11-21-- 李兵） 

[bug]shift+":"或“＠“等符号时，反应迟钝，需要长按shift加符号（2016-1-04）；

### 一般
[feature]输入时不跟随光标移动( 缓--李兵) 

# WPS office
### 重要

### 一般
[bug]word文档中内容不能按大小窗口比例缩放，点右上角“- 口x“ 这个标志，小窗口和最大话的对比，内容也应该按比例缩小，但是只是显示小窗口的大小，内容确

实大窗口的比例。

[bug]excel有插入图表的功能，但除了条形图，其他图表插入不上；

[bug]ctrl+滚轮对字体的放大和缩小不好用；

[bug]缺少关闭文档时的提示保存与否, 点击右上角关闭时，没提示是否保存，默认的是不保存。

[feature]无格式刷功能；

[feature]无选择粘贴方式,复制文本右键粘贴时会有选择粘贴方式（带格式粘贴、不带格式粘贴、图片式粘贴等）;

[feature]缺少多选文字，快捷键ctrl的两处或多出选择,键盘ctrl+鼠标的多处片选;

[feature]目前尚不支持右键插入单元格功能；

[feature]无添加水印功能,pc端有此功能，我们没有;

[feature]word文档中不能插入excel快捷方式，PC版的有此功能，我们没有；

[feature]ctrl+p打印，word支持，excel和ppt不支持


# 图库
### 一般
[bug]左右切换可以鼠标滑动，但键盘的左右键不管用；

[feature]照片预览时缺少“第x页-共x页“的提示信息；