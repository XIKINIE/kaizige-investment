# 凯子哥爱投资 Skills

面向投资研究、市场分析、投资者沟通与内容创作的 Codex Skills 合集。

## 包含的 Skills

- `market-research`：市场研究、竞争分析与投资尽调
- `deep-research`：多来源深度研究与资料综合
- `exa-search`：网页、公司和行业资料搜索
- `investor-materials`：投资备忘录、路演材料与财务模型支持
- `investor-outreach`：投资者邮件、引荐文案与后续沟通
- `article-writing`：投资文章、报告与长篇内容写作
- `content-engine`：多平台投资内容生产与复用

## 目录结构

每个 Skill 使用独立目录，入口文件统一命名为 `SKILL.md`：

```text
skills/
├── article-writing/SKILL.md
├── content-engine/SKILL.md
├── deep-research/SKILL.md
├── exa-search/SKILL.md
├── investor-materials/SKILL.md
├── investor-outreach/SKILL.md
└── market-research/SKILL.md
```

## 使用方法

将需要的 Skill 目录复制到项目的 `.agents/skills/` 下，或将全部目录复制过去：

```powershell
Copy-Item -Recurse .\skills\* .\你的项目\.agents\skills\
```
