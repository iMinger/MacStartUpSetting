#Mac 装机经历


1.科学上网工具：

 - [ClashX](https://github.com/yichengchen/clashX)
 - [Shadowsocks](https://github.com/shadowsocks/ShadowsocksX-NG/releases/) (已弃用)
 - [V2Ray](https://github.com/v2ray/v2ray-core/releases) (已弃用)
 
 目前购买的服务在`https://portal.shadowsocks.nz/aff.php?aff=24033`
 可以科学上网之后，打开终端
 ```
 touch .bash_profile
 vim .bash_profile
 ```
 然后在里面写上
 ```
 # 终端开启代理吗，关闭代理命令
function setproxy() {
    # export {HTTP,HTTPS,FTP}_PROXY="http://127.0.0.1:3128" 也可以设置http代理
    # 设置socks5代理会比较好
    export ALL_PROXY=socks5://127.0.0.1:7890
    echo -e "已开启代理"
}

function unsetproxy() {
    # unset {HTTP,HTTPS,FTP}_PROXY
    unset ALL_PROXY
    echo -e "已关闭代理"
}

# 设置 'curl ip.gs'命令 的别名ip
alias ip="curl ip.gs"
 ```
 
 ***注意： 这里的端口号要和你的翻墙工具里监听 socks的端口号一致。***
 保存并推出，然后 source .bash_profile使得生效.
 然后，就可以使用别名 setproxy 来使得终端走代理了。
 
2.安装 ruby
[MacOS 下安装 Ruby](https://liangbogopher.github.io/2018/04/15/mac-upgrade-ruby)
3.安装 cocoapods
[iOS安装CocoaPods详细过程](https://www.jianshu.com/p/9e4e36ba8574)
[CocoaPods安装方法-2019.10.11](https://www.jianshu.com/p/f43b5964f582)
 

 
 
 


[item2+oh my zsh 终端体验](https://segmentfault.com/a/1190000014992947)

