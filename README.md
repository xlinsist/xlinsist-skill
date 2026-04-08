<div align="center">

# xlinsist.skill

> *“人生是一场长期游戏，探索自我是主线任务。”*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)

<br>

**Xlinsist 的决策与表达操作系统。不是语录合集，是可执行的主线框架。**

<br>

基于 `xlinsist.github.io` 的一手 markdown 语料重构，
提炼“唯一主线、长短期协同、风险门槛、低空滑行、补强与留白”等核心方法，
并按多维调研 + 长文切片方式整理参考资料。

[看效果](#效果示例) · [安装](#安装) · [蒸馏了什么](#蒸馏了什么) · [调研来源](#调研来源)

</div>

---

## 效果示例

### 问：我同时接了3个项目都重要，最近每天焦虑失眠，怎么排优先级？

```text
Xlinsist  ❯ 维度结论：你现在的问题不是时间不够，是主线冲突。

            核心方法：
            1) 写一句“本阶段唯一主线是____”
            2) 其余任务分成支线/噪声，统一降级
            3) 本周只保留一个里程碑，其他任务无过线处理

            关键张力/误区：把“都重要”当真，会导致每条线都浅。

            执行清单：
            - 今日：删掉1个噪声任务
            - 本周：主线推进至少一次严格大于0
            - 每晚：10分钟复盘，重排次日优先级

            证据锚点：`references/02-decision-patterns.md`
```

### 问：给我原文证据，不要概括话术。

```text
Xlinsist  ❯ 核心判断：你需要的是研究模式，不是摘要模式。

            原文切片：
            1) “同一时间一般只有一件最值得的事情要做。”
               来源：`references/research/02-conversations.md`
            2) “紧急的事情有ddl…重要的事情没有ddl。”
               来源：`references/research/02-conversations.md`

            切片分析：
            - 前者给出主线唯一性
            - 后者给出紧急/重要分离

            跨文档归纳：主线优先 + 长期优先 = 取舍总规则

            执行建议：先砍并行主线，再重排本周任务
```

### 问：我写了一篇技术文，反馈是“逻辑乱、信息多”，怎么改？

```text
Xlinsist  ❯ 维度结论：你不是内容不够，而是结构失序。

            核心方法：
            1) 先重排骨架：Goal -> Challenge -> Insight -> Action
            2) 每段只留一个takeaway
            3) 删除所有不支撑结论的细节

            关键张力/误区：堆信息会制造“专业感”，但会破坏可读性。

            执行清单：
            - 先改标题和首段（先结论）
            - 再改段落顺序（先why后how）
            - 最后做一轮“删除测试”（删掉30%冗余）

            证据锚点：`references/03-expression-dna.md`
```

---

## 安装

```bash
npx skills add xlinsist/xlinsist-skill
```

本地调试安装：

```bash
cd ~/paper/xlinsist-skill
npx skills add . -y -g
```

---

## 蒸馏了什么

### 核心框架

1. **唯一主线**：同阶段只保留一条主线。
2. **长短期协同**：短期计划服务长期规划。
3. **严格大于0**：不追完美最优，追稳定推进。
4. **风险门槛**：信息不全时不做不可逆承诺。
5. **低空滑行**：非主线任务以“无过线”为目标。
6. **补强与留白**：接收端补强，输出端留白。

### 使用场景

- 学业/科研/职业选择
- 多项目并行下的取舍
- 合作谈判与承诺边界
- 写作与表达结构优化
- 高压阶段节奏重建

---

## 调研来源

`references/` 提供两层资料：

### 维度文档（可快速调用）

- `00-source-inventory.md`
- `01-writings-and-system-thinking.md`
- `02-decision-patterns.md`
- `03-expression-dna.md`
- `04-values-and-anti-patterns.md`
- `05-timeline-and-turning-points.md`
- `06-practice-cases.md`
- `07-evidence-map.md`

### 深度调研（原文切片）

- `references/research/02-conversations.md`

这份长文采用“切片 -> 分析 -> 归纳”结构，适合需要详尽出处和论证链的回答场景。

---

## License

MIT
