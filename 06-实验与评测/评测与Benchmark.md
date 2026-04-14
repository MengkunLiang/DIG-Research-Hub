# 评测与 Benchmark

科研智能体不只要“看起来很聪明”，还要能被评估。下面这些资源很适合给 ResearchOS 建 benchmark 与回归测试体系。

## 1. 科研 / 研究工程相关 Benchmark

| 资源 | 类型 | 简述 | 链接 |
| --- | --- | --- | --- |
| MLE-bench | ML engineering benchmark | 强调真实 ML 工程任务与 Kaggle 风格问题，对科研实验能力评估很有价值。 | [OpenAI - MLE-bench](https://openai.com/index/mle-bench/) |
| Aviary | Agent 环境基座 | Future House 的 language agent gym，含科学文献搜索与 notebook 环境。 | [Future-House/aviary](https://github.com/Future-House/aviary) |
| LAB-Bench | 科学研究 benchmark | 面向生物科学研究能力的评测集，也适合作为科研 agent 评测参考。 | [Future-House/LAB-Bench](https://github.com/Future-House/LAB-Bench) |

## 2. 通用模型 / RAG / Agent 评测资源

| 资源 | 类型 | 简述 | 链接 |
| --- | --- | --- | --- |
| OpenCompass | 大模型评测平台 | 中文社区比较常用，适合做基准评估与任务对比。 | [open-compass/opencompass](https://github.com/open-compass/opencompass) |
| lm-evaluation-harness | 语言模型评测 | 经典的 LLM benchmark 执行框架。 | [EleutherAI/lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness) |
| Ragas | RAG 评测 | 如果你的科研系统里有文献问答或知识库检索，这个很值得接。 | [explodinggradients/ragas](https://github.com/explodinggradients/ragas) |
| HELM | 评测框架 | 更适合理解综合评测设计和多任务基线。 | [stanford-crfm/helm](https://github.com/stanford-crfm/helm) |
| Papers with Code SOTA | 公开榜单 | 适合做外部 baseline 对照和任务标准追踪。 | [Papers with Code SOTA](https://paperswithcode.com/sota) |

## 3. 给 ResearchOS 的评测建议

### 至少做三类评测

1. 文献理解质量
2. 研究工程执行质量
3. Agent 工作流稳定性

### 对应可以参考的资源

- 文献理解：`PaperQA2` 风格问答、人工标注 claim 集
- 工程执行：`MLE-bench`
- 工作流稳定性：`Aviary`

## 4. 更实用的落地方式

不要一开始就想做一个巨大的 benchmark 平台，建议按下面顺序来：

1. 先做 10 到 20 个内部黄金任务
2. 再引入 `MLE-bench / Aviary / Ragas`
3. 最后再把 benchmark 和 CI、回归测试绑起来

这样最容易真正形成持续迭代的评测闭环。
