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

## 四、在 VS Code 中安装 `.vsix`

1. 打开 VS Code
2. 按下 `Cmd + Shift + P`
3. 输入并选择：
   <pre class="overflow-visible!" data-start="970" data-end="1016"><div class="contain-inline-size rounded-2xl relative bg-token-sidebar-surface-primary"><div class="sticky top-9"><div class="absolute end-0 bottom-0 flex h-9 items-center pe-2"><div class="bg-token-bg-elevated-secondary text-token-text-secondary flex items-center gap-4 rounded-sm px-2 font-sans text-xs"></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="whitespace-pre!"><span><span>Extensions:</span><span> Install </span><span>from</span><span> VSIX...</span></span></code></div></div></pre>

## 🆕 版本更新记录

### v1.0.1 （2025-11-06）

- 新增 **Base Commands** 与 **FISH Function Groups** 智能补全。
- 每个命令和函数均带有详细中文说明，可悬停查看。
- 优化 `.dat` 文件识别逻辑与注释支持。
- 提升代码搜索体验，支持快速命令查找。
