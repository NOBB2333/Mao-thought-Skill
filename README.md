# Mao Thought Skill

这个仓库现在收敛为一个核心目标：把《毛泽东选集》蒸馏成一个可迁移的方法型 skill。

重点不是模仿旧文风，也不是摘录语录，而是保留毛选最有辨识度的方法，并做成“主文件承载核心思想 + 三个场景补充”的结构：

- 矛盾分析法
- 调查研究
- 群众路线
- 战略战术思维
- 区分不同性质矛盾
- 从判断走到办法和组织动作

## 当前结构

```text
Mao-thought-Skill/
├── SKILL.md
├── README.md
├── agents/
│   └── openai.yaml
├── references/
│   ├── scene-conference-speech.md
│   ├── scene-report-upward.md
│   ├── scene-issue-analysis.md
│   └── source-map.md
└── 原始资料/
    ├── PDF/
    └── TXT/
```

## 使用方式

默认只读取 [SKILL.md](/Users/wong/Code/App/Mao-thought-Skill/SKILL.md)。

`SKILL.md` 本身就应当承载毛选的核心思想、核心精神和核心方法，不应把“出处感”完全外包给别的文件。

场景补充文件只负责不同任务中的展开方式。

只有在需要更细的篇目追溯时，再读取 [references/source-map.md](/Users/wong/Code/App/Mao-thought-Skill/references/source-map.md)。

只有在需要核原文时，才回到 [原始资料/TXT](/Users/wong/Code/App/Mao-thought-Skill/原始资料/TXT)。

## 推荐调用

- “用 `$mao-thought-analysis` 写一篇年度大会讲话，重点讲当前关口和下一步抓手。”
- “用 `$mao-thought-analysis` 写一份向上级的汇报，先讲态势，再讲问题和思路。”
- “用 `$mao-thought-analysis` 分析一下这个平时争论的问题，抓主要矛盾和几种思路。”
