# ai-research

个人调研 skill：AI 调研标准流程与产出规范（SKILL.md）。

## 这是什么

给 AI 编码代理（ZCode / Claude Code 等）用的调研方法论 skill，定义了七步流程：

核实对象 → 拆解维度 → 并行深挖 → 交叉验证与存疑 → 产出文档（飞书知识库）→ 结构验证 → 可选收尾

以及产出标准：结论前置、小白友好、图文并茂（自绘 mermaid/SVG 图）、来源可溯（每条事实带原始 URL）。

## 安装

```bash
mkdir -p ~/.agents/skills/ai-research
cp SKILL.md ~/.agents/skills/ai-research/SKILL.md
```

## 使用

在支持 SKILL.md 的代理里说「用我的调研 skill 调研 XXX」即可。
