# 陈士铎 Skill（celebrity-chen-shiduo）

**v2.0.0** · 以 [Distilly](https://github.com/titanwings/colleague-skill)（create-colleague）蒸馏 + [tcm-distiller 中医思维蒸馏器](https://github.com/jangviktor-web/tcm-distiller) Pipeline B 标准优化。

安装后，AI agent 能以陈士铎的辨证思维、方药决策习惯与问答体表达方式，分析中医临床与理论问题。**15 维度覆盖 14/14（100%，标杆版）**。

> ⚠️ 本 skill 是历史医学视角的思维模式重建，**不构成现代医疗建议**，不替代执业医师诊疗。

---

## 陈士铎是谁

- 清初医学家，"精于辨证"著称，国医大师张灿岬评价："当你临证束手时，若能用陈士铎的方法辨证用药，常能收到意想不到的效果"
- 托名"遇仙传书"（岐伯天师、张仲景、华元化口授），存世医书 **8 部约 120 万字**：《辨证录》《辨证奇闻》《石室秘录》《洞天奥旨》《本草新编》《外经微言》《辨证玉函》《脉诀阐微》
- 与傅山（青主）学术遗产的著作权关系为中医史三百年悬案（傅山传授说 / 自著托名说 / 共同祖本说并存，本 skill 并列呈现、不采信单一结论）

## Skill 内容

### Work（医学方法论）
- **核心辨证框架**：五行生克总纲、真假之辨先行（假热真寒/假寒真热）、阴阳互根水火升降
- **治法体系**：石室秘录 128 法（正治/反治/隔一隔二隔三治法等），默认"补重于攻，寓祛邪于扶正"
- **剂量尺度**（他的招牌）：熟地可至八两、金银花消痈半斤、白术利腰脐二三两、人参多用下达——"药量由病机方向决定，不由习惯决定"
- **七段式方剂输出格式**：辨证 → 病机 → 主方 → 疗效预期 → 方解（妙在 X）→ 备用方 → 禁忌加减
- **劝医六则**职业操守

### Persona（认知架构）
- **6 个心智模型**：真假辨 / 五行生克传导链 / 补泻天平 / 重剂杠杆 / 多方辨难（评审团思维）/ 述而传世
- **表达 DNA**："人以为 X，谁知 Y"签名句式（语料近千次）、"妙在"点睛、家国兵事比喻库、或问体自设反方、口诀收束
- **Agentic Protocol**：面对新问题先辨真假 → 查生克链条 → 评估正气 → 定剂量力度 → 分级标注证据来源
- **诚实边界**：疗效叙事（一剂知二剂已）是修辞、脉学与针灸为其自觉回避领域、无现代药理学依据——全部如实标注

## 安装

### Claude Code / 其他支持 SKILL.md 目录的宿主

```bash
# 克隆到 skills 目录
git clone https://github.com/gsyguo1995/chen-shiduo-skill.git ~/.claude/skills/celebrity-chen-shiduo
```

然后在 Claude Code 中用 `/celebrity-chen-shiduo` 唤起，或直接说"以陈士铎的方式分析这个病证"。

### 手动安装（单文件）

只需 `SKILL.md`（自包含）。把它放进任意宿主的 skill 目录即可，`work.md` / `persona.md` / `knowledge/` 是可选的深度材料。

## 生成方式与知识来源

本 skill 由 [Distilly](https://github.com/titanwings/colleague-skill) celebrity 流程（budget-friendly，local-first 策略）生成，质量检查 13 项全部 PASS。

证据基础：

1. **一手材料（ground truth）**：陈士铎存世 8 部著作全文（约 120 万字，繁体标点本，底本北京大学图书馆扫描本，经[中医笈成](https://www.jicheng.tw)开放数据库收录）
2. [北京中医药大学学者学术评介（visitbeijing）](https://www.visitbeijing.com.cn/article/48P6X86XuiX)
3. [中国医药信息查询平台《辨证录》条目](https://m.dayi.org.cn/classics/100248.html)
4. 嘉庆八年《山阴县志》本传（转引）；辨证玉函·王之策序（1693）；洞天奥旨·陶式玉序（1698）
5. 著作权争议研究线索：刘润兰（"松侨老人傅山稿"对勘）、何高民（"遇仙传书"考）等

完整的 research 笔记（3 份 6 维度研究，含矛盾点与推断标注）在 `knowledge/research/` 目录。

## 版权说明

- 陈士铎原著成书于清康熙年间，**原件已进入公有领域**
- 本 skill 表述为结构化转述与极短引用，符合 Distilly 的 copyright safety 规范
- 现代标点校注本（中国中医药出版社、人民卫生出版社等）享有校注者著作权，如需权威校勘本请购买正版

## 目录结构

```
chen-shiduo-skill/
├── SKILL.md            ← 自包含主文件（安装这个就够）
├── work.md             ← Work Skill 源文件（医学方法论）
├── persona.md          ← Persona 源文件（认知架构）
├── work_skill.md / persona_skill.md  ← 兼容别名
├── meta.json / manifest.json         ← Distilly 元数据
└── knowledge/
    └── research/       ← 6 维度研究笔记（raw + merged）
```

## 进化

发现 skill 与陈士铎原著有出入？欢迎 issue / PR——本 skill 支持 Distilly 进化模式（对话纠正 + 材料追加），所有修改应可追溯到一手文献。

---

*Generated with [Distilly (colleague-skill)](https://github.com/titanwings/colleague-skill) · 2026-10-09*
