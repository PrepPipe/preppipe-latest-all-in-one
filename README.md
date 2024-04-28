# 语涵编译器整合包仓库(All-in-one release repo for PrepPipe Compiler)

该仓库是语涵编译器的整合发布包，包含了语涵编译器的各个部分以及所有依赖。整合发布包包含：
* 主程序 (`preppipe-python`, 链接：[GitHub](https://github.com/PrepPipe/preppipe-python) 或 [Gitee](https://gitee.com/preppipe/preppipe-python))
* 启动器（图形界面）(`preppipe_gui`, 链接：[GitHub](https://github.com/PrepPipe/preppipe_gui) 或 [Gitee](https://gitee.com/preppipe/preppipe_gui))
* 主程序所需的 [ffmpeg](https://ffmpeg.org/)
* 以及其他依赖的 DLL、第三方库等

除了程序外，本仓库还包含语涵编译器测试所使用的素材(在`TestAssets`目录下)，素材仅供测试语涵编译器使用。

(墙内请点Gitee的链接，墙外或者可以科学上网的话可以点GitHub链接)

目前该库内的程序包只有`windows-x64`，支持64位 Windows 10/11，不支持更早的 Windows 版本。其他系统如有需要的话请联系开发者。下载后请双击 `preppipe_gui.exe` 运行启动器。

## 如何下载

请在页面右侧 `Releases` 中选择最新版本。

## 下载后如何使用
使用方法：
1. 将ZIP压缩包中您需要的程序部分（如`preppipe-windows-x64/windows-x64`）到任意目录下
2. （可选）将 `windows-x64` 改成您想要使用的目录名
3. 双击该目录下的 `preppipe_gui.exe` （紫色图标）运行启动器，或者以其他您希望的方式使用主程序 `preppipe_cli.exe`。

注：压缩包根目录下的其他文件、文件夹（包括`TestAssets`中的素材）不是程序运行所必需的，下载后可以删除。

## 反馈问题或者只是想联系我们

语涵编译器 QQ群：732421719

如需使用 issue 请在 GitHub 上加 issue，谢谢！
