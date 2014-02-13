#lessToSM
因为如果想要在chrome里面编辑查看less源文件，是需要相应的sourcemap文件。这个工具可以即时的将相应的less文件编译成css和sourcemap文件。

##依赖
[nodejs](http://nodejs.org/)

lessc > 1.5.0

##说明
* auto.bat: 实现双击即可启动本工具，否则需要启动命令行来运行主脚本
* lessToSM: nodejs的脚本。
    * 将css文件通过lessc编译成相应的css和sourcemap文件，如需要在不同的路径可以实现修改源码实现。
    * 文件监控功能，如果less文件发生改变能实时编译。

##Contact
If you have any questions or suggestions that don't fit GitHub, send them to [@choizhang](https://github.com/choizhang)