# Universal Research Scale (URS)

**Version 1.0 Final — Evidence-guided scientific decision, analysis, visualization, writing, review, and quality-control skill**

[中文说明](README.zh-CN.md) · [English Guide](README.en.md) · [Skill](SKILL.md) · [Changelog](CHANGELOG.md)

## 中文简介

**Universal Research Scale（URS，通用科研尺度）** 是一套跨学科、跨模型、跨平台的科研决策与质量控制标准。它的目标不是“按用户说的直接生成”，而是先识别真实科研问题和数据结构，再优先检索近五年高度相关、高质量文献与当前权威规范，比较多个候选方案，主动选择最科学合理的方法，然后执行并完成科研级质控。

URS 适用于科研制图、统计分析、论文写作、结果解释、实验设计、机器学习研究、严格审稿和投稿准备。它强调：**科学有效性优先于审美，方法学有效性优先于流行做法，证据优先于模型自信，科研诚信优先于发表便利。**

核心工作流：

`输入 → 任务诊断 → 科学问题识别 → 近5年证据检索 → 权威规范核对 → 候选方案比较 → Hard Gate → 明确选择 → 执行 → 溯源 → QC → 最终输出`

## English introduction

**Universal Research Scale (URS)** is a cross-disciplinary, cross-model, and cross-platform framework for evidence-guided scientific decision making and quality control. Its purpose is not to blindly execute the user’s initial request. Instead, URS first diagnoses the research question, study design, data structure, and intended output; then benchmarks recent high-quality literature and authoritative guidance; compares scientifically valid alternatives; makes one primary recommendation; executes the task; and performs research-grade quality control.

URS is designed for scientific visualization, statistical analysis, manuscript writing, result interpretation, study design, machine-learning research, peer review, and submission preparation.

Core principle:

**Scientific validity overrides aesthetics. Methodological validity overrides popularity. Evidence overrides confidence. Integrity overrides publication convenience.**

Core workflow:

`INPUT → TASK DIAGNOSIS → RESEARCH QUESTION → 5-YEAR EVIDENCE SEARCH → AUTHORITATIVE GUIDANCE → CANDIDATE COMPARISON → HARD GATES → PRIMARY DECISION → EXECUTION → PROVENANCE → QC → FINAL OUTPUT`

## What makes URS different

- Searches or benchmarks the **rolling previous five years** of high-quality, highly relevant literature when the task is evidence-sensitive.
- Does **not** assume high-impact journals are automatically methodologically correct.
- Treats the user’s requested method (e.g. bar chart, t-test, heatmap) as a **candidate**, not an unquestionable instruction, when scientific validity is at stake.
- Requires explicit comparison of valid alternatives and a **PRIMARY RECOMMENDATION**.
- Uses **Hard Gates** for scientific validity, statistical validity, data integrity, citation integrity, and research integrity.
- Links statistics and figures so both represent the same data structure and inferential question.
- Controls claim strength through a **Claim Ceiling** so writing never exceeds the evidence.
- Maintains a traceable chain from data to analysis to figure/table to manuscript claim.
- Supports **QUICK / STANDARD / DEEP** execution modes.

## Recommended use

Place `SKILL.md` in the instructions or skill directory of your preferred AI environment, or paste it into a persistent project/workspace instruction. The skill is platform-agnostic: if live web search, coding, file access, or document editing is unavailable, the model must explicitly disclose that limitation rather than pretending the work was performed.

## Repository layout

```text
universal-research-scale/
├── README.md
├── README.zh-CN.md
├── README.en.md
├── SKILL.md
├── CHANGELOG.md
├── LICENSE
└── examples/
    ├── figure-decision-example.md
    └── manuscript-review-example.md
```

## Status

`URS v1.0 Final` is the frozen core standard. Future additions should be modular extensions (for example `URS-FIG`, `URS-STAT`, `URS-WRITE`, `URS-REVIEW`, `URS-ML`) and should not weaken the core Hard Gates.

## License

MIT License. See [LICENSE](LICENSE).
