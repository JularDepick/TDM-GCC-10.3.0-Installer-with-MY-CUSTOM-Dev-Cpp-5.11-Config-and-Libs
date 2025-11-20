# TDM-GCC-10.3.0-Installer-with-MY-CUSTOM-Dev-Cpp-5.11-Config-and-Libs

## 适用于
- Windows_x64

## Release中含有:
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
## 编译器资源包来源
- https://github.com/jmeubank/tdm-gcc/releases/tag/v10.3.0-tdm64-2

## Dev-Cpp-5.11安装包来源
- https://sourceforge.net/projects/orwelldevcpp

## 声明
本仓库仅供分享学习，无任何盈利或商业目的。
