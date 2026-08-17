# 庚申夜 / Gengshen Night

简介
---
《庚申夜》是一个赛博朋克 + 道教美学的 2D 横版 roguelite。玩家在霓虹与祭坛交织的夜城中战斗，收集符箓与义体升级，面对随机生成的试炼与强悍的祭祀式 Boss。

主要特性
---
- 2D 横版动作，注重手感与连招
- Roguelite 元素：随机关卡、符箓与永久解锁
- 赛博朋克 + 道教的混合视觉与音效
- 模块化房间拼接的随机生成流程

快速开始（开发者）
---
先决条件：安装 Git、Git LFS、Godot 4（若使用 Godot）或 Unity（若使用 Unity）。

1. 克隆仓库：
   - git clone https://github.com/isekai486/gengshen-night.git
2. 拉取大文件（使用 Git LFS）：
   - git lfs install
   - git lfs pull
3. 在 Godot 中打开 game/project.godot 并运行（若使用 Godot）。

贡献
---
欢迎任何形式的贡献。请先在 Issues 里创建任务并在 Discord 上沟通核心设计。贡献请遵循分支策略：feature/*，并在 PR 描述中写明变更内容与演示方式。

代码提交规范（建议）
---
使用短前缀的提交信息，例如：
- feat: 添加新功能
- fix: 修复 bug
- chore: 构建优化或脚手架更改
- docs: 文档变更
- art: 美术/资源提交

仓库结构（建议）
---
- README.md
- LICENSE
- .gitignore
- .gitattributes
- game/ (Godot 项目)
  - project.godot
  - src/
  - assets/
- docs/
  - design.md
  - art-style.md
- .github/
  - ISSUE_TEMPLATE/
  - workflows/

联系方式与协作
---
请在 Discord（或你们指定的沟通渠道）中创建项目频道，方便协调美术、程序、音频与测试。仓库管理员可以通过 Settings → Manage access 邀请协作者。

许可证
---
本项目采用 MIT 许可证（详见 LICENSE 文件）。
