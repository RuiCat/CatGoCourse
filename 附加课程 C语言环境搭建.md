# C/C++ 环境搭建

* 配置安装
    > Zsh 命令窗口运行安装环境
    1. 更新系统
        > pacman -Syyu
    2. 安装 C/C++ 环境,回车全部安装
        > pacman -Syyu mingw-w64-x86_64-toolchain mingw-w64-x86_64-cmake

* 配置环境 ~/.zshrc 文件

    ``` bash
    # C/C++ 设置
    export PATH=${PATH}:/mingw64/bin
    alias make=/mingw64/bin/mingw32-make
    ```

* 插件安装

    1. [C/C++](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools)
    2. [CMake Tools](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cmake-tools)
