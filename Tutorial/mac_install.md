# MacOSX安装HBuilderX

## 安装

如图，将HBuilderX`拖`到Applications，才是正确的安装姿势。

<img src="/static/snapshots/tutorial/install_mac.jpeg" />

> MacOSX，软件必须安装到`/Applications`目录，如未安装到此目录，可能会出现插件安装失败、项目创建失败等问题。

## 启动问题

某些情况下，MacOSX HBuilderX无法启动，解决方法如下：

- 重启电脑
- 配置文件损坏，导致HBuilderX无法启动，重置配置文件即可。

## 重置配置文件

> 如HBuilderX内，有重要文件，删除前，先备份

配置文件目录：`$HOME/Library/Application\ Support/HBuilder\ X`

**请注意：** mac上，如果路径包含空格，需要`\`进行转义

```shell
# 备份配置文件，如不需要，请略过
cp -rf $HOME/Library/Application\ Support/HBuilder\ X   $HOME/Desktop/HX

# 直接删除配置文件目录
rm -rf $HOME/Library/Application\ Support/HBuilder\ X
```