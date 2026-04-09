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
聚焦提炼“6个核心心智模型 + 内在张力（保留矛盾）”，
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

```

### 问：我在纠结“直接工作”还是“继续申博”，你别给我空话。

```text
Xlinsist  ❯ 维度结论：你现在不是信息不足，而是主线未定。

            核心方法：
            1) 先写一句“我未来3-5年的主线是____”
            2) 再判断申博/工作哪个对主线增益更大
            3) 信息不全时先做阶段性决策，不做不可逆承诺

            关键张力/误区：把“体面感”当主线，会让选择失焦。

            执行清单：
            - 今天：写出主线定义句
            - 本周：列出申博/工作各3条主线增益
            - 下周：做一次阶段性决策并设复盘点
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
| **人生课题思维模型** | 把高频生活事项当长期课题，一次性建工作流，持续复利优化 | `2025-summary.md` |
| **唯一主线模型** | 同阶段只保留一条主线，其他任务分层处理 | `main-task.md` |
| **长短期协同模型** | 短期计划服务长期规划，不反向绑架 | `long-term-planning.md` |
| **严格大于0模型** | 决策先保证稳定增量，不追伪最优 | `rational-practice.md` |
| **节奏优先模型** | 系统稳定（睡眠/健康/交付）先于局部冲刺 | `life-style.md`, `2024-summary.md` |
| **补强与留白模型** | 接收端补强，输出端留白，提高沟通有效性 | `reinforcement-and-blank-space.md` |

### 内在张力（保留矛盾）

1. 长期从容 vs 危机意识  
2. 唯一主线 vs 多维生活  
3. 反外评绑架 vs 强调圈子影响力  
4. 低空滑行 vs 专业主义交付  
5. 严格大于0 vs 精品化打磨  
6. 做自己 vs 组织协同  
7. 情感重要性 vs 决策理性化  

这些张力不是bug，而是“战略层/战术层”分工。

---

## 调研来源

`references/` 已将原 research 层内容并入主文档，直接读取以下文件即可：

- `00-source-inventory.md`
- `01-writings-and-system-thinking.md`
- `02-decision-patterns.md`
- `03-expression-dna.md`
- `04-values-and-anti-patterns.md`
- `05-timeline-and-turning-points.md`
- `06-practice-cases.md`
- `07-evidence-map.md`

---

## License

MIT
