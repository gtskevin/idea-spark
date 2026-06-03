<div align="center">

<img src="assets/banner.svg" alt="Idea Spark — AI 驱动的学术研究想法孵化器" width="800">

<br/>

[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blue?style=for-the-badge&logo=anthropic)](https://claude.ai/code)
[![Codex](https://img.shields.io/badge/OpenAI-Codex-412991?style=for-the-badge&logo=openai)](https://github.com/openai/codex)
[![Gemini CLI](https://img.shields.io/badge/Gemini-CLI-4285F4?style=for-the-badge&logo=google)](https://github.com/google-gemini/gemini-cli)

</div>

> [!NOTE]
> **你是组织行为学 / 管理学者？** 你有一个研究方向，但不知道"这个角度有没有人做过"、"审稿人会怎么挑刺"、"还能怎么创新"。
> **Idea Spark** 像一个结构化的头脑风暴伙伴，从一个研究方向系统化地激发出多个创新角度——诊断你的想法、跨域寻找灵感、预判审稿人批评、评估理论贡献。

## Highlights

| | 特性 | 为什么重要 |
|---|------|----------|
| 🧠 | **五步引擎**：评估→诊断→孵化→评估→推荐 | 不是随机发散，而是系统化的创新空间扫描 |
| 💡 | **7 个创新元类别** + 深度/浅度判断标准 | 基于 AMJ/JAP/JOB 顶刊范文提炼的创新方法论 |
| 🔍 | **跨域灵感扫描** | AI 连接你没想到的学科——社会学、HCI、伦理学 |
| ⚔️ | **Reviewer 2 对抗模式** | 预判最尖锐的审稿人批评 + 回应策略 |
| 📊 | **理论贡献评估（So What?）** | 不只问"新不新"，更问"重不重要" |

## Quick Start

> ⏱️ **30 秒安装，无需编程基础**

### 方式一：告诉你的 AI（推荐，最简单）

直接在你的 AI 工具中发送以下指令：

| 平台 | 复制这条指令发送给你的 AI |
|------|-------------------------|
| **Claude Code** | `Install idea-spark from https://github.com/gtskevin/idea-spark` |
| **OpenAI Codex** | `Install idea-spark from https://github.com/gtskevin/idea-spark` |
| **Gemini CLI** | `Install idea-spark from https://github.com/gtskevin/idea-spark` |
| **Cursor** | 把 SKILL.md 和 perspectives.md 下载后放入 `.cursor/rules/` 目录 |
| **Windsurf** | 把 SKILL.md 和 perspectives.md 下载后放入 `.windsurf/rules/` 目录 |
| **其他 AI** | 将 SKILL.md 和 perspectives.md 放入自定义指令/skills 目录即可 |

> 💡 **完全不会编程？** 打开你的 AI 工具（比如 Claude Code），直接粘贴上面那条指令，AI 会自动帮你安装好。之后只需要输入 `/idea-spark 你的研究方向` 就能开始使用。

### 方式二：手动安装

<details>
<summary>Claude Code</summary>

```bash
mkdir -p ~/.claude/skills/idea-spark
curl -sL https://raw.githubusercontent.com/gtskevin/idea-spark/main/SKILL.md -o ~/.claude/skills/idea-spark/SKILL.md
curl -sL https://raw.githubusercontent.com/gtskevin/idea-spark/main/perspectives.md -o ~/.claude/skills/idea-spark/perspectives.md
```
</details>

<details>
<summary>OpenAI Codex</summary>

```bash
mkdir -p ~/.codex/skills/idea-spark
curl -sL https://raw.githubusercontent.com/gtskevin/idea-spark/main/SKILL.md -o ~/.codex/skills/idea-spark/SKILL.md
curl -sL https://raw.githubusercontent.com/gtskevin/idea-spark/main/perspectives.md -o ~/.codex/skills/idea-spark/perspectives.md
```
</details>

<details>
<summary>Gemini CLI</summary>

```bash
mkdir -p ~/.gemini/skills/idea-spark
curl -sL https://raw.githubusercontent.com/gtskevin/idea-spark/main/SKILL.md -o ~/.gemini/skills/idea-spark/SKILL.md
curl -sL https://raw.githubusercontent.com/gtskevin/idea-spark/main/perspectives.md -o ~/.gemini/skills/idea-spark/perspectives.md
```
</details>

---

安装后，输入你的研究想法：
```
/idea-spark 变革型领导是否可能通过增加员工的情感耗竭来削弱员工的创造力？
```

预期输出：
```
━━━ Idea Spark ━━━━━━━━━━━━━━━━━━━━
原始想法诊断：变革型领导的积极光环下隐藏的代价
理论谜题："为什么公认的积极领导风格可能抑制创造力的产生？"

1. 💡 变革型领导的"过度激励"效应——情感耗竭的中介机制
   N:4 T:5 F:3 I:4 Ti:4 | 理论扩展
2. 💡 员工创造力作为前因：高创造力员工是否反而引发领导的控制行为？
   N:5 T:4 F:3 I:5 Ti:3 | 范式转换
3. 💡 变革型领导的日常波动——哪天的"激励"反而变成了"压力"？
   N:3 T:3 F:4 I:3 Ti:4 | 实证补充

⭐ 推荐：Idea 2，挑战了领导力→创造力的因果方向假设
→ 完整报告已在浏览器中打开
```

## How It Works

```
Step 0: 原始想法评估 → 你的理论谜题是什么？构念质量如何？
Step 1: 创新地图诊断 → 7 个元类别逐一标注 🔓/✅/⚠️/❌
Step 2: 跨域灵感 + 孵化 → 生成 3 个深度研究问题（含研究模型+测量建议）
Step 3: 多维评估 → 评分 + "So What?" + "Reviewer 2" 对抗
Step 4: 文献检索指导 + 推荐 → 主动推荐最强想法
```

### 创新知识库：7 个元类别

| 元类别 | 操作 | 深度标准 |
|--------|------|---------|
| **翻转维度** | 短期↔长期、bright↔dark、自上↔自下 | 翻转后揭示新机制=深；只换方向=浅 |
| **替换构念** | 引入新变量或反面变量 | 命名了新现象=深；旧概念窄化=浅 |
| **切换层次** | 个体间↔个体内、工作↔家庭 | 不同层次有不同机制=深 |
| **重新组合** | 整合不对话的文献领域 | 两文献互相照亮=深 |
| **刷新情境** | 同一问题换场景 | 新情境推翻旧结论=深 |
| **刷新方法** | 用新方法研究老问题 | 新方法看到不同图景=深 |
| **从好奇出发** | 挑战核心假设 | 挑战核心假设=深 |

## Usage

```bash
/idea-spark "我想研究远程办公中的领导力"     # 完整分析
/idea-spark --diagnose "abusive supervision" # 只做诊断
/idea-spark --incubate "正念→情绪→创造力"    # 只做孵化
/idea-spark --journal amj "voice行为"         # 指定期刊
/idea-spark                                    # 交互式引导
```

| 期刊 | 加权维度 |
|------|---------|
| AMJ | 故事性 ↑ |
| JAP | 方法严谨 ↑ |
| JOB | 理论深度 ↑ |
| JOM | 新颖 + 理论 ↑ |

## FAQ

<details>
<summary>能保证生成的想法没人做过吗？</summary>

**不能。** Idea Spark 是启发式工具，不是文献数据库。每个想法都附具体检索策略——最终验证是你的责任。报告明确标注"文献检索状态：未检索"。
</details>

<details>
<summary>我不是 OB 领域的，能用吗？</summary>

7 个创新元类别来自 OB/管理学顶刊，但创新模式本身跨领域通用。心理学、教育学、社会学等社科领域都能用。
</details>

<details>
<summary>为什么不直接问 ChatGPT/Claude？</summary>

直接问 AI 是随机发散。Idea Spark 强制系统化：评估起点→扫描 7 类→跨域连接→质量评估→审稿人预判→主动推荐。更全面、更有结构，且输出完整 HTML 报告。
</details>

<details>
<summary>我不太会编程，能用吗？</summary>

完全可以。Idea Spark 是纯 prompt + 知识库，安装只需要让 AI 帮你操作。使用时只需要输入 `/idea-spark 你的研究方向`，所有分析过程由 AI 自动完成。
</details>

## Contributing

1. Fork → 2. Branch → 3. Commit → 4. Push → 5. PR

特别欢迎：新的创新子视角、跨域灵感建议、期刊权重校准、其他 AI 平台适配。

## License

[MIT](LICENSE)
