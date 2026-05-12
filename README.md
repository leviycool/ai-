# AI Publishing Operating System

这是一个面向海外游戏发行的 AI 协作仓库。

它不是聊天记录存放处，而是一个把高频发行工作逐步沉淀为系统的工作台：先处理真实任务，再把可复用的判断逻辑、信号和规则积累成资产。

## 仓库结构
- `AGENTS.md`
  长期稳定的原则、分工和判断标准。
- `01_inbox/`
  原始问题、临时线索、待分拣输入。
- `02_workspaces/`
  每个具体问题的分析工作区。
- `03_workflows/`
  高频任务的标准处理流程。
- `04_templates/`
  开工模板、分析模板、决策模板。
- `05_assets/`
  沉淀后的长期资产库。
- `06_decisions/`
  最终业务判断和关键决策记录。
- `docs/`
  系统运行规则、证据分级、文档路由说明。

## 默认工作流
1. 新问题先进入 `01_inbox/`，只记录事实、来源、时间和原始诉求。
2. 需要分析的问题进入 `02_workspaces/active/`，使用对应模板展开。
3. 处理时优先参考 `03_workflows/`，避免每次从零拆解。
4. 有复用价值的结论进入 `05_assets/`，更新旧版本而不是重复堆叠。
5. 最终业务判断进入 `06_decisions/`，记录决策依据、阈值和复盘日期。

## 推荐起步方式
- 日常投放异常：从 `03_workflows/01_ad_diagnosis.md` 开始。
- 素材复盘与创意拆解：从 `03_workflows/02_creative_intelligence.md` 开始。
- 竞品动态跟踪：从 `03_workflows/03_competitor_watch.md` 开始。
- 市场变化与热点判断：从 `03_workflows/04_market_watch.md` 开始。
- 新产品立项或发行判断：从 `03_workflows/05_launch_evaluation.md` 开始。
- 发行经验反哺产品：从 `03_workflows/06_product_feedback.md` 开始。

## 命名建议
- 工作区文件：`YYYY-MM-DD_topic.md`
- 决策文件：`YYYY-MM-DD_decision-topic.md`
- 信号记录：`YYYY-MM-DD_signal-topic.md`
- 资产文档：按主题长期维护，避免每天新建一份相似文件

## 当前最值得优先沉淀的资产
- 创意方法论
- 平台投放经验
- 优化规则库
- 竞品信号库
- 市场洞察库
- 产品反哺模式库
