参考 http://dockerfile.github.io/#/ubuntu

此镜像修改主要是为了本地化而修改apt-get的源，默认使用163的包镜像。

此外，还默认安装好byobu curl git htop man unzip vim wget和software-properties-common常用工具。为了便于使用add-apt-repository ppa:webupd8team/java这种方式来添加第三方源。
