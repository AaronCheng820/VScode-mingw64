# VScode-mingw64
一个VScode+mingw64的环境配置笔记

官网下载VScode安装https://code.visualstudio.com/

安装完成后在界面的应用拓展中搜索c/c++插件，同时可以搜索Chinese以安装汉语语言包

然后在source forge网站下载并安装mingw64 https://sourceforge.net/projects/mingw-w64/files/latest/download 处理器架构x86

安装完成后（默认在c根目录）将bin目录添加至系统环境变量（这样在编程时头文件的应用include就不会报错了）

右键windows，打开power shell，输入gcc和g++，没有输入文件显示说明安装成功

完成上述操作，进入vscode建立工作区文件夹，.vscode文件夹中需要三个文件配置（c_cpp_properties.json/launch.json/tasks.json），这里提供已经写好的文件供参考，也可在相应的github页面进行查询。这里需要说明的是，在c_cpp_properties.json/launch.json两个文件中的调试器的路径需要更改，即mingw64存放gdb.exe等的文件路径。

GIT下载安装详细教程https://www.jianshu.com/p/a152f82c5e4a

