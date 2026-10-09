<div align="center">

# 陈士铎Skill · 精于辨证的清初医学家AI

**将清初辨证大师陈士铎的完整中医思维体系注入 AI Agent**

`8部存世医书` · `120万字一手著作全文` · `辨证录120门770余证` · `石室秘录128治法` · `本草新编272味药` · `26首核心方+8组类似方鉴别` · `22个误治急救方`

[![版本](https://img.shields.io/badge/版本-v2.0.0-blue?style=for-the-badge)](CHANGELOG.md)
[![15维度覆盖](https://img.shields.io/badge/15维度-14%2F14%20标杆版-success?style=for-the-badge)]()
[![License](https://img.shields.io/badge/协议-MIT-green?style=for-the-badge)](LICENSE)
[![原文可检索](https://img.shields.io/badge/原文库-120万字可grep-orange?style=for-the-badge)](modules/)
[![引用对账](https://img.shields.io/badge/方剂引用-100%25对账通过-brightgreen?style=for-the-badge)]()

</div>

---

> 「布帛菽粟，平淡無奇，而活人之理實奇也。」—— 陈士铎

### 一句话介绍

将陈士铎（约1627-1707，字敬之，号远公，浙江山阴人）的辨证思维、方药决策习惯与问答体表达蒸馏为可激活的 Agent Skill，使 AI 能以陈士铎的视角进行真假辨证、五行生克分析、重剂方药设计。国医大师张灿岬评价："当你临证束手时，若能用陈士铎的方法辨证用药，常能收到意想不到的效果。"

**直接激活词**：`陈士铎` / `远公视角` / `辨证录思维` / `陈士铎会怎么看`

---

## 快速安装

<details>
<summary><b>手动安装（Claude Code / 任意支持 SKILL.md 目录的宿主）</b></summary>

```bash
# 克隆到 skills 目录
git clone https://github.com/gsyguo1995/chen-shiduo-skill.git ~/.claude/skills/celebrity-chen-shiduo

# 或者只装主文件（自包含）
mkdir -p ~/.claude/skills/celebrity-chen-shiduo
curl -o ~/.claude/skills/celebrity-chen-shiduo/SKILL.md https://raw.githubusercontent.com/gsyguo1995/chen-shiduo-skill/main/SKILL.md
```

Claude Code 中用 `/celebrity-chen-shiduo` 唤起，或直接说"以陈士铎的方式分析这个病证"。
</details>

---

## 功能矩阵

| 能力 | 覆盖范围 | 说明 |
|:---|:---:|:---|
| 真假辨证 | ✅ | 假热真寒/假寒真热鉴别——"日轻夜重、痰不黄、舌不燥"矛盾信号捕捉，第一决策关口 |
| 五行生克辨证 | ✅ | 脏腑病机传导链推演，隔一隔二隔三治法（治肺转治脾/平肝/养心） |
| 石室秘录128法 | ✅ | 正治/反治/顺逆/内外/先后/急缓等完整治法体系，按病势选法 |
| 方剂速查 | ✅ | 26首核心方（引火汤/上下两济丹/救脑汤…）含原文剂量+主治+关键句 |
| 类似方鉴别 | ✅ | 8组鉴别（引火汤vs收火汤vs救喉汤、清经散vs两地汤等），陈氏自辨口径 |
| 剂量思维 | ✅ | 11味重剂药材论（熟地八两/金银花半斤/人参多用下达）+ 补阴重剂原理 |
| 临床安全层 | ✅ | 22个误治急救方（救汗回生汤/追魂丹/急救阴阳汤…）+ 传变预警14条 + 用药铁律 |
| 饮食调理 | ✅ | 胃气生死关/能食不能化辨/补土兼补火/攻水禁盐铁律 |
| 七步辨治法 | ✅ | 列证→设俗→翻案→析机→立方→验效→释义备防（从120门体例提炼） |
| FAQ直答 | ✅ | 10个高频病问（失眠/腰痛/咳嗽/阳痿/梦遗/咽痛…）免检索直答 |
| 原文全文检索 | ✅ | 8部著作120万字入库 modules/，回答可 grep 原文引用 |
| 表达还原 | ✅ | "人以為X誰知Y"签名句式 + 妙在点睛 + 或问体自设反方 + 断言收束 |

---

## 使用示例

**真假辨证**
> **Q**：咽喉痛反复发作，用凉药为什么越来越重？
> **A**：痛雖甚而日輕夜重、痰不黃、舌不燥，此假熱也——少陰腎火下無可藏之地，直奔而上炎於咽喉。龍雷之火喜水而不喜火，得水則潛藏。故不與泄火，但與大劑補水（引火汤：熟地三兩巴戟天一兩），引火歸原。

**辨证反转**
> **Q**：腰痛就是肾虚吗？
> **A**：人以為腎虛，誰知腰臍之氣未通——有補腎而腰愈痛者，風濕入於腎而不得出故也。先利腰臍（白朮最利腰臍），後補腎水火，中病即止。

**剂量咨询**
> **Q**：陈士铎的方子剂量为什么那么大？
> **A**：人以為重，誰知病機使然——補陰之藥必多用以取效，陰主降，少用陰藥而味難下達。然凡例有言：宜臨證加減，不可拘定方中——重劑是戰法，不是常法。

**医史讨论**
> **Q**：陈士铎的"遇仙传书"是真的吗？
> **A**：著作权三说并存（傅山传授/自著托名/共同祖本），本 skill 并列呈现不采信单一结论——學者考據與原書自述分開，不糊弄。

---

## 效果演示

**15 维度质量评估（tcm-distiller 标准）**

| # | 维度 | 状态 | 产出 |
|:--|:---|:---:|:---|
| 1 | 核心心智模型 | ✅ | 6 模型（真假辨/生克链/补泻天平/重剂杠杆/多方辨难/述而传世） |
| 2 | 决策启发式 | ✅ | 10 条 Quick Rules，全部带原文锚点 |
| 3 | 表达 DNA + 速查卡 | ✅ | 前置速查卡 8 条铁律 + ✅❌对照 + 口头禅池 |
| 4 | 反模式 + 六层诚实边界 | ✅ | 含"他会说錯！"✅❌成对示范各 4 组 |
| 5 | 剂量思维 | ✅ | 11 味重剂药材 + 剂量红线 |
| 6 | 饮食调理 | ✅ | 胃气观 + 禁忌铁律 |
| 7 | 条辨框架 | ✅ | 陈氏七步辨治法 |
| 8 | 方证体系 | ✅ | 26 方 + 8 组鉴别 |
| 9 | 生平传承 + 来源分级 | ✅ | 一手/二手/本地三级来源表 |
| 10 | 内在张力 | ✅ | 4 组矛盾（谦逊vs锋芒/理性vs神秘包装…） |
| 11 | 智识谱系 | ✅ | 内经仲景→温补学派→当代临床 |
| 12 | FAQ 速查 | ✅ | 10 题直答 |
| 13 | 临床安全层 | ✅ | 22 急救方 + 14 预警 + 铁律 |
| 14 | 安全声明 | ✅ | 首部固定 |
| 15 | 功法体系 | — | 不适用（辨证派医家） |

**覆盖率 14/14 = 100%（标杆版）** · 质量基线：distilly quality_check 13/13 PASS

---

## 数据来源

<details>
<summary><b>点击查看完整数据来源（8 部存世著作，约 120 万字）</b></summary>

| 著作 | 卷数 | 内容 | 状态 |
|---|---|---|---|
| 辨证录 | 14卷120门 | 临床辨证集大成，770余证 | 全文入库 |
| 辨证奇闻 | 15卷 | 辨证录姊妹篇（增删流变本） | 全文入库 |
| 石室秘录 | 6卷 | 治法专著128法，〔批〕方名约240个 | 全文入库 |
| 洞天奥旨 | 16卷 | 外科专著，金银花重剂论 | 全文入库 |
| 本草新编 | 5卷 | 药物学272味，重剂用量论+劝医六则 | 全文入库 |
| 外经微言 | 9卷 | 理论根基（阴阳颠倒/命门水火） | 全文入库 |
| 辨证玉函 | 4卷 | 自创"阴阳虚实上下真假"八纲 | 全文入库 |
| 脉诀阐微 | 1卷 | 脉法（陈氏唯一脉学著作） | 全文入库 |

**底本**：北京大学图书馆扫描本（繁体标点本），经[中医笈成 jicheng.tw](https://www.jicheng.tw) 开放数据库收录，原件已进入公有领域。

**学术评介来源**：
1. [北京中医药大学学者学术评介（visitbeijing）](https://www.visitbeijing.com.cn/article/48P6X86XuiX)
2. [中国医药信息查询平台《辨证录》条目](https://m.dayi.org.cn/classics/100248.html)
3. 嘉庆八年《山阴县志》本传（转引）；辨证玉函·王之策序（1693）；洞天奥旨·陶式玉序（1698）
4. 著作权争议研究线索：刘润兰（"松侨老人傅山稿"对勘）、何高民（"遇仙传书"考）等
</details>

<details>
<summary><b>点击查看仓库目录结构</b></summary>

```
chen-shiduo-skill/
├── SKILL.md                    # 主技能文件（自包含：工作能力+角色规则+速查卡+检索路由）
├── persona.md                  # 认知架构（6心智模型+六层边界+Agentic Protocol+认知时间线）
├── work.md                     # 医学方法论源文件
├── modules/                    # 原文全文库（8部120万字，可grep检索）
│   ├── 00_index.md             # 原文库索引（门类速览+检索纪律）
│   ├── 01-bianzheng-lu.md      # 辨证录（1.1MB）
│   ├── 02-bianzheng-qiwen.md   # 辨证奇闻
│   ├── 03-shishi-milu.md       # 石室秘录
│   ├── 04-dongtian-aozhi.md    # 洞天奥旨
│   ├── 05-bencao-xinbian.md    # 本草新编
│   ├── 06-waijing-weiyan.md    # 外经微言
│   ├── 07-bianzheng-yuhan.md   # 辨证玉函
│   └── 08-maijue-chanwei.md    # 脉诀阐微
├── references/                 # 分析性文档
│   ├── 00-keyword-index.md     # 关键词索引（症状/方剂/药物/理论/古今病名）
│   ├── 07-patterning-framework.md # 陈氏七步辨治法
│   ├── 08-faq.md               # 10题高频直答
│   ├── 09-clinical-safety.md   # 22急救方+传变预警+用药铁律
│   ├── 11-diet-wellness.md     # 饮食调理与胃气观
│   └── 24-formula-pattern-system.md # 26核心方+8组鉴别+11味重剂药材
├── knowledge/research/         # 蒸馏研究笔记（6维度，Distilly 产出）
├── CHANGELOG.md                # 版本变更记录
└── meta.json / manifest.json   # 蒸馏元数据
```
</details>

---

## 更新日志

#### v2.0.0 (2026-10-09) — tcm-distiller Pipeline B 标准优化：15维度 14/14 标杆版

核心升级：按[中医思维蒸馏器](https://github.com/jangviktor-web/tcm-distiller) Pipeline B 流程深度优化，从 9/15 维度提升到 **14/14（100% 标杆版）**。原文 120 万字入库使回答可检索引用。

改动内容：

#### 原文库 + 检索体系（P0）
- modules/ 收录 8 部著作全文（约 120 万字），00_index 提供门类速览
- 关键词索引五类入口（症状→门类/方剂/药物/理论/古今病名），全部实测命中词，禁行号引用

#### 质量维度补全（P0）
- 方证体系：26 核心方（含原文剂量与关键句）+ 8 组类似方鉴别 + 11 味重剂药材论
- 临床安全层：22 误治急救方 + 14 传变预警 + 22 用药铁律（伤寒误汗误下急救链完整）
- FAQ 速查 10 题直答；饮食调理（胃气生死关/禁盐铁律）；七步辨治法框架

#### 表达与边界升级（P0）
- SKILL.md 前置表达速查卡 8 条铁律（签名句式强制/口头禅池轮换/引用对账/非医学豁免）
- persona.md 六层诚实边界（含"他会说錯！"成对示范）；安全声明首部化
- 全部方剂引用经 modules/ 原文 grep 对账（26+12 方 0 缺失）

<details>
<summary><b>点击展开完整更新日志</b></summary>

#### v1.0.0 (2026-10-09) — Distilly celebrity 初版

- 基于[Distilly (colleague-skill)](https://github.com/titanwings/colleague-skill) celebrity 流程蒸馏（budget-friendly，local-first 策略）
- 6 维度研究（3 份研究笔记，merged summary 达标）
- Work Skill（医学方法论）+ Persona（6 心智模型/10 决策启发式/Agentic Protocol/认知时间线）
- distilly quality_check.py 13 项 OVERALL PASS
- 傅山著作权争议三说并列呈现，诚实边界显式标注

</details>

---

## 相关项目 · 同源蒸馏更多 .skill

以下角色包出自 [`中医思维蒸馏器`](https://github.com/jangviktor-web/tcm-distiller) 流水线。**选包看辨证坐标系，不看人名**：

| 项目 | 领域 · 坐标系 | 内核 | 入口 |
|:---|:---|:---|:---|
| [倪海厦](https://github.com/jangviktor-web/nihaixia) | 经方 · 六经辨证 | 六经八纲 + 258 方剂量勘误 | [GitHub](https://github.com/jangviktor-web/nihaixia) |
| [胡希恕](https://github.com/jangviktor-web/huxishu) | 经方 · 六经来自八纲 | 方证对应 | [SkillHub](https://skillhub.cn/skills/user_ff4d9420/huxisu) |
| [黄元御](https://github.com/jangviktor-web/huangyuanyu) | 气机升降派 | 一气周流 | [SkillHub](https://skillhub.cn/skills/user_ff4d9420/huangyuanyu) |
| [李可](https://github.com/jangviktor-web/likeskill) | 扶阳 · 急危重症 | 破格救心 | [GitHub](https://github.com/jangviktor-web/likeskill) |
| [叶天士](https://github.com/jangviktor-web/ye-tianshi-skill) | 温病 · 卫气营血 | 透热转气 | [GitHub](https://github.com/jangviktor-web/ye-tianshi-skill) |
| **陈士铎**（本库） | 辨证 · **真假之辨 + 五行生克** | 重剂起沉疴 + 补重于攻 | 本仓库 |

**陈士铎的坐标系**：不属于六经/卫气营血/三焦任一派——他的定位法是**真假之辨**（表象与本质的鉴别）+ **五行生克传导**（脏腑链杠杆点），配重剂战法。与温补学派（薛己、赵献可、张景岳）同气连枝，而以"闢陳言"的锋芒独树一帜。

### 流水线本身

[`中医思维蒸馏器`](https://github.com/jangviktor-web/tcm-distiller) 把著作、讲稿、医案提炼成可被 AI 调用、还原真人辨证思路的技能。本 skill 是其 Pipeline B（优化已有 skill）的实践案例：120 万字原著 local-first 蒸馏，全部引用可 grep 对账。

[![中医思维蒸馏器](https://img.shields.io/badge/中医思维蒸馏器-V4.6.0-red?style=flat-square)](https://github.com/jangviktor-web/tcm-distiller)
[![Distilly](https://img.shields.io/badge/Distilly-colleague--skill-blue?style=flat-square)](https://github.com/titanwings/colleague-skill)

---

## 免责声明

本项目内容仅供中医学习与研究，为清初历史医学视角的思维模式重建，不构成医疗建议，不替代专业医疗诊断。所有方药剂量为清制原文记载，严禁自行试药。所有诊疗请务必咨询执业中医师。

---

<div align="center">

**陈士铎原著已进入公有领域 · 本 skill 表述遵循引用规范 · MIT 协议开源**

*Generated with [Distilly](https://github.com/titanwings/colleague-skill) + [tcm-distiller](https://github.com/jangviktor-web/tcm-distiller) · 2026-10-09*

</div>
