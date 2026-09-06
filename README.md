# hyy-future-house

## Universal Research Scale (URS)

### 中文项目介绍

**Universal Research Scale（URS，通用科研尺度）v1.0 Final** 是一套面向科研工作的、跨学科、跨模型、跨平台的循证决策与质量控制 Skill。

它不是一个“把用户要求直接照做”的普通 Prompt，而是一套科研操作标准：当用户提出制图、统计、论文写作、结果解释、实验设计、机器学习、审稿或投稿等任务时，URS 会先识别真实科研问题、研究设计和数据结构，再优先检索近5年高度相关的高质量文献，同时核对当前权威指南、报告规范和目标期刊要求；在此基础上比较多个可行方案，淘汰存在科学、统计或科研诚信问题的方案，明确给出一个主要推荐方案，然后执行并完成独立质控。

URS 的目标不是“做得像高分论文”，而是：**在当前研究问题和数据条件下，选择最科学、最透明、最可复现、最适合发表的方案。**

适用场景包括：

- 科研 Figure / Table 设计与投稿级优化
- 统计方法选择、效应量与不确定性报告
- SCI 论文 Introduction / Methods / Results / Discussion / Abstract
- 文献证据检索与 Claim–Citation 核验
- 机器学习与生物信息学模型评估
- 严格审稿与投稿前质量控制
- 数据溯源、版本管理、科研诚信与可复现性检查

核心工作流：

`输入 → 任务诊断 → 科学问题识别 → 近5年证据检索 → 权威规范核对 → 候选方案比较 → Hard Gate → 明确决策 → 执行 → 溯源 → QC → 最终输出`

核心原则：

> **科学有效性优先于审美；方法学有效性优先于流行；证据优先于模型自信；科研诚信优先于发表便利。**

### English overview

This repository currently hosts **Universal Research Scale (URS) v1.0 Final**, an evidence-guided scientific decision, analysis, visualization, writing, review, and quality-control skill.

URS does not blindly execute an initially requested method. It first diagnoses the scientific question, study design, data structure, and target output; benchmarks recent high-quality evidence and authoritative guidance; compares valid alternatives; applies scientific and integrity hard gates; makes one primary recommendation; executes the task; and performs research-grade quality control.

Core principle:

> **Scientific validity overrides aesthetics. Methodological validity overrides popularity. Evidence overrides confidence. Integrity overrides publication convenience.**

## Project links / 项目入口

➡️ **Project / 项目目录:** [`universal-research-scale/`](universal-research-scale/)

➡️ **Skill:** [`universal-research-scale/SKILL.md`](universal-research-scale/SKILL.md)

➡️ **中文说明:** [`universal-research-scale/README.zh-CN.md`](universal-research-scale/README.zh-CN.md)

➡️ **English Guide:** [`universal-research-scale/README.en.md`](universal-research-scale/README.en.md)
