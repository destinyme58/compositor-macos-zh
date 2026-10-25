# 来源、修改与再分发说明

## 上游项目

- 项目：Compositor
- 作者：Robbie Tilton / Wonder Assembly LLC
- 源码：https://github.com/robbietilton/Compositor
- 发行版本：v1.5.5
- 许可证：MIT

Compositor 的界面、设计与原始实现归原作者所有。本仓库仅分发社区制作的
简体中文兼容构建，不主张上游代码或设计的所有权。

## 汉化与兼容构建

- 汉化编译工具：https://ps.vumstar.com:5082/
- 教程视频：https://www.bilibili.com/video/BV1KFWA65EgW/
- 参考中文移植：https://github.com/J6meTime/Compositor

安装包按教程提供的选项生成：

- 简体中文界面
- Apple Silicon（arm64）
- 基于上游源码向下兼容至 macOS 12+

本仓库没有参与汉化翻译或兼容补丁的原始开发，仅负责按教程选项获取发行包、
执行本机验证、整理校验信息并通过 GitHub Release 再分发。

## 修改记录

- 将发行包重命名为便于识别的版本、平台、语言和最低系统组合。
- 为当前用户关闭应用内自动更新，防止升级到要求 macOS 26 的上游版本。
- 增加发布说明、SHA-256 校验与发布后自动校验工作流。
- 未修改应用二进制、资源或签名。

## 分发限制

- 本项目与 Robbie Tilton、Wonder Assembly、VUM 星球、Apple、腾讯云及 Octop
  官方均无隶属关系。
- 安装包使用 ad-hoc 签名，未经过 Apple 公证，不应被视为可信官方安装包。
- 使用前应自行核对 SHA-256，并自行承担使用非官方构建的风险。
- 如上游或汉化作者要求停止分发，应删除对应 Release 资产。

