#MySublimeText
clone下代码，运行sublime_text.exe即可
已汉化破解

## 插件推荐：
> * Emmet:
        emmet快速编辑html。
> * SublimeLinter:
        自动识别错误，并标红。
        再安装SublimeLinter-php，需配置里，path->windows->"F:\\xampp\\php"，右键设置fill\no clo..
> * Alignment:
        一键代码对齐
> * Snippets:
        自定义代码片段(ST3自带)
> * DocBlockr:
        快速注释,（函数上方）输入'/*'或'/**'，按enter。
        设置单行注释按enter不注释"jsdocs_extend_double_slash": false
> * Insert Nums:
        快速插入排列数字、字母，方法如下——
        1. 按住ctrl，鼠标点击左键，使光标活动在多行。若不行则有按键冲突。
        2. 按ctrl+alt+n，OK了，也支持字母，下面输入a 1 。
> * Side Bar:
        左侧文件右键增强。
> * TabsExtra:
        标签右键功能增强。
> * SublimeCodeIntel:
        alt+左键点击函数，自动跳转
        [ctrl+shift+space]自动提示函数参数
        自动加载提示自写函数名，但对php自带函数不如默认，Open file: $Packages[^Packages]\SublimeCodeIntel\SublimeCodeIntel.py, The 1401 line, Modify ''%s〔%s〕'' to '%s'。
> * Tag:
        html标签格式化等操作
> * jQuery:
        jQuery方法自动完成，下载snippets包https://github.com/SublimeText/jQuery/，放入$Packages[^Packages]/user/sbulime-snippets
> * FavoriteFiles:
        收藏夹。
> * Bracket Highlighter:
        匹配括号，括号内容操作
> * Function Name Display:
        显示函数参数，SublimeCodeIntel已有此功能
> * IMESupport:
        中文输入法光标跟随
> * ColorHighlighter:
        文本内颜色高亮显示，选择颜色
> * OpenInclude:
        快速打开文件，只要有路径
> * Smarty:
        更改smarty定界符 $Packages[^Packages]/User/Smarty.tmPreferences

## 汉化指南
    1. 无插件汉化
        下载[所有文件](https://coding.net/u/wilon/p/MySublimeText/git/tree/master/Data/Packages/Default) 
        放入$Packages[^Packages]/Default/下 
    2. 插件汉化
        源码包：打开插件目录，翻译修改配置文件里$caption[^caption]参数即可
        package包：压缩工具打开包，将里面配置文件放入$Packages[^Packages]/插件名/里，翻译修改$caption参数即可


[^Packages]: $Packages为菜单栏Preferences->Browse Packages所打开的文件位置
[^caption]: $caption为json文件的键
