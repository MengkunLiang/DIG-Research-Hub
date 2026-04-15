# AI / ML / Data Mining 资源

这一页聚焦 `AI / ML / data mining` 主线方向中最值得优先接入的公共资源。重点不是做“全领域百科”，而是把研究自动化、实验执行、benchmark、数据层、常用框架和公开合集整理成可直接转入研究工作流的方向视图。

## 这一步通常要回答的问题

1. AI/ML 主线里哪些 benchmark 最适合用来做稳定 baseline 与 agent 评测。
2. tabular、graph、推荐、检索、异常检测、因果推断等子方向分别有哪些高频框架。
3. 哪些 `Skills`、`MCP` 和实验平台最适合优先接到 AI/ML 研究链路里。
4. 哪些公开合集最适合继续补库，而不是停留在单条仓库链接。

## 推荐先看

- [05-实验执行、复现与评测](../05-实验执行、复现与评测/README.md)
- [91-Skills/科研工程与实验Skills](../91-Skills/科研工程与实验Skills.md)
- [92-MCP/实验执行与数据工程MCP](../92-MCP/实验执行与数据工程MCP.md)
- [AI4Science与Scientific Discovery](./AI4Science与Scientific%20Discovery.md)

## 一、相关 Skills

| 资源 | 类型 | 更适合的用途 | 链接 |
| --- | --- | --- | --- |
| 科研工程与实验Skills | 仓库内附录 | 当前仓库中训练、评测、自动化执行和实验工程 Skills 的主归属页。 | [91-Skills/科研工程与实验Skills](../91-Skills/科研工程与实验Skills.md) |
| 科学计算与领域Skills | 仓库内附录 | 当 AI/ML 与材料、生物、科学计算交叉时的 Skill 入口。 | [91-Skills/科学计算与领域Skills](../91-Skills/科学计算与领域Skills.md) |
| AI Research SKILLs | 研究工程技能库 | 覆盖训练、调试、评测、MLOps 和研究工作流。 | [Orchestra-Research/AI-Research-SKILLs](https://github.com/Orchestra-Research/AI-Research-SKILLs) |
| Claude Scientific Skills | 科学技能总库 | 适合补科研数据库、Python 包、分析流程与 scientific workflow。 | [K-Dense-AI/claude-scientific-skills](https://github.com/K-Dense-AI/claude-scientific-skills) |
| Hugging Face Skills | 官方技能生态 | `hf_model_evaluation`、`hf_dataset_creator`、`hf-llm-trainer` 等能力更适合 AI/ML 场景。 | [huggingface/skills](https://github.com/huggingface/skills) |
| OpenAI Skills / Anthropic Skills | 官方技能生态 | 适合补代码审查、工具编排、文档处理和 agent workflow 基础能力。 | [openai/skills](https://github.com/openai/skills)、[anthropics/skills](https://github.com/anthropics/skills) |

## 二、相关 MCP

| 资源 | 类型 | 更适合的用途 | 链接 |
| --- | --- | --- | --- |
| 实验执行与数据工程MCP | 仓库内附录 | Jupyter、GitHub、Kaggle、Optuna、Prefect、ZenML 等执行层入口。 | [92-MCP/实验执行与数据工程MCP](../92-MCP/实验执行与数据工程MCP.md) |
| 文献检索与知识库MCP | 仓库内附录 | OpenAlex、paper-search、OpenReview、Zotero 等文献与知识层入口。 | [92-MCP/文献检索与知识库MCP](../92-MCP/文献检索与知识库MCP.md) |
| Jupyter MCP Server | Notebook MCP | AI/ML 实验执行、分析与可视化的核心入口。 | [datalayer/jupyter-mcp-server](https://github.com/datalayer/jupyter-mcp-server) |
| GitHub MCP Server / GitMCP | 仓库与代码 MCP | 适合读取 benchmark 仓库、基线代码、CI 和 issue。 | [github/github-mcp-server](https://github.com/github/github-mcp-server)、[idosal/git-mcp](https://github.com/idosal/git-mcp) |
| Kaggle MCP | 数据平台 MCP | 适合补数据集发现与快速原型数据入口。 | [arrismo/kaggle-mcp](https://github.com/arrismo/kaggle-mcp) |
| Optuna MCP / Prefect MCP / ZenML MCP | 调参与 orchestration MCP | 适合把 HPO、pipeline、artifact 和运行状态接入 agent workflow。 | [optuna/optuna-mcp](https://github.com/optuna/optuna-mcp)、[PrefectHQ/prefect-mcp-server](https://github.com/PrefectHQ/prefect-mcp-server)、[zenml-io/mcp-zenml](https://github.com/zenml-io/mcp-zenml) |
| OpenAlex MCP / Paper Search MCP | 学术与 benchmark 检索 MCP | 适合回查论文、任务定义、benchmark 论文和最新工作。 | [hbiaou/openalex-mcp](https://github.com/hbiaou/openalex-mcp)、[openags/paper-search-mcp](https://github.com/openags/paper-search-mcp) |

## 三、研究自动化与 AI/ML 研究 Agent

| 资源 | 类型 | 更适合的用途 | 链接 |
| --- | --- | --- | --- |
| MLE-bench | ML engineering benchmark | 适合评估 agent 是否能真正完成 ML 工程任务、debug、调参和提分。 | [OpenAI - MLE-bench](https://openai.com/index/mle-bench/) |
| MLGym | AI research benchmark | 专门面向机器学习研究任务的评测环境。 | [facebookresearch/MLGym](https://github.com/facebookresearch/MLGym) |
| ResearcherBench | deep research benchmark | 适合评测长链条研究代理在高难度研究任务上的表现。 | [GAIR-NLP/ResearcherBench](https://github.com/GAIR-NLP/ResearcherBench) |
| ToolSandbox | tool-use benchmark | 适合测多轮工具调用、状态化执行和复杂任务编排。 | [apple/ToolSandbox](https://github.com/apple/ToolSandbox) |
| ML-Dev-Bench | ML development benchmark | 更偏模型开发、实验实现、调试与新思路落地。 | [ml-dev-bench/ml-dev-bench](https://github.com/ml-dev-bench/ml-dev-bench) |
| OpenML | 开放 ML 平台 | 提供开放数据、tasks、runs 和 benchmark suites，适合复现实验和标准化比较。 | [OpenML](https://openml.org/)、[OpenML Docs](https://docs.openml.org/) |

## 四、核心框架与 benchmark 入口

### 1. Tabular / AutoML

| 资源 | 类型 | 更适合的用途 | 链接 |
| --- | --- | --- | --- |
| AutoMLBenchmark | benchmarking 框架 | 对比 AutoML 系统和自定义 workflow。 | [openml/automlbenchmark](https://github.com/openml/automlbenchmark) |
| TabArena | living tabular benchmark | 适合持续维护 tabular 对照实验。 | [autogluon/tabarena](https://github.com/autogluon/tabarena) |
| AutoGluon | AutoML 框架 | 适合快速建立 tabular、multimodal 与 time series baseline。 | [autogluon/autogluon](https://github.com/autogluon/autogluon) |
| auto-sklearn | AutoML 框架 | 经典 tabular AutoML 入口。 | [automl/auto-sklearn](https://github.com/automl/auto-sklearn) |
| FLAML | 轻量 AutoML 框架 | 适合快速迭代与成本敏感搜索。 | [microsoft/FLAML](https://github.com/microsoft/FLAML) |

### 2. Graph / Knowledge Graph / Structured Mining

| 资源 | 类型 | 更适合的用途 | 链接 |
| --- | --- | --- | --- |
| PyTorch Geometric | 图学习框架 | GNN、heterogeneous graph、graph mining 的高频底座。 | [pyg-team/pytorch_geometric](https://github.com/pyg-team/pytorch_geometric) |
| DGL | 图学习框架 | 图学习与工程化训练的主流底座之一。 | [dmlc/dgl](https://github.com/dmlc/dgl) |
| OGB | 图学习 benchmark | 标准化 graph benchmark 与 evaluator 入口。 | [snap-stanford/ogb](https://github.com/snap-stanford/ogb) |
| GRB | graph robustness benchmark | 图鲁棒性、对抗评测与安全扩展入口。 | [THUDM/grb](https://github.com/THUDM/grb) |
| PyKEEN | 知识图谱表示学习 | KGE、link prediction 和 KG research 的常用框架。 | [pykeen/pykeen](https://github.com/pykeen/pykeen) |

### 3. Recommender Systems / Retrieval / Embeddings

| 资源 | 类型 | 更适合的用途 | 链接 |
| --- | --- | --- | --- |
| RecBole | 推荐系统框架 | 推荐算法、数据处理和评测流程的高频底座。 | [RUCAIBox/RecBole](https://github.com/RUCAIBox/RecBole) |
| Cornac | 推荐系统框架 | 更偏研究原型、多模态推荐和可比实验。 | [PreferredAI/cornac](https://github.com/PreferredAI/cornac) |
| Pyserini | 检索研究工具箱 | dense / sparse retrieval、reranking 和 IR 实验的高频工具。 | [castorini/pyserini](https://github.com/castorini/pyserini) |
| BEIR | 检索 benchmark | 跨域 IR 对照和 RAG retriever 评测入口。 | [beir-cellar/beir](https://github.com/beir-cellar/beir) |
| MTEB | embedding benchmark | 表征学习、语义检索与多任务 embedding 评测入口。 | [embeddings-benchmark/mteb](https://github.com/embeddings-benchmark/mteb) |

### 4. Anomaly Detection / Causal Inference

| 资源 | 类型 | 更适合的用途 | 链接 |
| --- | --- | --- | --- |
| PyOD | 异常检测工具箱 | 建立 outlier / anomaly detection 稳定 baseline。 | [yzhao062/pyod](https://github.com/yzhao062/pyod) |
| PyGOD | 图异常检测 | 图异常、欺诈、风控与 relational anomaly 研究入口。 | [pygod-team/pygod](https://github.com/pygod-team/pygod) |
| ADBench | 异常检测 benchmark | 适合系统比较异常检测算法、噪声设置和鲁棒性。 | [Minqi824/ADBench](https://github.com/Minqi824/ADBench) |
| DoWhy | 因果推断框架 | 适合把因果图、识别和 refutation 写成可追溯流程。 | [py-why/dowhy](https://github.com/py-why/dowhy) |
| causal-learn | 因果发现 | 适合探索变量结构与机制图。 | [py-why/causal-learn](https://github.com/py-why/causal-learn) |
| EconML / DoubleML | 异质性效应与双重机器学习 | 适合 treatment heterogeneity、政策评估与高维因果。 | [py-why/EconML](https://github.com/py-why/EconML)、[DoubleML](https://github.com/DoubleML/doubleml-for-py) |
| CausalBench | 因果 benchmark | 因果发现与因果机制比较的公开 benchmark。 | [ravivanpong/CausalBench](https://github.com/ravivanpong/CausalBench) |

## 五、外部整合入口

| 资源 | 类型 | 更适合的用途 | 链接 |
| --- | --- | --- | --- |
| awesome-data-agents | 外部合集 | 数据代理、分析代理与 data-centric agent 资源入口。 | [HKUSTDial/awesome-data-agents](https://github.com/HKUSTDial/awesome-data-agents) |
| Toolathlon | 外部合集 | tool-use benchmark、agent benchmark 和任务型评测入口。 | [hkust-nlp/Toolathlon](https://github.com/hkust-nlp/Toolathlon) |
| AgentBoard | 外部合集 | 继续扩展 agent benchmark 与任务维度。 | [hkust-nlp/AgentBoard](https://github.com/hkust-nlp/AgentBoard) |
| awesome-production-machine-learning | 外部合集 | MLOps、训练、部署、监控与生产级机器学习入口。 | [EthicalML/awesome-production-machine-learning](https://github.com/EthicalML/awesome-production-machine-learning) |
| awesome-causal-inference | 外部合集 | 因果推断论文、工具和资源入口。 | [matteocourthoud/awesome-causal-inference](https://github.com/matteocourthoud/awesome-causal-inference) |
| awesome-RecSys | 外部合集 | 推荐系统方向的资源和项目入口。 | [wusw14/awesome-recsys](https://github.com/wusw14/awesome-recsys) |

## 六、推荐组合

1. `OpenML + AutoGluon / FLAML + MLflow + DVC`
   适合建立稳定 tabular baseline 与可复现实验闭环。
2. `PyG / DGL + OGB + PyGOD / PyKEEN`
   适合 graph mining、知识图谱和图异常方向。
3. `RecBole / Cornac + Pyserini + BEIR + MTEB`
   适合推荐、检索、embedding 和 RAG 基线比较。
4. `DoWhy + causal-learn + EconML / DoubleML`
   适合 AI/ML 与政策、机制识别、平台治理交叉研究。
5. `MLE-bench + MLGym + ToolSandbox + ML-Dev-Bench`
   适合系统评估 AI/ML research agent 与自动化实验系统。

## 七、仓库内延伸阅读

- [05-实验执行、复现与评测](../05-实验执行、复现与评测/README.md)
- [07-安全与治理](../07-安全与治理/README.md)
- [AI4Science与Scientific Discovery](./AI4Science与Scientific%20Discovery.md)
- [Computational-Design-Science与管理技术交叉](./Computational-Design-Science与管理技术交叉.md)
