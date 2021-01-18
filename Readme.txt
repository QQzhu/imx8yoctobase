准备：
sudo apt-get update
sudo apt-get install gawk wget git-core diffstat unzip texinfo gcc-multilib build-essential chrpath socat libsdl1.2-dev
sudo apt-get install libsdl1.2-dev xterm sed cvs subversion coreutils texi2html docbook-utils python-pysqlite2 help2man make gcc g++ desktop-file-utils libgl1-mesa-dev libglu1-mesa-dev mercurial autoconf automake groff curl lzop asciidoc
sudo apt-get install u-boot-tools

如果有可以忽略：
git config --global user.name xxx
git config --global user.email xxx@xxx.com
git config –list


开始执行
DISTRO=fsl-imx-xwayland MACHINE=imx8qxpc0mek source imx-setup-release.sh -b imx8qxpc0mek_xwayland
bitbake imx-image-full