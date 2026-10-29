# 墨斗 MoDou — 插件下载

面向 Rhino 的矢量线稿、工程齿轮与建模辅助插件。

**[下载最新插件安装文件](https://github.com/a16358648-hub/MouDou-Rhino-Downloads/releases/latest)**

## 发布方式

本插件以闭源方式发布，源码不公开，可免费下载使用。未经作者许可，禁止贩售。

此仓库仅提供使用说明、版本记录和编译后的 `.rhp` 插件文件，不提供插件源码、构建工程或调试符号。

## 主要功能

- 矢量图档：记录视图与分组，批量导出 SVG/EPS 线稿，支持按模型实际尺寸 1:1 导出。
- 齿轮盘：工程齿轮、齿条、蜗杆蜗轮建模，自动啮合与齿轮模型树。
- 工程台：建模对齐、装配定位与重量计算。

## 下载与安装

1. 打开上方下载链接，在 **Assets** 中下载 `.rhp` 文件。
2. 将文件放在长期保留的插件目录，建议命名为 `墨斗 MoDou.rhp`。
3. 如果 Windows 阻止文件加载，在文件属性中勾选“解除锁定”。
4. 双击 `.rhp`，或在 Rhino 中运行 `PlugInManager`，点击“安装”并选择该文件。
5. 安装后重新启动 Rhino。更新已有插件时，请先关闭 Rhino，再覆盖原安装目录中的 `.rhp`。

GitHub 自动显示的 **Source code (zip/tar.gz)** 只包含本下载仓库的说明文件，不包含插件源码，也不是插件安装包。

## 兼容性

- 开发目标：Rhino 7、Windows 64 位、.NET Framework 4.8。
- 已测试可在 Rhino 8 使用；其他 Rhino 版本尚未测试。

## 问题反馈

可通过本仓库的 [Issues](https://github.com/a16358648-hub/MouDou-Rhino-Downloads/issues) 提交问题。请注明 Rhino 版本、插件版本及复现步骤。

---

## English

### MoDou — Plugin Downloads

A Rhino plugin for vector linework, engineering gears, and modeling assistance.

**[Download the latest plugin](https://github.com/a16358648-hub/MouDou-Rhino-Downloads/releases/latest)**

### Distribution

This plugin is distributed as closed-source software. It is free to download and use. Resale without the author's permission is prohibited.

This repository provides usage instructions, release notes, and compiled `.rhp` plugin files. Plugin source code, build projects, and debug symbols are not distributed here.

### Features

- **Vector Drawings:** Record views and groups, batch-export SVG/EPS linework, and export at the model's actual size with the 1:1 option.
- **Gears:** Generate engineering gears, racks, worms, and worm wheels, with automatic meshing and a hierarchical gear model tree.
- **Engineering Workbench:** Modeling alignment, assembly positioning, and weight calculation.

### Download and Installation

1. Follow the download link above and download the `.rhp` file under **Assets**.
2. Save it in a permanent plugin folder. The recommended filename is `墨斗 MoDou.rhp`.
3. If Windows blocks the file, open its Properties and select **Unblock**.
4. Double-click the `.rhp`, or run `PlugInManager` in Rhino, click **Install**, and select the file.
5. Restart Rhino after installation. To update an existing installation, close Rhino before replacing the `.rhp` in its original installation folder.

GitHub's automatic **Source code (zip/tar.gz)** downloads contain only this download repository's documentation. They do not contain the plugin source code and are not plugin installers.

### Compatibility

- Developed for Rhino 7 on 64-bit Windows, targeting .NET Framework 4.8.
- Also tested with Rhino 8; other Rhino versions have not been tested.

### Feedback

Report problems through [Issues](https://github.com/a16358648-hub/MouDou-Rhino-Downloads/issues). Include your Rhino version, plugin version, and steps to reproduce the problem.
