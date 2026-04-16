# AI4Science 与 Scientific Discovery

这一页聚焦 AI scientist、scientific discovery agents、科学任务 benchmark 以及化学、材料、生物方向最常见的开源框架和公共资源。适合把“AI/ML 基础能力”进一步推进到“面向科学发现与领域任务”的研究链路。

## 这一步通常要回答的问题

1. 哪些系统和 benchmark 最适合评估 AI scientist、scientific reasoning 和 scientific tool use。
2. 哪些开源框架最值得优先接入化学、材料和生命科学方向。
3. 哪些 `Skills`、`MCP`、领域数据平台和工作流工具最适合做 AI4Science。
4. 哪些外部合集最适合继续扩展 scientific discovery 资源。

## 推荐先看

- [AI-ML-DataMining资源](./AI-ML-DataMining资源.md)
- [91-Skills/科学计算与领域Skills](../91-Skills/科学计算与领域Skills.md)
- [92-MCP/生物医药与专利MCP](../92-MCP/生物医药与专利MCP.md)
- [05-实验执行、复现与评测](../05-实验执行、复现与评测/README.md)

## 一、相关 Skills 与 MCP

| 资源 | 类型 | 更适合的用途 | 链接 |
| --- | --- | --- | --- |
| 科学计算与领域Skills | 仓库内附录 | AI4Science、scientific computing、领域数据库和专用 workflow 的 Skill 入口。 | [91-Skills/科学计算与领域Skills](../91-Skills/科学计算与领域Skills.md) |
| Claude Scientific Skills / Scientific Agent Skills | 科学技能总库 | 适合补 scientific databases、Python packages、research methodology 与领域流程。 | [K-Dense-AI/claude-scientific-skills](https://github.com/K-Dense-AI/claude-scientific-skills)、[K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) |
| Materials Simulation Skills | 领域技能包 | 适合材料模拟、数值稳定性、solver 和 simulation workflow。 | [HeshamFS/materials-simulation-skills](https://github.com/HeshamFS/materials-simulation-skills) |
| 生物医药与专利MCP | 仓库内附录 | 生命科学、药物、专利和创新数据的 MCP 入口。 | [92-MCP/生物医药与专利MCP](../92-MCP/生物医药与专利MCP.md) |
| Hugging Face MCP Server | 模型与数据资产 MCP | 适合回查模型卡、数据集卡和 scientific model / dataset hub。 | [huggingface/hf-mcp-server](https://github.com/huggingface/hf-mcp-server) |
| Jupyter MCP / GitHub MCP / Paper Search MCP | 执行与检索 MCP | 适合把 notebook、代码仓库和 scientific literature 接进同一工作流。 | [datalayer/jupyter-mcp-server](https://github.com/datalayer/jupyter-mcp-server)、[github/github-mcp-server](https://github.com/github/github-mcp-server)、[openags/paper-search-mcp](https://github.com/openags/paper-search-mcp) |

## 二、scientific discovery agents 与 benchmark

| 资源 | 类型 | 更适合的用途 | 链接 |
| --- | --- | --- | --- |
| AI Co-Scientist | 科学假设生成系统 | ideation、reflection、ranking 与 evidence retrieval 的代表性系统。 | [Google Research Blog](https://research.google/blog/accelerating-scientific-breakthroughs-with-an-ai-co-scientist/) |
| AI Scientist / AI Scientist-v2 | 自动科研系统 | 从 idea 到实验、到 paper generation 的代表性开源系统。 | [SakanaAI/AI-Scientist](https://github.com/SakanaAI/AI-Scientist)、[SakanaAI/AI-Scientist-v2](https://github.com/SakanaAI/AI-Scientist-v2) |
| Robin | scientific discovery agent | FutureHouse 的科学发现方向系统入口。 | [Future-House/robin](https://github.com/Future-House/robin) |
| SciAgentsDiscovery | scientific discovery agents | 知识图谱 + 多 agent 科学发现系统。 | [lamm-mit/SciAgentsDiscovery](https://github.com/lamm-mit/SciAgentsDiscovery) |
| ScienceAgentBench | benchmark | 适合评测 scientific tool use 与科学任务型代理。 | [OSU-NLP-Group/ScienceAgentBench](https://github.com/OSU-NLP-Group/ScienceAgentBench) |
| ResearcherBench | benchmark | 适合评测深研究、长链推理与研究工作流。 | [GAIR-NLP/ResearcherBench](https://github.com/GAIR-NLP/ResearcherBench) |
| LiveDRBench | benchmark | 适合评测 deep research 与长链科学研究任务。 | [THUDM/LiveDRBench](https://github.com/THUDM/LiveDRBench) |
| NewtonBench | benchmark | scientific discovery / scientific reasoning 方向的 benchmark 入口。 | [HKUST-KnowComp/NewtonBench](https://github.com/HKUST-KnowComp/NewtonBench) |
| Aviary / LAB-Bench / BixBench | scientific benchmark | 适合科学任务、实验室场景、生物科学与 bench scientist 风格评测。 | [Future-House/aviary](https://github.com/Future-House/aviary)、[Future-House/LAB-Bench](https://github.com/Future-House/LAB-Bench)、[Future-House/BixBench](https://github.com/Future-House/BixBench) |

## 三、化学、材料与生命科学常见开源框架

### 1. Chemistry / Drug Discovery

| 资源 | 类型 | 更适合的用途 | 链接 |
| --- | --- | --- | --- |
| DeepChem | 科学机器学习框架 | 化学、药物发现、分子建模和 scientific ML 的高频入口。 | [deepchem/deepchem](https://github.com/deepchem/deepchem) |
| RDKit | 化学信息学工具箱 | 分子表示、分子特征、反应和化学数据处理的核心底座。 | [rdkit/rdkit](https://github.com/rdkit/rdkit) |
| Chemprop | 分子性质预测框架 | 适合分子性质预测、QSAR/QSPR 与 message passing 基线。 | [chemprop/chemprop](https://github.com/chemprop/chemprop) |
| TorchDrug | 药物发现与几何学习框架 | 适合 drug discovery、protein / molecule representation 与图学习。 | [DeepGraphLearning/torchdrug](https://github.com/DeepGraphLearning/torchdrug) |
| TDC | Therapeutics Data Commons | 药物发现、治疗科学与生物医药 benchmark 入口。 | [TDC](https://tdcommons.ai/)、[mims-harvard/TDC](https://github.com/mims-harvard/TDC) |

### 2. Materials Science

| 资源 | 类型 | 更适合的用途 | 链接 |
| --- | --- | --- | --- |
| pymatgen | 材料分析库 | 材料数据结构、特征、结构与模拟前处理的核心库。 | [materialsproject/pymatgen](https://github.com/materialsproject/pymatgen) |
| matminer | 材料特征工程 | 适合材料特征构建、benchmark 和结构化学习。 | [hackingmaterials/matminer](https://github.com/hackingmaterials/matminer) |
| Matbench | 材料 benchmark | 材料机器学习 benchmark 的标准入口。 | [Matbench](https://matbench.materialsproject.org/)、[materialsproject/matbench](https://github.com/materialsproject/matbench) |
| FAIR-Chem | 材料与催化科学 ML | 适合原子级表示、材料生成和催化任务。 | [FAIR-Chem/fairchem](https://github.com/FAIR-Chem/fairchem) |
| ASE | 原子模拟环境 | 原子结构、计算材料与模拟 workflow 的常用底座。 | [ASE](https://wiki.fysik.dtu.dk/ase/)、[ase/ase](https://github.com/ase/ase) |
| atomate2 / FireWorks | 材料 workflow 系统 | 适合大规模材料计算、任务编排与工作流自动化。 | [materialsproject/atomate2](https://github.com/materialsproject/atomate2)、[materialsproject/fireworks](https://github.com/materialsproject/fireworks) |

### 3. Biology / Single-cell / Domain ML

| 资源 | 类型 | 更适合的用途 | 链接 |
| --- | --- | --- | --- |
| Scanpy | single-cell 分析 | 单细胞数据预处理、可视化和分析的高频入口。 | [scverse/scanpy](https://github.com/scverse/scanpy) |
| scvi-tools | 深度生成模型工具 | 适合 single-cell 和 probabilistic modeling。 | [scverse/scvi-tools](https://github.com/scverse/scvi-tools) |

## 四、推荐组合

1. `Paper Search MCP + OpenAlex MCP + AI Co-Scientist + Robin`
   适合把 literature review、idea generation 和 scientific planning 串成一条链。
2. `DeepChem + RDKit + TDC + LAB-Bench / ScienceAgentBench`
   适合化学、生物医药与 drug discovery 方向。
3. `pymatgen + matminer + Matbench + FAIR-Chem + atomate2`
   适合材料科学与计算材料方向。
4. `MLE-bench + MLGym + ResearcherBench + NewtonBench`
   适合系统比较 AI scientist / research agent / scientific discovery agent。

## 五、如果这页的 Skills / MCP 还不够

- Skills：优先回看 [91-Skills/科学计算与领域Skills](../91-Skills/科学计算与领域Skills.md)、[91-Skills/Skill发现平台与精品合集](../91-Skills/Skill发现平台与精品合集.md)。
- MCP：优先回看 [92-MCP/生物医药与专利MCP](../92-MCP/生物医药与专利MCP.md)、[92-MCP/实验执行与数据工程MCP](../92-MCP/实验执行与数据工程MCP.md)、[92-MCP/MCP标准与发现平台](../92-MCP/MCP标准与发现平台.md)。

## 六、外部整合入口

| 资源 | 类型 | 更适合的用途 | 链接 |
| --- | --- | --- | --- |
| Awesome-LLM-Scientific-Discovery | 外部合集 | scientific discovery、scientific reasoning、benchmark 和系统综述入口。 | [HKUST-KnowComp/Awesome-LLM-Scientific-Discovery](https://github.com/HKUST-KnowComp/Awesome-LLM-Scientific-Discovery) |
| Awesome-AI-Scientist-Papers | 外部合集 | AI scientist、scientific discovery agents 和 benchmark 入口。 | [openags/Awesome-AI-Scientist-Papers](https://github.com/openags/Awesome-AI-Scientist-Papers) |
| AI-4-Research | 外部合集 | research workflow、scientific reasoning 和 benchmark 资料入口。 | [AI-4-Research/AI-4-Research.github.io](https://github.com/AI-4-Research/AI-4-Research.github.io) |

## 七、仓库内延伸阅读

- [AI-ML-DataMining资源](./AI-ML-DataMining资源.md)
- [科研新颖性与Idea生成](./科研新颖性与Idea生成.md)
- [05-实验执行、复现与评测](../05-实验执行、复现与评测/README.md)
