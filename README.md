 # My SublimeText Settings

## 配置SublimeText

1. <a href="http://www.sublimetext.com/" target="_blank">下载安装SublimeText</a>

2. 打开SublimeText，`Preferences -> Browse Packages` 文件夹内

3. git下载配置包

```shell
    git init
    git remote add origin git@github.com:wilon/Sublime-Text-Settings.git
    git pull
    git merge origin master
```

4. 配置 License、Preferences

    `cp -f $packages/Local/License (PLATFORM).sublime_license $packages/Local/License.sublime_license `

    `cp -f $packages/User/Preferences (PLATFORM).sublime-settings $packages/User/Preferences.sublime-settings`

5. 重启 SublimeText，等待插件配置

## 插件推荐：

* **Emmet**

emmet快速编辑html。

* **SublimeLinter**

自动识别错误，并标红。
再安装**SublimeLinter-php**，需配置里，`path->windows->"F:\\xampp\\php"`，右键设置`fill\no clo..`

* **Alignment**

一键代码对齐

* **Snippets**

自定义代码片段(ST3自带)

* **DocBlockr**

快速注释,（函数上方）输入`/*`或`/**`，按enter。
设置单行注释按enter不注释`"jsdocs_extend_double_slash": false`

* **Insert Nums**

快速插入排列数字、字母，方法如下——
    1. 按住`ctrl`，鼠标点击左键，使光标活动在多行。若不行则有按键冲突。
    2. 按`ctrl+alt+n`，OK了，也支持字母，下面输入a 1 。

* **Side Bar**

左侧文件右键增强。

* **TabsExtra**

标签右键功能增强。

* **SublimeCodeIntel**

`alt+左键`点击函数，自动跳转
`ctrl+shift+space`自动提示函数参数
自动加载提示自写函数名，但对php自带函数不如默认，Open file: `$Packages\SublimeCodeIntel\SublimeCodeIntel.py`, The 1401 line, Modify ''%s〔%s〕'' to '%s'。

* **Tag**

html标签格式化等操作

* **jQuery**

jQuery方法自动完成，[下载snippets包](https://github.com/SublimeText/jQuery/)，放入`$Packages/user/sbulime-snippets`

* **FavoriteFiles**

收藏夹。

* **Bracket Highlighter**

匹配括号，括号内容操作

* **Function Name Display**

显示函数参数，SublimeCodeIntel已有此功能

* **IMESupport**

中文输入法光标跟随

* **ColorHighlighter**

文本内颜色高亮显示，选择颜色

* **OpenInclude**

快速打开文件，只要有路径

* **Smarty**

更改smarty定界符 `$Packages/User/Smarty.tmPreferences`

## 汉化指南

1. 菜单汉化

    下载 [汉化文件](https://github.com/wilon/Sublime-Text-Settings/tree/master/Packages/Default)

    放入`$Packages/Default/`下

2. 插件汉化

    2.1 源码包：打开插件目录，翻译修改`配置文件`相应参数即可

    2.2 Package包：压缩工具打开包，将里面配置文件放入 `$Packages/插件名/`里，翻译修改参数即可

------
<a name="packages">1</a>: *$Packages*为菜单栏`Preferences->Browse Packages`所打开的文件位置

