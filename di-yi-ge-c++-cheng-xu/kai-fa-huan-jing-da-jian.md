# 开发环境搭建

## Windows

todo

## Mac

### 编译器安装

对于使用 Mac 电脑的朋友，可以先安装 Xcode 和 Homebrew，然后通过 Homebrew 安装 llvm

* Homebrew 官网：[https://brew.sh/](https://brew.sh/)
* Homebrew 国内安装脚本：[https://gitee.com/cunkai/HomebrewCN](https://gitee.com/cunkai/HomebrewCN)

通过 Homebrew 安装 llvm，直接在 Terminal 中执行 `brew install llvm@16` 或 `brew install llvm`，安装成功之后，分别执行 `llvm-config --version` 和 `clang++ --version` 来查看当前版本，在我的电脑上这两行命令输出如下：

```bash
$ llvm-config --version
16.0.5

$ clang++ --version
Homebrew clang version 16.0.5
Target: arm64-apple-darwin21.6.0
Thread model: posix
InstalledDir: /opt/homebrew/opt/llvm/bin
```



## Ubuntu

todo



## IDE 安装

IDE 本书中使用的是 CLion，这款 IDE 在 Windows、Mac、Ubuntu 下都可以使用。推荐直接安装 JetBrains ToolBox，然后通过 JetBrains ToolBox 来安装 CLion

* JetBrains ToolBox 下载地址：[https://www.jetbrains.com/toolbox-app/](https://www.jetbrains.com/toolbox-app/)
