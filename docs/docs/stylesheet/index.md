---
comments: true
icon: material/language-css3
---

# CSS - StyleSheet

> 位置: `assets/styles`

## `app.css`

`*`: 定义字体

`body`: 定义 `body` 的样式

## `boot.css`

`*`: 定义 `--grayboot` 和 `--boot` 的相关变量、字体、选择和光标

`html`: 定义 `html` 的样式

`body`: 定义 `body` 的样式

`p[logo]`: 定义 Apple Logo 的样式

`img[logo]`: 定义禁行符号的样式

`div[frame]`: 定义进度条以及 Apple 支持文字外部框架的样式

`div[processframe]`: 定义进度条的样式

`div[process]`: 定义进度的样式

`p[state]`: 定义 Apple 支持文字的样式

## `cursor.css`

`*`: 定义光标

## `desktop.css`

`*`: 定义 `--finderbar` 相关变量和字体、光标、选择以及字间距

`body`: 定义 body 的样式

`body[gradient]`: 定义背景渐变的 body 样式

`div[finderbar]`: 定义访达栏的样式

`div[finderbar][noblur]`: 定义背景不模糊的访达栏的样式

* `p`: 定义访达栏文字的样式

`div[menus]`: 定义访达栏左部菜单栏的样式

* `p`: 定义菜单栏文字的样式
* `p[logo]`: 定义菜单栏 Apple Logo 的样式
* `p[appname]`: 定义菜单栏 App 名称的样式
* `p:last-child`: 定义菜单栏最后一个文本的样式

`div[controls]`: 定义访达栏右部功能栏的样式

* `p`: 定义功能栏文字的样式

`iframe`: 定义 iframe 的样式

`iframe[wallpaper]`: 定义墙纸的样式

`iframe[dock]`: 定义 Dock 栏的样式

`iframe[window]`: 定义窗口的样式

## `dock.css`

`*`: 定义字体

`@media screen`: 定义 Dock 在不同宽度下的显示方式

`body`: 定义 body 的样式

`hr`: 定义分割线的样式

`div[appname]`: 定义 App 名称的样式

* `::after`: 定义下方小角的样式

`div[dock]`: 定义 Dock 栏的样式

* `div[container]`: 定义 App 容器的样式
* * `div[light]`: 定义指示灯的样式

`img`: 定义图片的样式

`p`: 定义文字的样式

## `firmware.css`

`body`: 定义 body 的样式

`img[logo]`: 定义闪烁文件夹图标的样式

`div[frame]`: 定义 Apple 支持文字外部框架的样式

`p[state]`: 定义 Apple 支持文字的样式

## `font.css`

`@font-face`: 定义字体

`body`: 定义字体

## `launchpad.css`

`*`: 定义字体

`body`: 定义 body 的样式

`@keyframes`: 定义关键帧动画

`div[launchpad]`: 定义启动台的样式

`div[bg]`: 定义启动台背景的样式

`div[container]`: 定义启动台内部 App 容器的样式

* `img`: 定义 App 图标的样式
* `p`: 定义 App 名称的样式

`div[search]`: 定义搜索框的样式

* `img`: 定义搜索图标的样式
* `p`: 定义搜索文字的样式

## `logon.css`

`*`: 定义 `--boot` 相关变量以及字体、光标和选择

`body`: 定义 body 的样式

`div[overlay]`: 定义渐变遮罩的样式

`*[relative]`: 定义 `position: relative` 的样式

`p[time]`: 定义时间大文字的样式

`p[date]`: 定义日期大文字的样式

`div[login]`: 定义下方容器的样式

`img[icon]`: 定义用户头像的样式

`p[username]`: 定义用户名文字的样式

`input[password]`: 定义密码输入框的样式

* `::placeholder`: 定义提示文字的样式

`p[tip]`: 定义下方提示文字的样式

`div[svgframe]`: 定义等待动画容器的样式

## `manager.css`

`body`: 定义 body 的样式

`div[manager]`: 定义 div[manager] 的样式

`div[option]`: 定义 div[option] 的样式

`img[icon]`: 定义 img[icon] 的样式

`img[selector]`: 定义 img[selector] 的样式

`p[text]`: 定义 p[text] 的样式

## `oobe.css`

`*`: 定义 * 的样式

`a[link]`: 定义 a[link] 的样式

`body`: 定义 body 的样式

`div[bottom-content]`: 定义 div[bottom-content] 的样式

`div[container]`: 定义 div[container] 的样式

`div[inner-content]`: 定义 div[inner-content] 的样式

`div[main]`: 定义 div[main] 的样式

`hr`: 定义 hr 的样式

`img`: 定义 img 的样式

`p`: 定义 p 的样式

`p[description]`: 定义 p[description] 的样式

`p[license]`: 定义 p[license] 的样式

`p[subtitle]`: 定义 p[subtitle] 的样式

`p[title]`: 定义 p[title] 的样式

`widget-button`: 定义 widget-button 的样式

## `recovery.css`

`div[toolschild]`: 定义工具选项的样式

* `img`: 定义图标的样式
* `p[text]`: 定义描述文字的样式
* `p[title]`: 定义工具标题的样式

`div[usefultools]`: 定义实用工具容器的样式

## `window.css`

`*[brightness]`: 定义亮度的样式

`*[opacity]`: 定义半透明的样式

`div[green]`: 定义最大化窗口的样式

`div[left]`: 定义左侧容器的样式

* `p[title]`: 定义左侧容器标题文字的样式

`div[leftchild]`: 定义左侧容器选项的样式

* `img[height]`: 定义窄图的样式
* `img[largewidth]`: 定义超宽图的样式
* `img[middle]`: 定义等长宽的样式
* `img[width]`: 定义宽图的样式
* `p`: 定义 p 的样式
* `.selected`: 定义已选择选项的样式

`div[red]`: 定义关闭按钮的样式

`div[right]`: 定义右侧容器的样式

`div[window]`: 定义窗口的样式

`div[wintools]`: 定义窗口左上方功能按钮的样式

`div[yellow]`: 定义最小化按钮的样式