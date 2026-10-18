# writing-ruankao-architecture-thesis

软考高级「系统架构设计师」下午论文写作 Skill（Cursor Agent Skill）。

面向机试论文：审题、提纲、代写/改写、批改与方法迭代。核心原则：**不偏题 > 技术炫技**。

方法对齐 2026 年 10 月总复习与论文专题 1–4：十段式、Q2 专段、点题链、加粗给分点、列举 N 项全覆。

## 安装

将本目录复制或克隆到 Cursor skills 目录：

```bash
git clone https://github.com/ragebabydontcry/writing-ruankao.git \
  ~/.cursor/skills/writing-ruankao-architecture-thesis
```

或手动复制 `SKILL.md` 与 `references/` 到：

```text
~/.cursor/skills/writing-ruankao-architecture-thesis/
```

重启或新开 Agent 对话后，在软考论文相关任务中会自动匹配启用。

## 目录

```text
SKILL.md                      # 主流程、铁律、模式
references/
  method-summary.md           # 权威写作方法（与备考「论文写作方法总结」同步）
  structure-10-segment.md     # 十段式字数与段落职责
  narrative.md                # 过渡句、点题链、加粗与表达禁令
  scoring-rubric.md           # 子题三刀 + 五维操作定义
  checklists.md               # 审题 / 交稿 / 批改清单
  anti-patterns.md            # 低分模式与避雷
```

## 使用场景

- 写 / 改一篇完整论文（`write`）
- 只批改已有草稿（`review`：先三刀再五维）
- 只出提纲与素材（`outline`）
- 根据课件/押题更新方法（`refine-method` → 先改 `method-summary.md`，再回写 SKILL）

## License

个人学习用途；论文内容请结合自身项目经历改写，勿机械套用。
