# AI Quad Restore 0.4.0 · 验证摘要

- macOS Apple Silicon，Blender 5.2.0 LTS：Standard 7 项 / Pro 9 项，通过。
- HANYUE Windows 11 x64，Blender 5.2.1 LTS：Standard 7 项 / Pro 9 项，通过。
- 使用完整 ZIP 和实际安装脚本，在隔离配置中测试；外部 Python 命令不可用，未安装系统 Python 依赖。
- 覆盖两种模型、恢复四边形、替换原对象、后处理、选择对角线、版本菜单及模型文件检查。
- 30 项单元及集成检查通过。
- 3 个 QW Report 网格 × 2 个模型 × 2 个平台，12 组新旧推理结果的顶点及面索引一致。

这是安装、功能与输出一致性验证，不代表任意三角模型都能达到 100% 准确恢复。macOS Intel、Windows ARM 和其他 Blender 大版本不在本次验证范围内。
