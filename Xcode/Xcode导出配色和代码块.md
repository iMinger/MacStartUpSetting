# Xcode导出配色和代码块
为了让我们将Xcode的一些配置快速的从一台电脑安装到另外一台电脑，减少不必要重新配置的时间，所以将一些配置提取出来，用时直接将这些配置放置到对应的位置即可。

## 导出代码块
代码块保存在 `~/Library/Developer/Xcode/UserData/CodeSnippets` 下，进入该目录可以看到每个代码块都被存储为一个文件，后缀名为： `.codesnippet`.我们可以将代码块文件或其所在的目录整体拷贝出来，重新安装Xcode之后再将这些文件拷贝回去`~/Library/Developer/Xcode/UserData/CodeSnippets`，然后重启Xcode即可。
## 导出字体配色方案
当我们修改了`xcode`的配色方案后，会在`~/Library/Developer/Xcode/UserData/FontAndColorThemes`目录下产生一个对应的配置文件，后缀名为：`xccolortheme`。 将这些配色方案拷贝出来，然后重新安装xcode之后再将这些文件拷贝回去，重启Xcode即可。