# 科研 Agent 系统

本页从系统视角整理“科研型 Agent”生态。相比单纯收集框架，这里更关注已经把 `检索 -> 阅读 -> 想法生成 -> 实验 -> 写作 -> 评测` 串成链路的系统、项目和研究原型。

## 1. 科研 Agent 版图

| 类型 | 代表资源 | 简述 |
| --- | --- | --- |
| Deep Research 与研究工作台 | [Open Research](https://www.open-research.info/)、[RTI](https://github.com/yrc-better/RTI)、[PaperQA2](https://github.com/Future-House/paper-qa)、[STORM](https://github.com/stanford-oval/storm)、[langchain-ai/open_deep_research](https://github.com/langchain-ai/open_deep_research)、[Alibaba-NLP/DeepResearch](https://github.com/Alibaba-NLP/DeepResearch)、[GPT Researcher](https://github.com/assafelovic/gpt-researcher)、[ResearStudio](https://github.com/ResearAI/ResearStudio) | 强调文献检索、证据汇总、长报告生成、可编辑研究计划与协作式深度研究。 |
| 自动科研与自主闭环 | [AiScientist](https://github.com/AweAI-Team/AiScientist)、[AI-Researcher](https://github.com/HKUDS/AI-Researcher)、[AI-Scientist](https://github.com/SakanaAI/AI-Scientist)、[AI-Scientist-v2](https://github.com/SakanaAI/AI-Scientist-v2)、[microsoft/RD-Agent](https://github.com/microsoft/RD-Agent)、[AgentLaboratory](https://github.com/SamuelSchmidgall/AgentLaboratory)、[CMBAgents/cmbagent](https://github.com/CMBAgents/cmbagent)、[Future-House/robin](https://github.com/Future-House/robin)、[The Station](https://github.com/dualverse-ai/station) | 强调从研究问题到实验执行、结果反馈与迭代修正的完整闭环。 |
| 想法生成 / novelty / review | [AI Co-Scientist](https://research.google/blog/accelerating-scientific-breakthroughs-with-an-ai-co-scientist/)、[ResearchAgent](https://aclanthology.org/2025.naacl-long.342/)、[Virtual Scientists (VirSci)](https://aclanthology.org/2025.acl-long.1368/)、[HypoGeniC](https://github.com/ChicagoHAI/hypothesis-generation)、[llm4novelty](https://github.com/njust-winchy/llm4novelty)、[ReviewAdvisor](https://github.com/neulab/ReviewAdvisor) | 关注课题空白识别、想法扩散、审稿人式自检与新颖性评估。 |
| 代码执行与实验代理 | [OpenHands](https://github.com/OpenHands/OpenHands)、[OpenHands Software Agent SDK](https://github.com/OpenHands/software-agent-sdk)、[google/adk-python](https://github.com/google/adk-python) | 偏向代码库操作、实验实现、工具调用和可扩展代理执行环境。 |
| 科学任务环境与 benchmark | [Future-House/aviary](https://github.com/Future-House/aviary)、[Future-House/LAB-Bench](https://github.com/Future-House/LAB-Bench)、[HKUST-KnowComp/NewtonBench](https://github.com/HKUST-KnowComp/NewtonBench)、[microsoft/livedrbench](https://github.com/microsoft/livedrbench) | 更偏真实 scientific tasks、任务环境和 agent 评测，而不只是聊天型 demo。 |
| 协作式科研基础设施 | [AgentRxiv](https://agentrxiv.github.io/)、[OpenReview](https://openreview.net/)、[NLPeer](https://github.com/UKPLab/nlpeer) | 支撑跨代理共享成果、同行评审模拟和审稿数据挖掘。 |

## 2. 2025-2026 不能漏掉的代表系统

| 系统 | 公开信息 | 更适合参考的能力 | 入口 |
| --- | --- | --- | --- |
| AiScientist | arXiv `2604.13018`，`2026-04-14` 提交；GitHub README 记录首次公开为 `2026-04-13` | 长时程研究工程、`File-as-Bus`、工作区即系统状态、`PaperBench / MLE-Bench Lite` | [论文](https://arxiv.org/abs/2604.13018) / [代码](https://github.com/AweAI-Team/AiScientist) |
| AI-Researcher | NeurIPS 2025 Spotlight；arXiv `2505.18705` | 完整自治科研、`Scientist-Bench`、从参考文献出发自动生成 idea 并落地实现 | [OpenReview](https://openreview.net/forum?id=kQWyOYUAC4) / [代码](https://github.com/HKUDS/AI-Researcher) |
| Virtual Scientists (VirSci) | ACL 2025 Long | 多代理科学家团队、idea generation、science-of-science 协作机制 | [论文](https://aclanthology.org/2025.acl-long.1368/) / [代码](https://github.com/InternScience/Virtual-Scientists) |
| ResearchAgent | NAACL 2025 Long | 文献驱动 research ideation、reviewing agent 反思式迭代修正 | [论文](https://aclanthology.org/2025.naacl-long.342/) |
| AI-Scientist | Sakana AI 2024 开源主线 | 模板化自动科研、自动 idea 与实验论文生成的经典起点 | [代码](https://github.com/SakanaAI/AI-Scientist) |
| AI-Scientist-v2 | `2025-04` 开源，Workshop-Level Automated Scientific Discovery via Agentic Tree Search | 更泛化的实验管理与 tree search，不再强依赖人工模板 | [代码](https://github.com/SakanaAI/AI-Scientist-v2) |

## 3. 容易混淆但其实不是一条线的系统

| 名称 | 核心差异 | 更像什么 |
| --- | --- | --- |
| `AI-Scientist` | Sakana AI 的早期开源主线，强调模板化自动科研与开放式 idea 生成 | 自动科研经典基线 |
| `AI-Scientist-v2` | 在 v1 基础上进一步走向更泛化的 agentic tree search 和 workshop 论文闭环 | 更强的科研闭环升级版 |
| `AiScientist` | `2026-04-14` 提交到 arXiv 的长时程 ML research engineering 系统，核心是 `File-as-Bus` | 研究工程系统与长时程执行架构 |

## 4. 从哪几页继续展开

| 页面 | 适合关注的重点 |
| --- | --- |
| [自动科研与闭环系统](./自动科研与闭环系统.md) | `AI-Scientist-v2 / RD-Agent / AgentLaboratory / Robin / Station` 这一条“自主研究闭环”主线。 |
| [Deep Research与研究工作台](./Deep%20Research与研究工作台.md) | `Open Research / STORM / DeepResearch / GPT Researcher / ResearStudio` 这一条“深度检索与研究工作台”主线。 |
| [科研工作流设计模式](./科研工作流设计模式.md) | 把系统拆到模块级：文献扫描、证据卡片、novelty 审计、实验执行、写作与 rebuttal。 |
| [通用Agent框架](./通用Agent框架.md) | 编排、状态机、结构化输出、工具调用、生产化框架的底座选择。 |

## 5. 面向科研工作流的组合视角

| 目标链路 | 适合优先参考的资源 | 说明 |
| --- | --- | --- |
| 文献综述与 landscape | `RTI`、`Open Research`、`PaperQA2`、`STORM`、`open_deep_research`、`GPT Researcher` | 适合搭建“搜索、证据抽取、引用汇总、长报告生成”这一段前链路。 |
| novelty 与 idea 生成 | `AI Co-Scientist`、`HypoGeniC`、`ResearchAgent`、`Virtual Scientists (VirSci)`、`llm4novelty`、`ReviewAdvisor` | 适合构造“研究空白发现、候选想法扩展、审稿式自检”的中段流程。 |
| 自动实验与数据科学闭环 | `AiScientist`、`AI-Researcher`、`RD-Agent`、`AgentLaboratory`、`AI-Scientist-v2`、`CMBAgent`、`OpenHands SDK` | 适合搭建“实验计划 -> 代码实现 -> 运行反馈 -> 结果修正”的执行环。 |
| 生物医药 / 科学发现 | `Robin`、`Station`、`Aviary`、`LAB-Bench`、`NewtonBench` | 更贴近科学发现、实验推理和领域型 agent 评测。 |
| 写作、审稿与转投 | `Open Research`、`OpenDraft`、`OpenReview`、[模板迁移与投稿](../97-模板与投稿/模板迁移与投稿.md) | 适合覆盖草稿生成、review response、模板迁移与投稿后链路。 |

## 6. 观察这些系统时最值得抽象出来的公共结构

1. `研究计划显式化`：把 query plan、子问题树、搜索日志和证据卡片做成单独 artifact，而不是只保留聊天上下文。
2. `执行与评测解耦`：实验执行器、代码代理、评测器、审稿代理最好是分层组件，便于替换和审计。
3. `证据链优先`：科研系统和通用对话系统最大的差别，通常不在“会不会对话”，而在“能否回到论文、数据、代码和日志”。
4. `人机协同节点`：在课题定义、实验方案冻结、结果归因和投稿输出前设置人工 gate，通常比完全放权更稳。
5. `共享记忆与持续积累`：AgentRxiv、OpenReview、Zotero、实验追踪系统共同指向一个趋势，即科研代理越来越依赖可复用知识资产。

## 7. 延伸阅读

- [自动科研与闭环系统](./自动科研与闭环系统.md)
- [Deep Research与研究工作台](./Deep%20Research与研究工作台.md)
- [科研工作流设计模式](./科研工作流设计模式.md)
- [科研新颖性与Idea生成](../08-方向专题/科研新颖性与Idea生成.md)
- [评测与Benchmark](../96-实验与评测/评测与Benchmark.md)
