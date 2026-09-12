---
name: ai-for-everyone-router
description: |
  《给所有人的AI入门课》来源路由入口：当请求命中本书未单独晋级的 11 个能力卡时经此进入—— AI流水线设计（"多个AI模块怎么串"/"端到端"/error propagation）、AI战略护城河（"护城河"/ "竞争优势"/"壁垒"/ai moat）、AI团队构建（"AI团队"/"招什么人"/"团队角色"/ai team roles）、 AI转型路线图（"公司想做AI转型"/"怎么让公司变成AI公司"/ai transformation）、自动化任务而非岗位 （"替代XX岗位"/"全自动"/"AI取代"/automate a task）、跨职能头脑风暴（"我们该做什么AI项目"/ "怎么找AI落地场景"/brainstorm AI ideas）、试点势能飞轮（"第一个AI项目做什么"/"先做什么AI"/ first pilot）、分层AI培训（"AI培训"/"不同层级学什么"/"全员AI学习"/AI literacy）、从小处着手找伙伴 （"我想学AI但不知道从哪开始"/"想找人一起学AI"/start small find a partner）、三重尽职调查 （"这个项目值得做吗"/"该投入多少"/"有没有风险"/due diligence）、统一数据仓库（"数据孤岛"/ "数据散落"/"统一数据仓库"/data warehouse）。与 13 个晋级 Skill 互有近邻负例。
metadata:
  cangjie.generated-by: cangjie-tools v2.5.0
  cangjie.variant: router
  cangjie.bundle-id: bundle.ai-for-everyone
  cangjie.capability-count: 24
  cangjie.entrypoint-count: 14
---
# 《给所有人的AI入门课》 — 来源路由入口（compact pack）

## 触发与不触发

**适用**：与本书能力域相关的咨询与任务（见下方路由表的意图列）。
**不适用**：
- 具体模型选型、超参数调优与框架/代码实现细节（本书讲的是通识决策框架，不是算法与工程实现）
- 需要工程团队的分布式训练、算力采购与生产部署运维方案
- AI 伦理与法规的正式合规意见或法律结论（应转交专业合规与法务判断）
- 前沿研究论文解读与最新 SOTA 技术追踪（本书基于监督学习范式，时效性有限）

## 核心原则（常驻速览，概览类问题读到这里即可回答）

1. AI 是新型电力：它是通用技术，放大你已有的数据、品牌与规模优势，而不会凭空创造优势
2. 数据是战略资产，但数据本身不等于价值——价值取决于它能否转化为明确的 A→B 映射
3. 先做小项目、找伙伴，先求成功再求价值，而不是等条件齐备、等完美数据
4. ML 产出可运行的软件，DS 产出洞察报告；两类项目的判定、流程、人才与指标都不同
5. 用统计化验收标准（如测试集 95% 准确率）取代"零错误"要求，并为必然发生的错误设计兜底
6. ML 项目是闭环而非流水线：收集数据 → 训练 → 部署 → 收集失败案例 → 再训练
7. AI 的价值来自三条路径：降低成本、增加收入、创建新业务

## 能力路由（先读本表，按意图加载 1 张能力卡）

| 用户意图 | 先读 | 补读/备注 |
|---|---|---|
| 团队提出一个 AI 想法，想知道值不值得投入资源；想知道"我们到底需要多少数据"；技术负责人评审 AI 提案，需要判断可行性；创业者想快速排除不可行的 AI 方向 | references/capabilities/ml-feasibility.md | 已晋级为独立 Skill `ml-feasibility`（已安装时优先直接使用；本卡仅作原文与背景补充） |
| 团队刚启动 ML 项目，不知道从何下手；模型训练完了，不知道下一步做什么；部署上线后效果不好，想知道怎么改进；想理清"机器学习项目的步骤是什么" | references/capabilities/ml-workflow.md | 已晋级为独立 Skill `ml-workflow`（已安装时优先直接使用；本卡仅作原文与背景补充） |
| 团队争论"这到底算个什么项目"；老板问"这个项目最后要交付什么东西"；招聘时纠结招 ML 工程师还是数据分析师；分不清该建系统还是做报告 | references/capabilities/ml-vs-ds.md | 已晋级为独立 Skill `ml-vs-ds`（已安装时优先直接使用；本卡仅作原文与背景补充） |
| 讨论产品的长期竞争壁垒；评估 AI 产品的增长策略；分析某家 AI 公司为什么能持续领先；设计产品的数据收集策略 | references/capabilities/data-flywheel.md | 已晋级为独立 Skill `data-flywheel`（已安装时优先直接使用；本卡仅作原文与背景补充） |
| 团队争论"这个组件该自建还是购买"；技术选型会上争论"要不要自己造轮子"；评估外部供应商方案还是内部研发；担心过度依赖第三方导致供应商锁定 | references/capabilities/build-vs-buy.md | 已晋级为独立 Skill `build-vs-buy`（已安装时优先直接使用；本卡仅作原文与背景补充） |
| 业务团队提了个 AI 想法，想快速判断值不值得深入调研；产品经理在筛选 AI 功能优先级；非技术管理者想快速理解"AI 现在到底能做什么"；投资人在评估 AI 创业公司的技术可行性 | references/capabilities/one-second-rule.md | 已晋级为独立 Skill `one-second-rule`（已安装时优先直接使用；本卡仅作原文与背景补充） |
| 评估一个 AI 项目值不值得做；向管理层或投资人解释 AI 项目的商业价值；比较多个 AI 项目的优先级；尽调阶段需要量化项目价值 | references/capabilities/three-value-drivers.md | 已晋级为独立 Skill `three-value-drivers`（已安装时优先直接使用；本卡仅作原文与背景补充） |
| 团队说"数据还没准备好"，项目一直启动不了；数据清洗拖了很久，没有明确终点；业务方要求"数据 100% 准确"才肯开始建模；想推动"边建边用"而不是等数据治理全部完成 | references/capabilities/dont-wait-perfect-data.md | 已晋级为独立 Skill `dont-wait-perfect-data`（已安装时优先直接使用；本卡仅作原文与背景补充） |
| 公司想收购另一家公司，理由是"他们的数据很有价值"；有人提议"先把数据买下来，以后再找用途"；评估数据投资或数据收购的 ROI；数据团队说"给我更多数据就能做出更好的模型" | references/capabilities/dont-acquire-for-data.md | 已晋级为独立 Skill `dont-acquire-for-data`（已安装时优先直接使用；本卡仅作原文与背景补充） |
| 业务方坚持"AI 不能出错 / 必须 100% 准确"；团队因为 AI 犯了几个错误就否定整个项目；验收时对"什么算合格"产生争议；需要为错误规划人工复核等兜底流程 | references/capabilities/statistical-acceptance.md | 已晋级为独立 Skill `statistical-acceptance`（已安装时优先直接使用；本卡仅作原文与背景补充） |
| 团队报了个很高的准确率，想知道可不可信；新开 ML 项目，需要设计评估方案；业务方质疑"这个 AI 到底好不好用"；想知道该如何评估模型、怎么看测试结果 | references/capabilities/train-test-split.md | 已晋级为独立 Skill `train-test-split`（已安装时优先直接使用；本卡仅作原文与背景补充） |
| 要启动一个新的 AI/ML 项目；评估 AI 项目的进度和风险；规划 AI 团队的工作流程与里程碑；向管理层汇报 AI 项目计划 | references/capabilities/ai-project-lifecycle.md | 已晋级为独立 Skill `ai-project-lifecycle`（已安装时优先直接使用；本卡仅作原文与背景补充） |
| 团队一直在打磨模型但迟迟不上线；业务方要求"功能完备"后才允许发布；为了几个百分点的准确率提升错过发布窗口；反复说"还没准备好 / 再优化一下" | references/capabilities/iterate-not-perfect.md | 已晋级为独立 Skill `iterate-not-perfect`（已安装时优先直接使用；本卡仅作原文与背景补充） |
| 设计的复杂 AI 产品需要多个步骤或多个模块；单模块指标都很高，但用户体验不好；要将一个复杂 AI 问题拆成多个子问题；多个团队协作开发同一个 AI 系统 | references/capabilities/ai-pipeline.md | references/capabilities/ml-workflow.md、references/capabilities/automate-task.md |
| 评估 AI 项目的长期竞争力；制定公司级 AI 战略；向投资人阐述 AI 竞争优势；分析竞争对手的 AI 能力 | references/capabilities/ai-strategy-moat.md | references/capabilities/build-vs-buy.md、references/capabilities/data-flywheel.md、references/capabilities/three-value-drivers.md |
| 组建或扩充 AI 团队；评估团队的能力缺口；招聘 AI 相关岗位；设计 AI 团队的协作流程 | references/capabilities/ai-team-building.md | references/capabilities/role-tiered-training.md、references/capabilities/ai-transformation-playbook.md、references/capabilities/ai-project-lifecycle.md |
| 公司高层提出"我们要做 AI 转型"；被问"怎么让公司变成 AI 公司"；传统企业面对 AI 浪潮需要行动路线图；需要评估转型步骤与时间线 | references/capabilities/ai-transformation-playbook.md | references/capabilities/ai-team-building.md、references/capabilities/role-tiered-training.md、references/capabilities/pilot-momentum-flywheel.md |
| 管理者说"我们想用 AI 取代 X 岗位"；有人提出"全自动"目标，需要设定更现实的期望；项目范围过大，需要拆成可执行的小项目；分析 AI 对某个角色的影响 | references/capabilities/automate-task.md | references/capabilities/one-second-rule.md、references/capabilities/ml-feasibility.md、references/capabilities/cross-functional-brainstorming.md |
| 企业刚成立 AI 团队，要找第一批落地项目；想启动 AI 转型，但不知道从哪个业务场景切入；技术团队和业务团队各自为政，需要一种对齐机制；咨询顾问帮客户规划 AI 战略，需要结构化创意发现流程 | references/capabilities/cross-functional-brainstorming.md | references/capabilities/three-value-drivers.md、references/capabilities/automate-task.md、references/capabilities/pilot-momentum-flywheel.md |
| 团队纠结"第一个 AI 项目选什么"；有多个 AI 想法，不知道先做哪个；组织刚起步 AI 能力建设，需要决定起点；想知道试点项目的"成功"标准怎么定 | references/capabilities/pilot-momentum-flywheel.md | references/capabilities/start-small-find-partner.md、references/capabilities/ai-transformation-playbook.md、references/capabilities/cross-functional-brainstorming.md |
| 公司要推 AI 培训，但不知道各层级该学什么；培训效果不好——高管觉得太技术、工程师觉得太浅；设计 AI 培训体系；评估 AI 培训的投资回报 | references/capabilities/role-tiered-training.md | references/capabilities/ai-team-building.md、references/capabilities/ai-transformation-playbook.md |
| 个人想入门 AI，但不知从哪开始；担心"我能力不够，做不了 AI"；想找人一起学 AI；一直在"准备"，迟迟不动手 | references/capabilities/start-small-find-partner.md | references/capabilities/pilot-momentum-flywheel.md、references/capabilities/iterate-not-perfect.md |
| 企业准备启动需要数月和大量资源的 AI 项目；决策层评审 AI 项目提案，需要全面评估框架；投资人评估 AI 创业公司的项目可行性；团队已完成初步技术验证，准备进入正式开发 | references/capabilities/triple-due-diligence.md | references/capabilities/ml-feasibility.md、references/capabilities/three-value-drivers.md、references/capabilities/cross-functional-brainstorming.md |
| AI 团队抱怨"数据拿不到 / 数据散落在各处"；公司想做 AI 但不知道数据在哪里；不同部门对同一个业务指标有不同数字；想建数据飞轮但发现数据汇聚是瓶颈 | references/capabilities/unified-data-warehouse.md | references/capabilities/data-flywheel.md、references/capabilities/dont-wait-perfect-data.md |

**非能力类查询**：
- 书名/作者/章节/整书概览 → references/overview.md
- 术语解释 → references/glossary.md
- 决策规则速查（不需要原文依据时） → references/cheatsheet.md
- 完整意图与关键词索引（本表未覆盖的意图先查这里） → references/capability-index.md

## 加载规则

- 每次任务先读本文件，再按路由表加载 **1** 张能力卡；任务明确跨域时最多加载 2 张。
- 概览/书名类问题不加载能力卡，用「核心原则」与 overview.md 回答。
- 路由表与 capability-index.md 都无法命中的意图，明确告知超出本书范围，不要硬套。

## 边界与判停

- 用户索要具体模型、超参数或可运行代码建议 → 说明超出本书范围，建议转算法/工程专家
- 涉及医疗、金融、招聘等高风险场景的 AI 应用 → 提示需专业合规与伦理评估，本书不提供合规结论
- 用户只是要课程笔记或询问"这门课讲了什么" → 直接回答，不启动决策流程
- 项目已明确决定推进，只缺执行排期 → 不重复启动可行性/尽调评估流程
