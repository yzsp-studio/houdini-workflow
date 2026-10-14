<div align="center">

# 🎬 houdini-workflow

## 别在 Houdini 里瞎点：先体检工程，再交可编辑 .hip
## Stop clicking blindly in Houdini: audit the HIP first, ship an editable scene

📮 **商务合作 / Business：wow.vip@foxmail.com**
🎬 **抖音 / Douyin：[v.douyin.com/07EjIDGVErY](https://v.douyin.com/07EjIDGVErY/)**

</div>

---

## 🇨🇳 中文

一条把 Houdini 需求推进到可验证成果的工作流：拿到需求、参考素材或已有 HIP/HDA 工程后，先区分只读分析、新建制作与局部修改，再确认目标工程、软件版本和实例、可编辑范围与交付位置。它用自带脚本检查软件与连接状态，核对当前对话实际控制的场景，而不是把进程启动当成控制成功。随后按任务选择程序化建模、VEX、模拟、动效或工程分析资料，搭建节点网络并分阶段检查几何、依赖与实际画面。交付是可编辑的 .hip/.hiplc/.hipnc 工程、按需的 HDA 或其他导出，以及关联源工程与版本的预览，方便继续修改；版本兼容与许可证限制会被明确说明。

### ✨ 能做什么

- 需求/参考/HIP 工程 → 可编辑 .hip/.hiplc/.hipnc + HDA 导出
- 运行自带 ensure_houdini.py，用 --status 检查并按需准备软件连接
- 核对实际受控场景与目标版本，避免控制错实例
- HIP/拓扑/VEX 分析与循环、依赖、架构债务检查
- 程序化资产与 HDA 控件：先最小可用网络，再叠加 VEX 与参数
- 动效、绑定、相机、RBD 与缓存按规范检查最终输出与代表帧

### 📦 包含的技能

- `houdini-workflow` —— 见 [`houdini-workflow/SKILL.md`](houdini-workflow/SKILL.md)

### 🚀 安装

```bash
git clone https://github.com/yzsp-studio/houdini-workflow.git
cp -r houdini-workflow/* "$DSH_HOME/skills/"
```

> 技能是**纯文本说明**（`SKILL.md` + `references/`），零依赖、零 API key，用你当前 agent 的会话额度。

---

## 🇬🇧 English

A workflow that drives a Houdini request to verifiable results: given a brief, reference material or an existing HIP/HDA project it separates read-only analysis from new production and local edits, then pins down the target project, application version and instance, editable scope and delivery location. A bundled script checks the application and connection state and confirms which scene this conversation actually controls, rather than treating a live process as control. It then picks the right reference set for procedural modeling, VEX, simulation, motion design or project analysis, builds the node network and checks geometry, dependencies and real output in stages. Delivery is an editable .hip/.hiplc/.hipnc project, HDA or other exports where asked, and previews tied to the source project and version; version compatibility and licence limits are reported explicitly instead of silently worked around.

### ✨ What it does

- Brief, references or a HIP project in → editable .hip/.hiplc/.hipnc plus HDA exports out
- Bundled ensure_houdini.py with --status to prepare and verify the application connection
- Confirms the actually-controlled scene and target version instead of the wrong instance
- HIP, topology and VEX analysis plus loop, dependency and architecture-debt checks
- Procedural assets and HDA controls: minimum viable network first, then VEX and parameters
- Motion, rigging, camera, RBD and cache checks against real output and representative frames

### 📦 Skills included

- `houdini-workflow` — [`houdini-workflow/SKILL.md`](houdini-workflow/SKILL.md)

### 🚀 Install

```bash
git clone https://github.com/yzsp-studio/houdini-workflow.git
cp -r houdini-workflow/* "$DSH_HOME/skills/"
```

> Skills are **plain-text instructions** (`SKILL.md` + `references/`). Zero dependencies, no API keys — they run on your agent's existing session quota.

---

## 📮 联系 / Contact

| | |
|---|---|
| 🎬 **抖音 / Douyin** | [https://v.douyin.com/07EjIDGVErY/](https://v.douyin.com/07EjIDGVErY/) |
| 📮 **商务合作 / Business** | **wow.vip@foxmail.com** |
| 🐙 **GitHub** | [https://github.com/yzsp-ai](https://github.com/yzsp-ai) |
| 💖 **打赏 / Support** | [afdian.com/a/yzsp-ai](https://afdian.com/a/yzsp-ai) |

## 📄 License

[MIT](LICENSE) · © 2026 [yzsp-ai](https://github.com/yzsp-ai)
