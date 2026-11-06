# MDPAF · Multi-dimensional Project Assessment Framework

**多维分析法** —— 一套判定产品 / 项目 / 功能 / 想法「**值不值得做**」的完整分析方法论，封装为 AI 可直接执行的 Skill（B6 口径）。提供中文版（`mdpaf/`）与英文版（`mdpaf-en/`）两个 skill。

> **一句话说尽这套方法**：用「是否有人付出过代价」判真伪（守门两遍，细守为痛点七问全检：真、量、解、志、度、凑），把想法放回用户世界的长链中定位（延伸建坐标 → 重切定范围），再按范围配价值判断，用「有据结论 + 排序标价的行动」收束，沿链四向生长但每个候选回炉重审——全程相信成本、不信口号，并随时准备重画地图。

## 核心概念

- **四个动词**：判定（粗守）→ 分析（延伸 → 重切 → 下尺）→ 改善（收束）→ 扩展（回炉）
- **行为区块链**（原创核心模型）：用户做事的完整过程是一条链，按用户的阶段感切块、递归分层、聚分双检定案——你的想法只是链中间的一个区块，不是世界的中心
- **痛点七问 + 时机问**：真的痛吗 / 有多痛 / 有多少人痛 / 有解法吗 / 要解决吗 / 解了多少 / 痛完之后呢 / 为什么是现在
- **三个信念**：顺序即逻辑；成本是唯一的测谎仪；地图会过期（机会有保质期）

完整方法论：[`mdpaf/references/mdpaf-methodology.md`](mdpaf/references/mdpaf-methodology.md)

## 怎么用

### WorkBuddy

把 `mdpaf/` 文件夹复制到 `~/.workbuddy/skills/` 下，之后在对话里说「用多维分析法分析这个项目」并附上项目资料即可。英文对话用 `mdpaf-en/`（同样复制到 skills 目录）。

### 任意 AI（通用提示词用法）

把 `mdpaf/SKILL.md` 与 `mdpaf/references/mdpaf-methodology.md` 全文一起发给任何 AI，然后附上项目资料，AI 会按七段结构交付完整分析（英文对话则改用 `mdpaf-en/` 下的两份文件）。

分析只需要一份材料输入：项目说明、用户反馈、竞品信息、付费证据——有多少给多少，缺的会被如实标注「待补充」而不是编造。

### 想要人类阅读版 PDF 报告

分析完成后，把 `mdpaf/references/report-generation.md`（英文对话用 `mdpaf-en/references/report-generation.md`）一并发给 AI，它会按「第 2 页五问速览」结构把结果排版成 PDF 报告。该文件已内联方法论全文，也可**单独**作为报告生成提示词使用（只发它一份 + 项目材料即可）。

## 仓库结构

```
mdpaf/                            # 中文版 skill
├── SKILL.md                      # 工作流程、交付结构、硬纪律
└── references/
    ├── mdpaf-methodology.md      # B6 方法论权威文本（必读）
    └── report-generation.md      # 人读版报告生成提示词（B6 派生件，含内联方法论）
mdpaf-en/                         # English edition
├── SKILL.md                      # workflow, delivery structure, hard disciplines
└── references/
    ├── mdpaf-methodology.md      # B6 authoritative text (English translation)
    └── report-generation.md      # human-readable report generation prompt (derived; English translation)
```

**英文版从属条款**：`mdpaf-en` 是中文 B6 快照的全量英译；两版有出入时**以中文版为准**，B 系列升版时两版同步重发。核心术语对照：行为区块链 = Behavior Chain；四动词 = Gate / Analyze / Refine / Extend；粗守/细守 = Coarse Gate / Fine Gate；卡口 = Choke Point；土办法 = Folk Workaround；让步的重量 = Weight of Concession。

## 版本

当前为 **B6 快照**（2026-11-05 封装）。版本沿革（B1 提纯 → B2 行为区块链 → B3 范围轴翻转 → B4 痛点七问并入 → B5 机会保质期 → B6 时机问）见权威文本末尾。

## 作者与许可

方法与「行为区块链」模型由 **esf** 原创。

License：[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)（署名 4.0 国际）——使用、修改、商用均允许，须保留署名；全文见 [LICENSE](LICENSE)。
