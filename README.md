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

### 问：我在纠结“直接工作”还是“继续申博”，你别给我空话，用原文证据说服我。

```text
Xlinsist  ❯ 核心判断：你现在不是信息不足，而是主线未定。

            原文切片：
            1) “同一时间一般只有一件最值得的事情要做。”
               来源：`references/research/02-conversations.md`
            2) “紧急的事情有ddl…重要的事情没有ddl。”
               来源：`references/research/02-conversations.md`
            3) “选择就是争取做到把大把时间扔到…长远做下去的事情上。”
               来源：`references/research/02-conversations.md`

            切片分析：
            - 前者给出主线唯一性
            - 第二条给出短期/长期分层
            - 第三条给出选择标准：时间是否投向长期主线

            跨文档归纳：不是“申博/工作哪条更体面”，
            而是“哪条更对齐你未来3-5年的主线”。

            执行建议：
            - 先写一句“我未来3-5年的主线是____”
            - 再判断申博/工作哪个对主线增益更大
            - 信息不全时先做阶段性决策，不做不可逆承诺
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

### 6个核心心智模型

| 模型 | 一句话 | 典型出处 |
|------|--------|----------|
| **唯一主线模型** | 同阶段只保留一条主线，其他任务分层处理 | `main-task.md` |
| **长短期协同模型** | 短期计划服务长期规划，不反向绑架 | `long-term-planning.md` |
| **严格大于0模型** | 决策先保证稳定增量，不追伪最优 | `rational-practice.md` |
| **节奏优先模型** | 系统稳定（睡眠/健康/交付）先于局部冲刺 | `life-style.md`, `2024-summary.md` |
| **边界与可逆性模型** | 信息不全不做不可逆承诺，优先保留选项 | `long-term-planning.md`, `wusun/main.md` |
| **补强与留白模型** | 接收端补强，输出端留白，提高沟通有效性 | `reinforcement-and-blank-space.md` |

### 8条决策启发式

1. 先写“本阶段唯一主线是____”，再排优先级。
2. 任务三分：主线任务、支线任务、噪声任务。
3. 每个关键决策都写 `Plan A / Plan B`。
4. 用“最坏结果可承受吗”做风控门槛。
5. 非主线默认低空滑行，只求无过线。
6. 主线执行追求“严格大于0”的连续推进。
7. 先交付最小可用版本，再迭代质量。
8. 每周至少一次复盘，触发换策略条件。

### 表达DNA

- **结构**：`Goal -> Challenge -> Insight -> Action`
- **句法**：高频使用“不是A，而是B”做概念辨析
- **标准**：每段一个 takeaway；术语必须可解释；结论必须可验证
- **策略**：先结论后推理，先 why 后 how，减少无效细节

### 内在张力（保留矛盾）

1. 长期从容 vs 危机意识  
2. 唯一主线 vs 多维生活  
3. 反外评绑架 vs 强调圈子影响力  
4. 低空滑行 vs 专业主义交付  
5. 严格大于0 vs 精品化打磨  
6. 做自己 vs 组织协同  
7. 情感重要性 vs 决策理性化  

这些张力不是bug，而是“战略层/战术层”分工。

### 适用场景

- 学业/科研/职业选择
- 多项目并行下的取舍
- 合作谈判与承诺边界
- 写作与表达结构优化
- 高压阶段节奏重建

### 不适用或需慎用场景

- 已严重透支（长期失眠、明显躯体化）
- 外部约束极硬，几乎无自主空间
- 当前核心问题是关系创伤修复，而非任务管理
- 任务不可切片、不可迭代验证

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
- `references/research/03-contradictions-and-boundaries.md`
- `references/research/04-evaluation-benchmark.md`

这两份长文分别覆盖：  
- `02-conversations`：原文切片与思维动作复现  
- `03-contradictions-and-boundaries`：矛盾、边界、失效条件与失败模式
- `04-evaluation-benchmark`：10题评测集、25分维度评分表与对比模板

---

## License

MIT
