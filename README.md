# baota
宝塔使用

最近宝塔面板升级到了7.8版本，违背了宝塔开源协议，竟然在免费版的源码里面加入了加密的授权验证模块。除此之外，7.8版本使用各种方法均无法绕过面板强制绑定账号，如果不绑定账号插件就无法下载。

因此这里分享一下7.7版本的安装脚本，是官方免费版的。

安装命令：

wget -O install.sh  https://raw.githubusercontent.com/expfukck/baota/main/install_6.0.sh && bash install.sh


升级(降级)到7.7版本命令：

curl https://raw.githubusercontent.com/expfukck/baota/main/update6.sh|bash
