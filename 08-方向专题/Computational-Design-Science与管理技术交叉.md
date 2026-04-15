# Computational Design Science 与管理技术交叉

这一页聚焦 `AI / analytics / data mining` 与 `management / IS / digital innovation / decision support` 的交叉研究。重点不是单一算法库，而是把开放学术与创新数据、机制识别工具、行为实验平台、设计科学原型和公共评测资源整合成可复用的研究路线。

## 这一步通常要回答的问题

1. 哪些开放学术、专利、政策、经济与平台数据最适合做管理技术交叉研究。
2. 哪些方法工具最适合支撑因果识别、机制解释、主题演化、网络扩散和设计科学原型。
3. 哪些 `Skills`、`MCP`、实验平台与 survey / behavior 工具最值得优先接入。
4. 对平台治理、数字创新、AI 辅助决策、开放科学与科研组织研究，如何快速拼出一条可执行 pipeline。

## 推荐先看

- [开放学术、创新与行为实验资源](./开放学术、创新与行为实验资源.md)
- [03-知识管理与证据沉淀](../03-知识管理与证据沉淀/README.md)
- [04-新颖性判断与综述](../04-新颖性判断与综述/README.md)
- [05-实验执行、复现与评测](../05-实验执行、复现与评测/README.md)

## 一、相关 Skills

| 资源 | 类型 | 更适合的用途 | 链接 |
| --- | --- | --- | --- |
| 科学计算与领域Skills | 仓库内附录 | 数据分析、网络分析、统计建模和领域数据库访问的 Skill 入口。 | [91-Skills/科学计算与领域Skills](../91-Skills/科学计算与领域Skills.md) |
| 科研写作与文献Skills | 仓库内附录 | 综述、review mining、研究叙事和证据回查入口。 | [91-Skills/科研写作与文献Skills](../91-Skills/科研写作与文献Skills.md) |
| Claude Scientific Skills / Scientific Agent Skills | 科学技能总库 | 更适合补数据库查询、统计分析、network analysis、research methodology 和 scientific writing。 | [K-Dense-AI/claude-scientific-skills](https://github.com/K-Dense-AI/claude-scientific-skills)、[K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) |
| AI Research SKILLs | 研究工程技能库 | 适合把分析脚本、数据预处理、实验工程和可视化接成统一研究流程。 | [Orchestra-Research/AI-Research-SKILLs](https://github.com/Orchestra-Research/AI-Research-SKILLs) |

## 二、相关 MCP

| 资源 | 类型 | 更适合的用途 | 链接 |
| --- | --- | --- | --- |
| 文献检索与知识库MCP | 仓库内附录 | OpenAlex、paper-search、OpenReview、Zotero 等文献与知识图谱入口。 | [92-MCP/文献检索与知识库MCP](../92-MCP/文献检索与知识库MCP.md) |
| 实验执行与数据工程MCP | 仓库内附录 | Jupyter、GitHub、DuckDB、Chart、Kaggle 等执行和分析层入口。 | [92-MCP/实验执行与数据工程MCP](../92-MCP/实验执行与数据工程MCP.md) |
| Paper Search MCP / OpenAlex MCP / OpenReview MCP | 学术与审稿 MCP | 适合追踪论文、审稿、作者、机构与主题网络。 | [openags/paper-search-mcp](https://github.com/openags/paper-search-mcp)、[hbiaou/openalex-mcp](https://github.com/hbiaou/openalex-mcp)、[openreview/openreview-mcp](https://github.com/openreview/openreview-mcp) |
| Zotero MCP / GitHub MCP / Jupyter MCP | 知识库与执行 MCP | 适合把文献库、代码、notebook 和实验脚本接成统一工作流。 | [54yyyu/zotero-mcp](https://github.com/54yyyu/zotero-mcp)、[github/github-mcp-server](https://github.com/github/github-mcp-server)、[datalayer/jupyter-mcp-server](https://github.com/datalayer/jupyter-mcp-server) |

## 三、开放数据与干预平台

| 资源层 | 更适合的用途 | 首选入口 |
| --- | --- | --- |
| 学术图谱与开放科学 | 研究主题演化、引用网络、作者/机构分析、开放科学项目追踪 | [开放学术、创新与行为实验资源](./开放学术、创新与行为实验资源.md) |
| 专利与创新数据 | 论文到专利、技术融合、创新扩散、知识重组 | [开放学术、创新与行为实验资源](./开放学术、创新与行为实验资源.md) |
| 经济、政策与社会技术数据 | 平台治理、数字经济、政策冲击、组织行为 | [开放学术、创新与行为实验资源](./开放学术、创新与行为实验资源.md) |
| 在线实验与设计科学原型 | 行为实验、A/B 测试、交互实验、干预设计 | [开放学术、创新与行为实验资源](./开放学术、创新与行为实验资源.md) |

## 四、机制识别与解释性方法

| 资源 | 类型 | 更适合的用途 | 链接 |
| --- | --- | --- | --- |
| DoWhy | 因果推断框架 | 把识别假设、估计与 refutation 写成可追溯研究流程。 | [py-why/dowhy](https://github.com/py-why/dowhy) |
| EconML | 异质性效应 | 研究不同组织、用户或平台情境下的 treatment heterogeneity。 | [py-why/EconML](https://github.com/py-why/EconML) |
| DoubleML | 双重机器学习 | 高维因果、政策评估与稳健估计的高频入口。 | [DoubleML/doubleml-for-py](https://github.com/DoubleML/doubleml-for-py) |
| causal-learn | 因果发现 | 探索变量结构和潜在机制图。 | [py-why/causal-learn](https://github.com/py-why/causal-learn) |
| statsmodels / linearmodels | 统计与面板建模 | DID、IV、固定效应、事件研究和面板回归的稳健入口。 | [statsmodels](https://www.statsmodels.org/)、[linearmodels](https://bashtage.github.io/linearmodels/) |
| PyMC | 贝叶斯建模 | 适合层级模型、多源先验和机制不确定场景。 | [PyMC](https://www.pymc.io/) |

## 五、文本、主题、网络与知识结构分析

| 资源 | 类型 | 更适合的用途 | 链接 |
| --- | --- | --- | --- |
| BERTopic | 主题建模 | 研究主题演化、专利主题聚类、评论主题归纳。 | [MaartenGr/BERTopic](https://github.com/MaartenGr/BERTopic) |
| Gensim | 文本挖掘 | topic modeling、词向量与经典语义空间分析。 | [piskvorky/gensim](https://github.com/piskvorky/gensim) |
| sentence-transformers | 表征学习 | semantic similarity、paper/patent matching、cluster analysis。 | [UKPLab/sentence-transformers](https://github.com/UKPLab/sentence-transformers) |
| NetworkX / igraph | 网络分析 | 引文网络、合作网络、扩散网络与创新网络分析。 | [networkx/networkx](https://github.com/networkx/networkx)、[igraph/python-igraph](https://github.com/igraph/python-igraph) |

## 六、三条高价值研究路线

1. `OpenAlex + Lens + USPTO Open Data + BERTopic + NetworkX + DoWhy`
   适合技术融合、知识重组、论文到专利的知识流动研究。
2. `平台日志 / 行为数据 + oTree / jsPsych + statsmodels + EconML`
   适合平台治理、AI 辅助决策、解释与排序对用户行为的影响研究。
3. `OpenReview + OpenAlex + OSF + NLPeer + linearmodels / PyMC`
   适合开放科学、科研组织行为、审稿机制和创新筛选研究。

## 七、外部整合入口

| 资源 | 类型 | 更适合的用途 | 链接 |
| --- | --- | --- | --- |
| awesome-scholarly-data-analysis | 外部合集 | 学术数据分析、计量与开放学术资源入口。 | [napsternxg/awesome-scholarly-data-analysis](https://github.com/napsternxg/awesome-scholarly-data-analysis) |
| AI-4-Research | 外部合集 | 研究自动化、开放科学与研究工作流资料入口。 | [AI-4-Research/AI-4-Research.github.io](https://github.com/AI-4-Research/AI-4-Research.github.io) |
| awesome-causal-inference | 外部合集 | 因果推断方法、课程、软件和论文入口。 | [matteocourthoud/awesome-causal-inference](https://github.com/matteocourthoud/awesome-causal-inference) |
| Local Citation Network | 外部工具与资料 | 引文网络分析和本地引文图谱入口。 | [LocalCitationNetwork](https://github.com/LocalCitationNetwork/LocalCitationNetwork.github.io) |

## 八、仓库内延伸阅读

- [科研新颖性与Idea生成](./科研新颖性与Idea生成.md)
- [开放学术、创新与行为实验资源](./开放学术、创新与行为实验资源.md)
- [07-安全与治理](../07-安全与治理/README.md)
