# AI Quad Restore 0.4.0

Blender 5.2 LTS 的本地三角面转四边形工具。安装包包含插件、模型和推理运行库，无需额外安装 Python 或 PyTorch。安装和运行可完全离线。

## 下载

[下载 0.4.0 完整安装包](https://github.com/475519905/ai-quad-restore-releases/releases/tag/v0.4.0)

| 版本 | macOS 14+ Apple Silicon | Windows 10/11 x64 |
|---|---|---|
| Standard 标准版 | [下载 · 51.7 MiB](https://github.com/475519905/ai-quad-restore-releases/releases/download/v0.4.0/AI_Quad_Restore_Standard_0.4.0_macOS_AppleSilicon.zip) | [下载 · 81.7 MiB](https://github.com/475519905/ai-quad-restore-releases/releases/download/v0.4.0/AI_Quad_Restore_Standard_0.4.0_Windows_x64.zip) |
| Pro 专业版 | [下载 · 60.8 MiB](https://github.com/475519905/ai-quad-restore-releases/releases/download/v0.4.0/AI_Quad_Restore_Pro_0.4.0_macOS_AppleSilicon.zip) | [下载 · 90.8 MiB](https://github.com/475519905/ai-quad-restore-releases/releases/download/v0.4.0/AI_Quad_Restore_Pro_0.4.0_Windows_x64.zip) |

[SHA-256 校验清单](https://github.com/475519905/ai-quad-restore-releases/releases/download/v0.4.0/SHA256SUMS.txt)

- **Standard**：仅 Athena，固定模型，无下拉菜单。
- **Pro**：Athena / Argus Pro 两种模型，下拉切换；Athena 仍是默认。
- 两版都支持 Restore Quads、Replace Original、Post Process 和 Select Diagonals。

## 安装与使用

1. 完整解压，退出 Blender。
2. Windows 双击 `Install AI Quad Restore.bat`；macOS 双击 `Install AI Quad Restore.command`。
3. 重启 Blender 5.2，在 Preferences → Add-ons 中启用 AI Quad Restore。
4. 选择完全三角化的 Mesh，打开 N 侧栏 → AI Quad → Restore Quads。

初次使用建议关闭 Replace Original 和 Post Process，并保留原网格。高覆盖不等于所有区域都更正确，请检查关键区域。

[专业版图文教程](https://www.yuque.com/shouwangxingkong-0p4w3/vao7si/dmcnsg5u2sebrt47) · [验证摘要](VALIDATION.md)

此仓库仅提供产品安装包、使用说明和版本信息。
