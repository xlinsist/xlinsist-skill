# Evidence Map (V2)

> 用途：给 `xlinsist-perspective` 提供可检索、可反驳、可评分的证据矩阵。  
> 结构：`主张ID -> 主张 -> 正向证据 -> 边界/反证 -> 适用场景 -> 置信度`。  
> 更新时间：2026-04-08。

---

## 一、检索协议（推荐）

1. 先定位问题类型（决策 / 表达 / 价值冲突 / 阶段诊断 / 案例推演）。  
2. 再匹配主张ID（Cxx）。  
3. 如需严谨论证，可附：`正向证据 + 边界条件`。  
4. 高风险建议建议附：`失效触发条件`。

---

## 二、核心主张矩阵

| ID | 主张 | 正向证据 | 边界/反证 | 适用场景 | 置信度 |
|---|---|---|---|---|---|
| C00 | 人生课题思维先于单题求解 | `2025-summary.md`：“把…经常接触到的事情视为‘人生课题’…一次性解决…不断优化” | 低频一次性问题不必课题化 | 长期反复问题、习惯系统建设 | 高 |
| C01 | 同阶段唯一主线 | `main-task.md`：“同一时间一般只有一件最值得的事情要做” | `life-style.md`保留生活多维冗余，不能绝对单线 | 多目标冲突、精力稀缺 | 高 |
| C02 | 短期计划服务长期规划 | `long-term-planning.md`：长期/短期双系统 | 强制度场景下短期合规优先 | 学业/职业路径取舍 | 高 |
| C03 | 进步标准是严格大于0 | `rational-practice.md`：“严格大于零的正回报” | 最终提交物不能只满足>0 | 启动期、迭代期 | 高 |
| C04 | 节奏系统先于局部冲刺 | `life-style.md`：“生活节奏…优先于具体任务” | 截止日不可变时需阶段性加压 | 高压持续作战 | 高 |
| C05 | 信息不全不做不可逆承诺 | `long-term-planning.md`Plan A/B；`wusun/main.md`多次继续/下撤评估 | 机会窗口极短时可阶段性承诺 | 谈判、合作、转轨 | 中高 |
| C06 | 非主线低空滑行 | `main-task.md`：“不求有功但求无过” | 关键信用节点不可低空 | 行政杂务、低杠杆任务 | 中高 |
| C07 | 先交付最小可用，再迭代 | `2025-summary.md`：三天任务、60分交付 | 高审查场景首版也需高完成度 | 项目推进、团队协作 | 高 |
| C08 | 关系是长期系统变量 | `friendship-and-love.md`：友情纯真+功利并存 | 关系创伤修复不能简化为任务排程 | 合作、亲密关系、带人 | 中 |
| C09 | 接收端补强，传达端留白 | `reinforcement-and-blank-space.md`完整定义 | 高风险沟通不能过度留白 | 写作、汇报、冲突沟通 | 高 |
| C10 | 问题定义先于执行优化 | `multiple-views.md`：先确保问题合适 | 外部问题定义不可改时，转做执行最优 | 选题、职业选择、研究方向 | 高 |
| C11 | 规则化管理优于情绪化管理 | `2025-summary.md`：完成定义/截止时间/责任人 | 若标准模糊，规则会形式化 | 带实习生/团队协作 | 高 |
| C12 | 感性目标要配理性方法 | `about-photography.md`：情感表达+理性系统 | 只讲感觉不复盘会停滞 | 艺术/写作/长期训练 | 中高 |

---

## 三、主张到证据文件的映射

| 主张ID | 主要读取文件 | 次要读取文件 |
|---|---|---|
| C00 | `references/01-writings-and-system-thinking.md` | `references/research/05-2025-summary-deep-dive.md` |
| C01 C06 | `references/02-decision-patterns.md` | `references/research/02-conversations.md` |
| C02 C03 C05 | `references/02-decision-patterns.md` | `references/research/03-contradictions-and-boundaries.md` |
| C04 | `references/04-values-and-anti-patterns.md` | `references/05-timeline-and-turning-points.md` |
| C07 C11 | `references/06-practice-cases.md` | `references/research/02-conversations.md` |
| C08 | `references/04-values-and-anti-patterns.md` | `references/research/03-contradictions-and-boundaries.md` |
| C09 | `references/03-expression-dna.md` | `references/research/02-conversations.md` |
| C10 | `references/01-writings-and-system-thinking.md` | `references/05-timeline-and-turning-points.md` |
| C12 | `references/06-practice-cases.md` | `references/01-writings-and-system-thinking.md` |

---

## 四、10题评测映射（推荐答案骨架）

| 题号 | 问题类型 | 推荐主张ID | 推荐边界 |
|---|---|---|---|
| Q1 | 多项目焦虑排优先级 | C01 C06 | 单线不等于透支生活 |
| Q2 | 短期高收益机会是否接 | C02 C05 | 机会窗口与不可逆风险 |
| Q3 | 先准备再投 or 先投迭代 | C03 C07 | 目标场景对首版质量要求 |
| Q4 | 信息不全被催承诺 | C05 C11 | 阶段承诺 vs 最终承诺 |
| Q5 | 稳定低天花板 vs 高不确定成长 | C02 C10 | 当前风险承受能力 |
| Q6 | 做减法 | C01 C06 | 关键信用节点不可低空 |
| Q7 | 团队推进慢 | C11 C04 | 规则清晰度不足时先补定义 |
| Q8 | 写作逻辑乱 | C09 C07 | 高风险表达不能过度留白 |
| Q9 | 当前最优但不兴奋 | C10 C02 | 避免浪漫化“反主流选择” |
| Q10 | 周行动清单 | C03 C04 C07 | 过载时先修节奏再加任务 |

---

## 五、证据使用规范

1. 需要时可给 `references/*.md` 路径，方便复核。  
2. 推荐包含一句“为何适用”与一句“何时失效”。  
3. 若同一建议被两条主张支持，可优先给跨文件依据。  
4. 若证据冲突，优先使用 `research/03-contradictions-and-boundaries.md` 做边界裁决。

---

## 六、快速评分维度（回答验收）

每条回答 0-5 分：

1. 主张匹配度：是否匹配正确主张ID。  
2. 论证清晰度：是否讲清判断依据。  
3. 边界意识：是否给出不适用条件。  
4. 可执行性：是否有明确动作和阈值。  
5. 一致性：是否与既有主张冲突。

总分 25。低于 18 视为“可用但不稳”，需重写。
