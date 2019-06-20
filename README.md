# Tool
package


enigmavbQT打包工具：使用方法
生成的程序运行正常之后，找到项目的生成目录，比如 项目源码路径：C:\QtPros\hellomw\ 。
它的项目生成目录是 C:\QtPros\build-hellomw-Desktop_Qt_5_4_0_MinGW_32bit-Release\ 。
进入这个文件夹，在进入它的子文件夹 release 里面，找到 hellomw.exe，将这个exe 复制到一个新的单独的文件夹里用于发布，比如存到 D:\hellomw\ 文件夹里面。

然后从开始菜单打开 Qt 命令行，输入命令：cd /d D:\hellomw
然后使用 windeployqt 工具命令：windeployqt hellomw.exe

参考网址：https://blog.csdn.net/windsnow1/article/details/78004265/

# QT
Password requirements
Minimum 7 characters
Cannot contain your email address or name
Must include at least three of these four types: lowercase letters, uppercase letters, digits, symbols
Accepted characters: a-z, A-Z, 0-9, space and symbols !"#/()=?@${[]}\,.-_<>|;:'*^~+
 Hg .... 9;
