# awesome_kde_theme
一系列美观的kde主题。

[TOC]

# KDE 主题的安装方式

由于在 KDE 设置里安装的主题在网速不好的情况下安装容易出问题，所以推荐的三种安装方式为：

- 使用包管理器安装：这个是最推荐的，可以一次性安装一套主题。安装和更新都比较方便。
- 使用 Github 手动安装。
- 使用 [OCS-URL](https://www.opendesktop.org/p/1136805/) 或者 [Pling-Stroe](https://www.opendesktop.org/p/1175480/) 安装：这种安装在安装一套主题的时候比较麻烦，但是优点是不会安装不会出问题。
- 使用 Discover 安装：KDE 自带的软件管理器，但是网速不好的时候安装主题容易出问题。

# 配置主题需要了解的知识

KDE 的主题配置一般为：

- Plasma 样式：决定了你面板（默认面板和 latte dock 面板）和小部件的颜色、图表、边框（boder）样式。
- 应用程序风格：决定了你界面中按钮等小部件的样式（颜色、大小边框、对齐方式等）。推荐使用 Kvantum Manager
- 窗口装饰：决定了程序最大化/最小化等按钮的样式。
- 颜色：决定了程序小部件的背景颜色
- 图标：决定了应用程序图标、dolphin 中文件的图标

需要注意的是 `窗口装饰` 内的 `主题默认边框`，如果设置的边框大小和主题边框大小不一样，就会导致程序上部分和下部分错位的情况。

窗口装饰推荐使用 svg 图标而不是 png 图标，因为 png 图标在 KDE 开启了 `模糊透明窗口` 的情况下可以看到程序四角有模糊的图片。


# 配置主题可能用到的资源：

- Github：https://github.com/topics/plasma-desktop
- https://store.kde.org/browse/cat/
- [OCS-URL](https://www.opendesktop.org/p/1136805/) 或/和 [Pling-Stroe](https://www.opendesktop.org/p/1175480/)
- Discover
- Kvantum Manager
- 你的包管理器

# 全局主题

## 亮色主题

- [Aritim-Light](https://github.com/Mrcuve0/Aritim-Light/tree/master/KDE/lookAndFeel)：这个是我用过最多的一个主题。`KDE` + `GTK` + `Kvantum` 一整套主题。窗口装饰的颜色和窗口背景的颜色一致，看情况非常漂亮，而且也没有滥用颜色和特效。唯一的缺点是高亮字体看不清。这个推荐使用 Discover 安装。
- [Adapta KDE](https://github.com/PapirusDevelopmentTeam/adapta-kde)。KDE + [GTK](https://github.com/adapta-project/adapta-gtk-theme) 主题。非常有层次感。我觉得在 Gnome 上看起来更好看。

## 暗色主题
- [Aritim-Dark](https://www.pling.com/p/1281836/) 。颜色有点暗，但是整体还是很不错的。
- [Arc KDE](https://www.pling.com/p/1167640/)。颜色非常不错，而且还有配合 `[GTK](https://github.com/horst3180/arc-theme)` 和 `[Firefox](https://github.com/horst3180/arc-firefox-theme)` 使用的主题。这个主题在 Gnome 上非常好看，KDE 上则窗口装饰看起来比较小
- Breath2。Manjaro 自带的主题，也非常好看，kde + gtk 一套带走。可惜网上没有资源，需要自己提取。


# 图标

- [McMojave-Circle](https://www.opendesktop.org/p/1305429)：本身是一个全局主题，但是它的图标更好看
- [Numigsur](https://www.opendesktop.org/p/1414301)：扁平风格的类 MacOS 图标。很不错。
- [UOS](https://www.opendesktop.org/p/1349376)：deepin v20 自带的图标主题，也超级好看。
- [Tela-icon-theme](https://www.opendesktop.org/p/1279924)：扁平风格主题
- [Vimix icon theme](https://www.opendesktop.org/p/1273372)：Gnome 上我用的时间最长的主题。配合它的主题看起来很有层次感，但是在 KDE 下主题表现欠佳。
- [Papirus](https://www.opendesktop.org/p/1166289)：这个图标的层次感也很好。
- [Dexie Icon](https://www.opendesktop.org/p/1324180/)。胖乎乎的图标看起来很好看。我比较喜欢 teal 版本的。

# 字体

- Noto Sans CJK SC：可用用于界面。字体表现很不错
- Fira Code：可用于 Konsole 和 代码编辑器。连体字看起来听舒服的。

# 观感

观感一般推荐使用 kvantum 设置与主题配套的主题，此外，以下第三方观感也可用：

- [Lightly](https://github.com/Luwx/Lightly) ：一个现代化的观感
- QtCurve：一个可高度自定义的观感

我个人更喜欢 Lightly ，其次是 Kvantum。

# 一些落选的，但是依然很好看的主题
- [WhiteSur](https://store.kde.org/p/1398840/)。仿 MacOs Big Sur 的主题，非常大气好看。推荐使用 Github 安装，安装后需要该 `窗口边框`。落选的原因是窗口装饰使用的是 png 图标，程序四角可看到模糊的透明图片，而且窗口装饰和小部件背景颜色不匹配。
- [DeepinV20-white](https://store.kde.org/p/1413901/)。虽然我觉得 DeepinV20 不好看，但是把它挪到 KDE 还是很好看的。落选理由同上。


总的来说，Gnome 的主题看起来有层次感更好看，而 KDE 的主题看起来精致更好看。Gnome 增删主题更简单，KDE 要得到一个更好看的主题比较麻烦。

一般配置主题的步骤为：全局主题 -> Kvantum Manager -> 应用程序风格 -> 颜色 -> 图标
