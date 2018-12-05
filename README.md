# mac-iterm2-zsh-tutorial

## 1、Mac必备开发神器
下面介绍几款Mac下必备开发神器：iTerm2、Zsh、Homebrew、Ohmyzsh。

## 2、iTerm2

#### 2.1、什么是iTerm2？
iTerm2是iTerm的替代品，也是iTerm的继承者。 它适用于使用macOS 10.10或更高版本的Mac。 iTerm2将iTerm带入了您从未想过的功能的现代时代。

#### 2.2、下载安装iTerm2
下载地址[在这里](https://www.iterm2.com/)，安装就不用多讲了。

#### 2.3、常用快捷键

```
⌘+N、⌘+T、⌘+↔、⌘+F、⌘+W 这几个快捷键就不解释了。

⌘+D 垂直分屏、⌘+⇧+D 水平分屏、⌘+⌥+↑↓↔ 切换分屏。

⌘+↩全屏、⌘ + R 清屏。

⌃+A/E 行首/尾、⌃+R 查询历史命令。

⌥+↔ 左右跳过单词。
```

记住这些就差不多了，脑容量有限，应能省则省。

## 3、什么是Zsh、Ohmyzsh？
Zsh 是一款功能强大终端（shell）软件，既可以作为一个交互式终端，也可以作为一个脚本解释器。它在兼容 Bash 的同时 (默认不兼容，除非设置成 emulate sh) 还有提供了很多改进，例如：
更高效
更好的自动补全
更好的文件名展开（通配符展开）
更好的数组处理
可定制性高


## 4、什么是Homebrew？
下载地址[在这里](https://brew.sh/)，安装就不用多讲了。

#### 4.1 安装Homebrew
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

#### 4.2 brew常用命令
```
搜索：brew search mysql

查询：brew info mysql #主要看具体的信息，比如目前的版本，依赖，安装后注意事项等

更新：brew update #这会更新 Homebrew 自己，并且使得接下来的两个操作有意义——

检查过时（是否有新版本）：brew outdated #这回列出所有安装的软件里可以升级的那些

升级：brew upgrade #升级所有可以升级的软件们

清理：brew cleanup #清理不需要的版本极其安装包缓存

更新：brew update          #  Homebrew 的信息

升级：brew outdated        # 看一下哪些软件可以升级

升级指定的：brew upgrade <xxx>   # 如果不是所有的都要升级，那就这样升级指定的
 
升级并清理：brew upgrade; brew cleanup    # 如果都要升级，直接升级完然后清理干净
```

## 10 、引用
1. [Mac 小记 — iTerm2、Zsh、Homebrew](https://www.cnblogs.com/youclk/p/8125305.html)

2. [Mac 从零开始配置开发环境](https://www.codecasts.com/series/setup-a-mac-dev-machine)

3. [Zsh(简体中文)](https://wiki.archlinux.org/index.php/Zsh_(%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87))