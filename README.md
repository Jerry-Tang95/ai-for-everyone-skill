# 给所有人的AI入门课 · Agent Skill

> 吴恩达（Andrew Ng）《给所有人的AI入门课》（AI for Everyone，2019 非技术向 AI 通识课）蒸馏出的 AI Agent Skill。
> 24 张能力卡：13 张已晋级为独立 Skill，11 张只能经本入口到达——本包即那 11 张降级卡的入口，适用于 WorkBuddy / CodeBuddy / Claude。

**这个包不教你算法，它替你做判断题。** 课程体例本身就是「判断题而非知识点」——要 100% 准确还是 95% 就够？第一个项目选最有价值还是最容易成功？所以蒸馏产物是 24 张有判据、有否决条件的决策卡。你问"数据还不够能不能开工"，它先要你把「足够好」的门槛定义出来。

它**不能**做的是：模型选型、超参调优、代码调试、SOTA 追踪，以及医疗/金融/招聘等高风险场景的合规结论。

---

## 30 秒验证装没装好

装好后直接问这一句：

> **我们要设计一条由识别、分类、生成三段接力的AI链路，各段之间怎么定接口才不出错？**

期望行为：激活本来源路由入口，路由到 `AI流水线设计` 能力卡（`references/capabilities/ai-pipeline.md`），**按端到端准确率 ≈ 各模块准确率相乘**（如 0.95⁴≈81%）定位最弱环节，并追问"谁对端到端结果负责"，而不是逐个模块给你调优建议。

若它开始讲通用 AI 架构、或直接给代码 —— 没装好，或它把请求误当成技术实现型问题（属 out_of_scope）。

---

## 24 张能力卡（全部摊开，不挑拣）

`references/capability-index.md` 是权威清单，实际行数为 **24 张**：**2 张 critical · 14 张 high · 8 张 medium**。

> 「本包」列：**本入口** = 已降级，只能经本 SKILL.md 路由表加载；**独立** = 已晋级同名独立 Skill，装了它时优先直达，本包内副本仅作原文补充。

### critical（2 张 · 遇到就该先查）

| 能力卡 | 触发提问 | 本包 |
|---|---|---|
| `ml-feasibility` ML可行性双因素 | 这个 AI 想法可行吗、需要多少数据、技术上能做到吗 | 独立 |
| `ml-workflow` ML项目流程 | ML 项目从何下手、部署上线后效果不好怎么改进 | 独立 |

### high（14 张）

| 能力卡 | 触发提问 | 本包 |
|---|---|---|
| `ml-vs-ds` ML与DS项目判定 | 这到底算个什么项目、该建系统还是做报告、招 ML 还是招数据分析师 | 独立 |
| `data-flywheel` 数据飞轮 | 产品的长期竞争壁垒、增长策略、某家 AI 公司为什么能持续领先 | 独立 |
| `build-vs-buy` 自建还是购买 | 这个组件该自建还是买、要不要自己造轮子、会不会被供应商锁定 | 独立 |
| `one-second-rule` 一秒法则 | 这个 AI 能做吗、现在 AI 到底能做到什么程度 | 独立 |
| `three-value-drivers` AI价值三途径 | 这个 AI 项目的 ROI、商业价值在哪、值不值得投入 | 独立 |
| `dont-wait-perfect-data` 不等完美数据 | 数据还没准备好、等数据完善了再说、要求 100% 准确才肯建模 | 独立 |
| `statistical-acceptance` 统计化验收标准 | AI 必须零错误吗、准确率多少算够、要不要人工复核兜底 | 独立 |
| `train-test-split` 训练集测试集分离 | 团队报的准确率可不可信、该怎么评估模型 | 独立 |
| `ai-project-lifecycle` AI项目生命周期 | AI 项目的里程碑怎么排、怎么向管理层汇报项目计划 | 独立 |
| `iterate-not-perfect` 迭代而非完美 | 还没准备好、再优化一下、等准确率再高一点再上线 | 独立 |
| `ai-team-building` AI团队构建 | 想拉起一支 AI 小队，找哪些背景的人、人数控制多少 | 本入口 |
| `ai-transformation-playbook` AI转型路线图 | 传统企业变成 AI 公司，从试点到培训到战略的路线图怎么排 | 本入口 |
| `cross-functional-brainstorming` 跨职能头脑风暴 | 想搞一场工作坊，让懂业务的和懂 AI 的坐一起挖 AI 点子 | 本入口 |
| `triple-due-diligence` 三重尽职调查 | 这个 AI 项目要动一大笔预算，除了技术还得考虑哪些方面 | 本入口 |

### medium（8 张）

| 能力卡 | 触发提问 | 本包 |
|---|---|---|
| `dont-acquire-for-data` 不为数据而收购 | 收购他们的数据、先把数据买下来再说、数据量大自然有价值 | 独立 |
| `ai-pipeline` AI流水线设计 | 多个 AI 模块怎么串、端到端验收、复杂 AI 产品怎么拆 | 本入口 |
| `ai-strategy-moat` AI战略护城河 | 竞争对手也在用 AI，我们还剩哪些抄不走的老本行 | 本入口 |
| `automate-task` 自动化任务而非岗位 | 老板要把整个运营岗交给 AI，怎么拆成能落地的小块 | 本入口 |
| `pilot-momentum-flywheel` 试点势能飞轮 | 第一个 AI 试点选最容易成功的，还是选价值最高的 | 本入口 |
| `role-tiered-training` 分层AI培训 | 新员工培训和主管轮训的 AI 内容能一样吗、按什么维度拆课 | 本入口 |
| `start-small-find-partner` 从小处着手找伙伴 | 身边没人懂 AI，我想一个人入门没底，怎么先迈第一步 | 本入口 |
| `unified-data-warehouse` 统一数据仓库 | 数据分散在客户、订单、日志三套系统里，怎么汇到一处 | 本入口 |

**非能力类查询** → `overview.md`（书 / 作者 / 概览）、`glossary.md`（术语）、`cheatsheet.md`（决策规则速查）、`capability-index.md`（完整索引）。冲突时以 capability-index.md 为准。

---

## 全部测试用例（16 条 · 一条不漏）

`test-prompts.json` 的全部用例。**`minimum_pass_rate` = 0.8**（16 条中至少过 13 条；跨入口互斥负例不允许出错）。

### should_trigger（11 条）

| 提问原文 | 期望行为 | 类型 |
|---|---|---|
| 我们要设计一条由识别、分类、生成三段接力的AI链路，各段之间怎么定接口才不出错？ | 路由入口 → `AI流水线设计`（ai-pipeline） | should_trigger |
| 竞争对手也在用AI，我们想知道公司还剩下哪些它们抄不走的老本行？ | 路由入口 → `AI战略护城河`（ai-strategy-moat） | should_trigger |
| 我们想拉起一支AI小队，应该找哪些背景的人、人数控制在多少？ | 路由入口 → `AI团队构建`（ai-team-building） | should_trigger |
| 传统企业要整体变成AI驱动的公司，从试点到培训再到战略的完整路线图该怎么排？ | 路由入口 → `AI转型路线图`（ai-transformation-playbook） | should_trigger |
| 老板说要把整个运营岗交给AI，我知道这摊子太大，该怎么把它拆成能落地的小块？ | 路由入口 → `自动化任务而非岗位`（automate-task） | should_trigger |
| 我们想搞一场工作坊，让懂业务的和懂AI的坐在一起挖AI点子，怎么组织？ | 路由入口 → `跨职能头脑风暴`（cross-functional-brainstorming） | should_trigger |
| 公司要挑第一个AI试点，是选最容易成功的，还是选价值最高的？ | 路由入口 → `试点势能飞轮`（pilot-momentum-flywheel） | should_trigger |
| 新员工培训和主管轮训的AI内容能一样吗？公司该按什么维度把课程拆开？ | 路由入口 → `分层AI培训`（role-tiered-training） | should_trigger |
| 身边没人懂AI，我想一个人入门总没底，有什么办法先把第一步迈出去？ | 路由入口 → `从小处着手找伙伴`（start-small-find-partner） | should_trigger |
| 这个AI项目要动公司一大笔预算，除了技术，还得考虑哪些方面才不算拍脑袋？ | 路由入口 → `三重尽职调查`（triple-due-diligence） | should_trigger |
| 训练模型的数据分散在客户、订单、日志三套系统里，怎么把它们汇到一处给AI用？ | 路由入口 → `统一数据仓库`（unified-data-warehouse） | should_trigger |

### should_not_trigger（5 条）

| 提问原文 | 期望行为 | 类型 |
|---|---|---|
| 帮我调一下这个模型的学习率和批大小，用网格搜索还是贝叶斯优化？ | 不激活本书任何入口（none）——越界：超参调优属 out_of_scope | should_not_trigger |
| 帮我看看这段PyTorch训练代码，loss一直变成NaN，怎么改？ | 不激活本书任何入口（none）——越界：代码调试应转工程专家 | should_not_trigger |
| 我们这个行业做AI要过哪些监管合规审查，需要准备什么法律材料？ | 不激活本书任何入口（none）——越界：合规结论应转法务 | should_not_trigger |
| 我们计划训练一个客户流失预测模型，需要准备多少条历史样本才算够？ | **不激活路由入口**，应直达 `ml-feasibility` 独立 Skill | should_not_trigger |
| 我们模型在测试集上做到95%准确率，这个水平算不算达标、能不能上线？ | **不激活路由入口**，应直达 `statistical-acceptance` 独立 Skill | should_not_trigger |

### edge_case（0 条）

> 如实说明：`test-prompts.json` 中**没有** `edge_case` 用例。边界行为只写在 SKILL.md 的「边界与判停」里，**未落成可回归的测试**——这是本包最薄弱的一环，靠 5 条负例间接覆盖。

---

## 加载规则

- 每次任务先读 `SKILL.md`，再按路由表加载 **1** 张能力卡；任务明确跨域时最多加载 2 张。
- 概览 / 书名类问题**不加载**能力卡，用 SKILL.md 的「核心原则」+ `overview.md` 回答。
- 路由表与 `capability-index.md` 都无法命中的意图，**明确告知超出本书范围**，不硬套。

---

## 什么情况下不该用它

负面用例不是"答不上来"，而是**有更专业的入口**。这个包的边界分三类：

| 你的问题 | 为什么不该用这个包 |
|---|---|
| 具体模型选型、超参调优、框架 / 代码实现细节 | 课程讲的是通识决策框架，不是算法与工程实现。这是 out_of_scope 第一条 |
| 分布式训练、算力采购、生产部署运维方案 | 需要工程团队而非决策框架，本书没有素材 |
| AI 伦理与法规的正式合规意见或法律结论 | 应转交专业合规与法务判断，本书明确不提供合规结论 |
| 前沿研究论文解读与最新 SOTA 技术追踪 | 本书基于 2019 年监督学习范式，时效性有限 |
| 已晋级的 13 个能力域（即上表标「独立」的那些卡） | **不是答不上来，是有更专业的独立 Skill**：应直达对应 Skill，经路由入口进入反而是截胡（`router-notrigger-rev-01/02` 即防这个） |

另外，SKILL.md「边界与判停」里还有两条**停止条件**：

- 索要具体模型、超参数或可运行代码建议 → 说明超出本书范围，建议转算法 / 工程专家。
- 只是要课程笔记、或项目已决定推进只缺排期 → 直接回答 / 不重复启动可行性评估。

---

## 这本书不能全信的部分（本包已内建这些提醒）

以下 **9 条**全部来自 `references/overview.md` 的批判章节（5.1 时代局限 4 条 + 5.2 方法层面 3 条 + 5.3 样本与适用边界 2 条），一条不少：

### 时效性（最要命的一组 —— 课程录制于 2019 年）

1. **课程录制于 2019 年，是 LLM / 生成式 AI 普及之前的内容。** 全书技术默认值是**监督学习**：需大量 (A, B) 标注样本、先有数据再训练。**到 2026 年已过时**：「一秒法则」「概念简单性 × 数据充足性」这两个核心判据基于 2019 年水平，**对生成式 / 长文本生成任务必须重新校准**，不能直接套用。
2. **"先有数据再做模型"的顺序被部分反转。** 预训练模型把通用能力变成可购买的现成基础设施，很多任务从零样本 / 少样本起步再补数据。**已过时**：「数据准备占项目 60–80% 时间」（p08–p10）这一经验假设未必仍成立。
3. **"AI 是新型电力"仍成立，但基础设施形态已变。** "电厂"如今对应基础模型与云端 API，自建算力与自研模型的经济性大幅下降——「不在火车前冲刺」（p15）的**适用面反而扩大**，"哪些会标准化"需按当下格局重估。
4. **迭代节奏与团队分工被改写。** 用 LLM API 数天即可搭出可用 MVP，「迭代而非完美」（p20）的成本与周期已不同于课程假设；课程列举的 ML 工程师 / 数据工程师 / MLOps（p11–p13）**未覆盖 Prompt / LLM 应用工程、评测工程等新分工**，团队构成不能照搬。

### 方法层面

5. **课程面向非技术管理者，不含技术实现细节。** 模型选型、超参、部署监控、数据管道实现均不在范围内，**不能作为技术方案依据**。
6. **统计化验收、训练 / 测试集分离始终成立，但阈值口径必须按场景重设。** "95% 准确率""80% 标注一致性"是**示例不是标准**；错误代价高（如金融反欺诈）或假阳/假阴代价不同时，同一数字含义完全不同——课程**未给出阈值推导方法**。
7. **流程框架被理想化为线性，且低估了部署工程。** "AI 项目六阶段"（p08–p10）与 ML 工作流在现实中大量回退；"最后一公里"部署工程（API 设计、延迟优化、灰度发布）常占项目 50% 以上工作量，课程着墨不多。

### 样本与适用边界

8. **案例以美国大型企业为主**（Google、Amazon、TikTok、Tesla 等），中小企业与国内企业的资源约束覆盖不足——"2–3 年转型周期""建中心化专职 AI 部门"在 KPI 导向、编制紧张的中小组织里往往不具备条件。
9. **数据合规环境覆盖不足，高风险领域不能作合规依据。** 课程成书时并无中国《数据安全法》《个人信息保护法》的约束语境；"统一数据仓库""数据飞轮""数据收购"在数据出境、个人信息处理、行业准入上都需**本地化合规重审**。医疗、金融、招聘场景下课程均已判停或要求转交专业评估。

> 另需注意：本包与 `overview.md` 均由 24 张能力卡归纳，**未回原课程逐讲核对**；页码（pXX）引用取自能力卡已保留的原文，未新增。

---

## 文件结构

```
README.md  ← 你正在读的这份
ai-for-everyone-router/
  SKILL.md  ← 路由入口：核心原则 + 24 张卡路由表 + 加载规则 + 边界与判停
  test-prompts.json  ← 16 条用例（11 正向 / 5 负向），minimum_pass_rate = 0.8
  references/
    capability-index.md  ← 24 张能力的完整索引（ID / 标题 / 重要度 / 意图 / 关键词 / 卡路径）
    overview.md  ← 整书概览（五论点骨架 + 12 条核心命题 + 9 条批判）
    cheatsheet.md  ← 决策规则速查
    glossary.md  ← 术语词典（吴恩达本人的特定用法 + 易混词对照）
    capabilities/  ← 24 张能力卡，每张一个文件
      ml-feasibility.md  ml-workflow.md  ml-vs-ds.md
      data-flywheel.md  build-vs-buy.md  one-second-rule.md
      three-value-drivers.md  dont-wait-perfect-data.md  dont-acquire-for-data.md
      statistical-acceptance.md  train-test-split.md  ai-project-lifecycle.md
      iterate-not-perfect.md  ai-pipeline.md  ai-strategy-moat.md
      ai-team-building.md  ai-transformation-playbook.md  automate-task.md
      cross-functional-brainstorming.md  pilot-momentum-flywheel.md  role-tiered-training.md
      start-small-find-partner.md  triple-due-diligence.md  unified-data-warehouse.md
```

---

## 安装

### WorkBuddy / CodeBuddy / Claude Agent Skills

```bash
# Windows
cp -r ai-for-everyone-router ~/.workbuddy/skills/

# macOS / Linux
cp -r ai-for-everyone-router ~/.claude/skills/
```

项目级安装放在当前工作区的 `.workbuddy/skills/` 下，团队共享。

### 直接当 prompt 用

不需要 Skill 框架：把 `SKILL.md` 作为 system prompt，需要时再按路由表把 `references/capabilities/` 下对应的那**一张**卡一起喂进去。

**不要把 24 张卡一次性全喂进去** —— 上下文塞满判据，模型会混用口径（把 ML 的验收标准用到 DS 上、把「足够好数据」的门槛用在合规场景里）。概览类问题连卡都不用加，只喂「核心原则」。已单独安装的 13 张晋级 Skill 会让本包在这些能力域上主动让位。

---

## License

MIT

仓库: https://github.com/Jerry-Tang95/ai-for-everyone-skill
