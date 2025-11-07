# FLAC3D Language Support

这是一个为 **FLAC3D 7.0** 定制的 VS Code 插件，支持：

- `.dat` 文件命令流语法补全
- FISH 语言函数提示与说明
- 自动缩进与注释识别

### 功能

 模型命令补全
 FISH 脚本智能提示
 鼠标悬停显示解释说明

### 安装步骤

1. 安装 [VSCE 工具](https://code.visualstudio.com/api/working-with-extensions/publishing-extension#vsce)
   ```bash
   npm install -g vsce
   ```


## 🆕 版本更新记录

### v1.0.1 （2025-11-06）

- 新增 **Base Commands** 与 **FISH Function Groups** 智能补全。
- 每个命令和函数均带有详细中文说明，可悬停查看。
- 优化 `.dat` 文件识别逻辑与注释支持。
- 提升代码搜索体验，支持快速命令查找。
