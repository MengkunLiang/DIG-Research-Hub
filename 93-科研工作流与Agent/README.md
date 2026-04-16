# 科研工作流与 Agent（类型附录）

本目录保留为查全型附录，适合系统补科研 agent、deep research、自动科研闭环、多代理协作和研究工作流框架。

## 推荐先看

- [科研Agent系统](./科研Agent系统.md)
- [自动科研与闭环系统](./自动科研与闭环系统.md)
- [Deep Research与研究工作台](./Deep%20Research与研究工作台.md)
- [科研工作流设计模式](./科研工作流设计模式.md)
- [通用Agent框架](./通用Agent框架.md)

## 按任务回查

| 当前任务 | 更适合先看 |
| --- | --- |
| 选题、趋势扫描、研究情报 | [Deep Research与研究工作台](./Deep%20Research与研究工作台.md) |
| 自动化研究闭环、实验规划 | [自动科研与闭环系统](./自动科研与闭环系统.md) |
| 多代理协作与研究流程设计 | [科研工作流设计模式](./科研工作流设计模式.md) |
| 框架选型与基础能力对比 | [通用Agent框架](./通用Agent框架.md) |

## 2025-2026 不能漏掉的代表系统

| 系统 | 公开时间 / venue | 更适合看什么 | 入口 |
| --- | --- | --- | --- |
| AiScientist | arXiv `2604.13018`，提交于 `2026-04-14`；GitHub README 新闻写明首次公开为 `2026-04-13` | 长时程 ML research engineering、`File-as-Bus`、`PaperBench / MLE-Bench Lite` | [论文](https://arxiv.org/abs/2604.13018) / [AweAI-Team/AiScientist](https://github.com/AweAI-Team/AiScientist) |
| AI-Researcher | NeurIPS 2025 Spotlight；arXiv `2505.18705` | 从想法到实现到论文生成的完整自治科研系统，附 `Scientist-Bench` | [OpenReview](https://openreview.net/forum?id=kQWyOYUAC4) / [HKUDS/AI-Researcher](https://github.com/HKUDS/AI-Researcher) |
| Virtual Scientists (VirSci) | ACL 2025 Long | 多代理 scientific idea generation、science-of-science 风格协作模拟 | [ACL Anthology](https://aclanthology.org/2025.acl-long.1368/) / [InternScience/Virtual-Scientists](https://github.com/InternScience/Virtual-Scientists) |
| ResearchAgent | NAACL 2025 Long | 文献驱动的 idea generation、reviewing agent 迭代修正 | [ACL Anthology](https://aclanthology.org/2025.naacl-long.342/) |
| AI-Scientist / AI-Scientist-v2 | v1 为 Sakana AI 2024 开源主线，v2 为 `2025-04` 公开的 workshop-level agentic tree search 系统 | 自动科研经典主线，适合看“模板化自治科研”到“更泛化 tree search”演化 | [SakanaAI/AI-Scientist](https://github.com/SakanaAI/AI-Scientist) / [SakanaAI/AI-Scientist-v2](https://github.com/SakanaAI/AI-Scientist-v2) |

## 高频公开资源

| 资源 | 类型 | 简述 | 链接 |
| --- | --- | --- | --- |
| AiScientist | 长时程科研工程系统 | 适合查看 `File-as-Bus` 如何支撑长时间研究实现、调试和持续实验。 | [AweAI-Team/AiScientist](https://github.com/AweAI-Team/AiScientist) |
| AI-Researcher | 自治科研系统 | 适合查看从 idea、survey、实现到 paper writing 的完整自动科研流水线。 | [HKUDS/AI-Researcher](https://github.com/HKUDS/AI-Researcher) |
| AI-Scientist | 自动科研系统 | 适合查看较早期但非常经典的“自动生成 idea 与实验论文”开源实现。 | [SakanaAI/AI-Scientist](https://github.com/SakanaAI/AI-Scientist) |
| ResearchAgent | 想法生成系统 | 适合查看“核心论文 + 学术图谱 + reviewing agents”的 ideation 主线。 | [ACL Anthology](https://aclanthology.org/2025.naacl-long.342/) |
| Virtual Scientists (VirSci) | 多代理 idea generation | 适合查看多科学家协作式 ideation 与新颖性提升机制。 | [InternScience/Virtual-Scientists](https://github.com/InternScience/Virtual-Scientists) |
| RD-Agent | 研究开发代理 | 适合研发自动化与实验循环。 | [microsoft/RD-Agent](https://github.com/microsoft/RD-Agent) |
| AgentLaboratory | 多代理科研系统 | 适合把研究流程拆成协作环节。 | [SamuelSchmidgall/AgentLaboratory](https://github.com/SamuelSchmidgall/AgentLaboratory) |
| AI-Scientist-v2 | 自动科研系统 | 适合查看从想法到实验的闭环实现。 | [SakanaAI/AI-Scientist-v2](https://github.com/SakanaAI/AI-Scientist-v2) |
| Open Deep Research | 开源 deep research agent | 适合观察 deep research 应用的开放实现。 | [langchain-ai/open_deep_research](https://github.com/langchain-ai/open_deep_research) |
| CMBAgent | 科学研究多代理系统 | 适合查看 domain-agnostic 的 autonomous scientific research engine。 | [CMBAgents/cmbagent](https://github.com/CMBAgents/cmbagent) |
| OpenHands Software Agent SDK | 代理开发框架 | 适合搭建可执行代码与工具的代理。 | [OpenHands/software-agent-sdk](https://github.com/OpenHands/software-agent-sdk) |
| Aviary | 科学任务环境 | 适合给科研 agent 提供带工具和 scientific tasks 的语言环境。 | [Future-House/aviary](https://github.com/Future-House/aviary) |
| LiveDRBench | deep research benchmark | 适合评测 deep research 与 claim discovery 能力。 | [microsoft/livedrbench](https://github.com/microsoft/livedrbench) |
| NewtonBench | 科学定律发现 benchmark | 适合评测交互式科学发现与主动实验能力，而不只是静态拟合。 | [HKUST-KnowComp/NewtonBench](https://github.com/HKUST-KnowComp/NewtonBench) |

## 推荐配合使用的页面

- [05-实验执行、复现与评测](../05-实验执行、复现与评测/README.md)
- [98-全局索引/Agent与工作流索引](../98-全局索引/Agent与工作流索引.md)
- [08-方向专题/AI4Science与Scientific Discovery](../08-方向专题/AI4Science与Scientific%20Discovery.md)
