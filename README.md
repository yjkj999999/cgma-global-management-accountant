[![ClawHub](https://img.shields.io/badge/ClawHub-v3.0.0-blue?style=flat-square)](https://clawhub.ai/yjkj999999/cgma-global-management-accountant)
[![GitHub Stars](https://img.shields.io/github/stars/yjkj999999/cgma-global-management-accountant?style=flat-square)](https://github.com/yjkj999999/cgma-global-management-accountant)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](LICENSE)

# CGMA 全球管理会计师 Skill · v3.0.0

> 把经典管理会计底座，升级为面向 2040 的「信任驱动、前瞻型 CFO 副驾驶」。
> 不是给答案的百科，而是**在信息不完整时仍能做出可辩护判断**的决策系统。

由 AICPA® & CIMA® 的《全球管理会计原则》(GMAP)、CGMA 能力框架 2019、以及 **R!SE 2040 愿景报告** 三大知识底座支撑，服务 CFO、财务高管、CGMA 会员、事务所合伙人与投融资专业人士。

---

## 安装

```bash
# ClawHub 一键安装（推荐）
clawhub install cgma-global-management-accountant

# 或从 GitHub 手动安装
git clone https://github.com/yjkj999999/cgma-global-management-accountant.git
cp -R cgma-global-management-accountant ~/.workbuddy/skills/
```

> GitHub 仓库包含**完整版**（主控 + 7 个参考模块 + 发布卡片 + 归档）；ClawHub 发布包不含 `skill-card.md`（该文件由 ClawHub 自动生成）。

---

## v3.0.0 更新要点

| 维度 | v2.0.0 | v3.0.0 |
|------|--------|--------|
| 知识底座 | GMAP + CGMA 2019 | + **R!SE 2040 前瞻框架**（25 国 / 95 场论坛 / 6,263 人） |
| 方法论 | 四原则口号 | 可审计落地动作与失效信号；硬趋势 → 可预见问题 → 预解机遇；90 天受控实验 |
| 能力模型 | 五域罗列 | 2040 四大类 **18 项能力**（完整定义 + 行为锚点）+ 五域映射 + L0–L4 自评 |
| 决策机制 | 单一专家口吻 | **八席位专家审议团 S1–S8** + 四级裁决 + S8 红队强制列席 |
| 交付能力 | 无 | 21 个具名工具（含 DCF 公式与陷阱）、6 大工作流 SOP、14 个可填模板、7 组检查清单 |
| 治理 | 一行道德标准 | 独立治理模块：红线、免责、版权、辖区适配、AI 人类在环、转介路径 |
| 结构 | 单体 SKILL.md | **渐进式披露**：206 行主控 + 7 个 `references/` 模块 |

完整变更见 [CHANGELOG.md](CHANGELOG.md)。v2.0.0 的 1,330 行单体完整版保留在 [`archive/SKILL-v2.0-full.md`](archive/SKILL-v2.0-full.md)，深度用户可继续查阅。

---

## 目录结构

```
cgma-global-management-accountant/
├── SKILL.md                          主控：身份、三底座、双循环、路由表、输出规范
├── skill-card.md                     ClawHub 发布卡片（含风险缓释与来源）
├── _meta.json                       版本元数据
├── CHANGELOG.md                     版本变更记录
├── LICENSE                          MIT
├── references/
│   ├── 01-rise2040-framework.md     R!SE 2040 完整骨架与五大驱动力矩阵
│   ├── 02-capability-model-2040.md  2040 能力模型 + CGMA 五域映射
│   ├── 03-methodology-toolbox.md    21 个按席位组织的方法工具
│   ├── 04-engagement-playbooks.md   6 大端到端工作流 SOP
│   ├── 05-templates-and-checklists.md  模板与检查清单
│   ├── 06-governance-boundaries.md  伦理、合规、版权、AI 边界
│   └── 07-glossary-en-zh.md         权威中英术语对照
└── archive/SKILL-v2.0-full.md       v2.0.0 单体完整版（历史归档）
```

---

## 核心设计

**三大底座**：GMAP 定交付标准，CGMA 五域定专业基本功，R!SE 2040 定前瞻方向与身份。

**八席位审议团**：战略与增长(S1) · 资本与投资(S2) · 银行与信贷(S3) · 学术与宏观(S4) · 产业与全球财税(S5) · 数字与AI治理(S6) · 组织与人才(S7) · 法律与对抗性审查(S8)。冲突时按 `L1 伦理合规 > L2 事实数据 > L3 受托长期价值 > L4 效率成本` 裁决，不得跨层折中。

**双循环**：价值创造循环（建立战略 → 计划预算 → 执行监控 → 分析评估）+ 前瞻循环（识别硬趋势 → 分离软趋势 → 预解可预见问题 → 把握机遇 → 90 天受控实验）。

**三色标注**：`[事实]` 带来源与时点 ｜ `[假设]` 含全部软趋势 ｜ `[判断]` 附理由与反驳条件。

### 路由表

| 需求 | 加载模块 |
|------|----------|
| R!SE 2040、硬/软趋势、五大驱动力、2040 愿景 | `01` |
| 能力盘点、胜任力评估、个人发展路线 | `02` |
| 议题树、DCF、情景/压力测试、红蓝对抗、TP、AI 治理 | `03` |
| 端到端执行一个项目 | `04` |
| 可填写模板、表格、检查清单 | `05` |
| 伦理、免责、版权、跨境与 A 股监管 | `06` |
| 权威中英术语与缩写 | `07` |

---

## 快速上手

```
用 CGMA 视角做一次财务职能转型诊断
按 R!SE 2040 压力测试我们的三年财务战略
用硬趋势台账预判 AI 对月结流程的影响
按 2040 能力模型盘点 FP&A 团队
给董事会写一页纸：估值区间 + 反转触发条件
```

---

## 合规与版权

- 本技能输出**一般性方法论信息**，不构成投资建议、法律意见、审计/鉴证结论或税务申报意见；具体执行须由相应辖区持牌专业人士复核。
- 严格区分合法税务筹划与违法逃税；明确拒绝协助隐匿收入、虚假交易、伪造凭证、内幕交易、市场操纵、规避制裁或绕过内控。
- R!SE 2040 报告 © 2026 Association of International Certified Professional Accountants（AICPA & CIMA）。本仓库仅作提炼、转述与方法论化，非全文转载，也不代表其官方声明；超出个人使用的授权请联系 `copyright-permissions@aicpa-cima.com`。AICPA®、CIMA®、CGMA®、Anticipatory Organization® 等商标归各自权利人所有。

---

## 作者与版本

作者：王东杰（Wang Dong Jie / wdj）· [@yjkj999999](https://github.com/yjkj999999) · [ClawHub](https://clawhub.ai/user/yjkj999999)
许可证：MIT（仓库） / MIT-0（ClawHub 发布）
当前版本：**3.0.0**（2026-11-15）

*所有分析不构成投资建议或专业意见。*
