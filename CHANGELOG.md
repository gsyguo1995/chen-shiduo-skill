# CHANGELOG

## v2.0.0（2026-10-09）· tcm-distiller 标准优化

基于 [tcm-distiller 中医思维蒸馏器](https://github.com/jangviktor-web/tcm-distiller) Pipeline B 流程的深度优化。15 维度覆盖率从 9/15 → **14/15**（达标版→标杆版）。

### 新增

- **modules/ 原文库**（P0）：8 部著作全文约 120 万字入库（01-08 编号文件 + 00_index.md 索引），AI 回答可检索原文引用
- **references/00-keyword-index.md**（P0）：症状→门类/方剂/药物/理论/古今病名五类关键词索引（全部实测命中词，禁行号引用）
- **references/08-faq.md**（P0）：10 个高频问题直答（失眠/腰痛/咳嗽/阳痿/梦遗/咽痛/水肿/五郁/忌口/重剂论），全部附原文出处
- **references/07-patterning-framework.md**（P2）：陈氏七步辨治法（列证→设俗→翻案→析机→立方→验效→释义备防），从辨证录 120 门体例提炼
- **references/09-clinical-safety.md**（P0）：误治急救/传变预警/用药铁律（子代理从原文提取）
- **references/24-formula-pattern-system.md**（P0）：核心方剂速查+类似方鉴别+重剂药材特色（子代理从原文提取）
- **references/11-diet-wellness.md**（P1）：饮食调理与胃气观（能食主阳旺/补土兼补火/禁盐铁律）
- **SKILL.md 前置表达速查卡**（P0·S11 双保险）：8 条表达约束 + ✅❌微型对照 + 非医学问答豁免（S14）
- **SKILL.md 安全声明**（P0·维度14）：移至首部固定位置
- **SKILL.md 知识库检索路由**（P0）：问题类型→处理方式映射表
- **persona.md 六层诚实边界**（P0·维度4）：含第5/6层"他会说錯/他会认可"✅❌成对示范各4组

### 优化

- 表达 DNA 升级：口头禅池机制（蓋/誰知/妙在/嗟乎/不知轮换）+ 签名句式强制（人以為X誰知Y）+ 断言式收束
- 索引健康：零行号引用（全部改为"文件 搜关键词"格式）

### 未覆盖（诚实标注）

- 维度 15 功法体系：不适用（辨证派医家，非道医/养生家）

### 质量基线

- distilly quality_check：13/13 OVERALL PASS（v1.0 基线）
- 素材真实性：所有新增引用均来自 modules/ 原文 grep 实检，未编造方名/剂量

---

## v1.0.0（2026-10-09）· Distilly 初版

- character=celebrity, research_profile=budget-friendly, local-first 策略
- 6 维度研究（3 份研究笔记，merged summary 达标：Files 3 / URLs 4 / 长引文 0）
- Work Skill（医学方法论）+ Persona（6 心智模型/10 决策启发式/Agentic Protocol/认知时间线）
- distilly quality_check.py 13 项 OVERALL PASS
- 发布 https://github.com/gsyguo1995/chen-shiduo-skill
