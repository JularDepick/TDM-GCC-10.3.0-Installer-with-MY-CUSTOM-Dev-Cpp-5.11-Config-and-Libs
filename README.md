# TDM-GCC-10.3.0-Installer-with-MY-CUSTOM-Dev-Cpp-5.11-Config-and-Libs

## 初衷
- 原版的 Dev-Cpp-5.11 具有较好的简洁性和快捷性，但携带的编译器版本较低，于是我创建了这个仓库，整合Dev-Cpp-5.11编辑器和高版本编译器，不过没有实现一键安装到位，仍需要开发者手动操作配置。
- 以后应该会出一个整合安装包，一键安装带有优秀编译器及其配置的Dev-Cpp-5.11编辑器，降低配置门槛。

## 适用于
- Windows_x64
- C/C++ 语言

## Releases中含有:
- 打包安装器.exe，运行时建议安装到独立的目录 D:/TDM_GCC 下。
- 资源包.zip，建议解压到独立的目录 D:/TDM_GCC 下。
- Dev-Cpp-5.11安装包.exe

## 使用指南
0. 如果您没有安装Dev-Cpp-5.11，可以先安装它
1. 运行安装器.exe或解压资源包.zip到路径 D:/TDM_GCC 下
2. 运行 Dev-Cpp-5.11 一次，以创建软件配置文件
3. 将目录 D:\TDM-GCC\tdm-gcc-10.3.0-copyright\My-Dev-Cpp-5.11-ini-Template 下的文件复制覆盖到目录 C:\Users\您的用户名\AppData\Roaming\Dev-Cpp (Dev-Cpp-5.11配置文件默认目录)下
4. 再次运行 Dev-Cpp-5.11

## Dev-Cpp-5.11 个性化配置说明
- 依据我的习惯配置了编辑器相关属性，适用于绝大部分开发者的习惯
- 提供了以下四个我惯用的编译器配置：
  - Release
  - Debug
  - Profile
  - Release-GUI
- 如果只想要编译器配置，则只需复制文件 devcpp.ini 内容中的 [CompilerSets_0] 到 [CompilerSets_3] 标签内容到对应的Dev-Cpp-5.11配置文件即可
- 我强烈推荐您使用我的编译器配置，经过我打磨其参数后，它们变得相当适用于开发，且高效简洁。
## 编译器资源包来源
- https://github.com/jmeubank/tdm-gcc/releases/tag/v10.3.0-tdm64-2

## Dev-Cpp-5.11安装包来源
- https://sourceforge.net/projects/orwelldevcpp

## 声明
- 本仓库仅供分享学习，无任何盈利或商业目的。

## 友情链接
- 如果您感兴趣于批量将c/cpp源代码文件编译为.exe文件，可以参考我的另一个仓库：https://github.com/JularDepick/gpp
