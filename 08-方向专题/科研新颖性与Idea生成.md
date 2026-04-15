# 科研新颖性与 Idea 生成

这一页聚焦“新颖性判断、idea 生成、peer-review 结构化分析”这一条线。方向重点不是停留在灵感收集，而是把 novelty retrieval、novelty judging、idea diversification、review mining 和 benchmark 串成可复用的研究流程。

## 这一步通常要回答的问题

1. 新颖性判断应当依赖哪些 benchmark、review 数据和文献图谱，而不是只靠主观感觉。
2. idea generation 与 reviewer-style critique 应当怎样形成闭环，而不是只生成单条想法。
3. 哪些 `Skills`、`MCP` 和公共数据层最适合支撑 novelty 审计与 review mining。
4. 哪些公开合集最适合继续补充这一方向的 benchmark 与开源系统。

## 推荐先看

- [04-新颖性判断与综述](../04-新颖性判断与综述/README.md)
- [91-Skills/科研写作与文献Skills](../91-Skills/科研写作与文献Skills.md)
- [92-MCP/文献检索与知识库MCP](../92-MCP/文献检索与知识库MCP.md)
- [AI4Science与Scientific Discovery](./AI4Science与Scientific%20Discovery.md)

## 一、相关 Skills

| 资源 | 类型 | 更适合的用途 | 链接 |
| --- | --- | --- | --- |
| 科研写作与文献Skills | 仓库内附录 | 当前仓库里综述、review、写作、citation 和 evidence-grounded output 的 Skill 入口。 | [91-Skills/科研写作与文献Skills](../91-Skills/科研写作与文献Skills.md) |
| Claude Scientific Writer | 写作与 review 工具包 | 覆盖 `research-lookup`、`peer-review`、`citation-management`、`venue-templates` 等子能力。 | [K-Dense-AI/claude-scientific-writer](https://github.com/K-Dense-AI/claude-scientific-writer) |
| academic-research-skills | 学术流程 Skill 集 | 适合 `academic-paper`、`academic-paper-reviewer`、`academic-pipeline` 等研究流程。 | [Imbad0202/academic-research-skills](https://github.com/Imbad0202/academic-research-skills) |
| Claude Scientific Skills / Scientific Agent Skills | 科学技能总库 | 适合补 hypothesis generation、scholar evaluation、文献分析和研究方法能力。 | [K-Dense-AI/claude-scientific-skills](https://github.com/K-Dense-AI/claude-scientific-skills)、[K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) |

## 二、相关 MCP 与公共数据层

| 资源 | 类型 | 更适合的用途 | 链接 |
| --- | --- | --- | --- |
| 文献检索与知识库MCP | 仓库内附录 | 当前仓库里 OpenAlex、paper-search、OpenReview、Semantic Scholar、Zotero 等入口。 | [92-MCP/文献检索与知识库MCP](../92-MCP/文献检索与知识库MCP.md) |
| Paper Search MCP | 多源学术检索 MCP | 适合统一接入 arXiv、PubMed、Semantic Scholar、Crossref、OpenAlex 等数据源。 | [openags/paper-search-mcp](https://github.com/openags/paper-search-mcp) |
| OpenAlex MCP / OpenReview MCP | 学术图谱与审稿 MCP | novelty 检索、作者/机构网络和 review mining 的关键入口。 | [hbiaou/openalex-mcp](https://github.com/hbiaou/openalex-mcp)、[openreview/openreview-mcp](https://github.com/openreview/openreview-mcp) |
| Semantic Scholar MCP / Crossref MCP | 元数据与引文网络 MCP | 适合补 citation、作者和 DOI 层面的核验。 | [zongmin-yu/semantic-scholar-fastmcp-mcp-server](https://github.com/zongmin-yu/semantic-scholar-fastmcp-mcp-server)、[botanicastudios/crossref-mcp](https://github.com/botanicastudios/crossref-mcp) |
| Zotero MCP / GitHub MCP | 文献库与代码 MCP | 适合把个人文献库、配套代码和 benchmark 仓库接进 novelty 流程。 | [54yyyu/zotero-mcp](https://github.com/54yyyu/zotero-mcp)、[github/github-mcp-server](https://github.com/github/github-mcp-server) |

## 三、novelty / idea 系统与 benchmark

| 资源 | 类型 | 更适合的用途 | 链接 |
| --- | --- | --- | --- |
| NovBench / llm4novelty | novelty benchmark | 围绕学术论文 novelty assessment 构建数据与代码，是这一方向最值得优先补齐的 benchmark 之一。 | [njust-winchy/llm4novelty](https://github.com/njust-winchy/llm4novelty) |
| AI Co-Scientist | 科研 idea 生成系统 | 把 ideation、reflection、ranking 和 evidence retrieval 串成闭环。 | [Google Research Blog](https://research.google/blog/accelerating-scientific-breakthroughs-with-an-ai-co-scientist/) |
| Can LLMs Generate Novel Research Ideas? | 人类对照研究 | 适合做“LLM 生成研究想法是否足够新”的基准参考。 | [OpenReview](https://openreview.net/forum?id=M23dTGWCZy) |
| HypoGeniC / hypothesis-generation | hypothesis generation | 强调从数据中提出可迁移假设并做 OOD 验证。 | [HypoGeniC Demo](https://chicagohai.github.io/hypogenic-demo/)、[ChicagoHAI/hypothesis-generation](https://github.com/ChicagoHAI/hypothesis-generation) |
| ResearchAgent / VirSci / Dolphin | 多 agent idea 系统 | 分别强调 idea + review、multi-agent debate 和 `Thinking -> Practice -> Feedback` 闭环。 | [ResearchAgent](https://aclanthology.org/2025.naacl-long.342/)、[VirSci](https://aclanthology.org/2025.acl-long.1368/)、[Dolphin](https://aclanthology.org/2025.acl-long.1056/) |
| AI Scientist / AI Scientist-v2 | 自动科研系统 | 从 idea 到实验、再到 review 的代表性端到端系统。 | [SakanaAI/AI-Scientist](https://github.com/SakanaAI/AI-Scientist)、[SakanaAI/AI-Scientist-v2](https://github.com/SakanaAI/AI-Scientist-v2) |
| SciAgents | scientific discovery agents | 利用知识图谱和多 agent 推进科学发现与 hypothesis generation。 | [lamm-mit/SciAgentsDiscovery](https://github.com/lamm-mit/SciAgentsDiscovery) |

## 四、review mining 与公开审稿数据

| 资源 | 类型 | 更适合的用途 | 链接 |
| --- | --- | --- | --- |
| ReviewAdvisor | scientific review 数据与方法 | 自动 scientific reviewing 的高价值早期资源。 | [neulab/ReviewAdvisor](https://github.com/neulab/ReviewAdvisor) |
| NLPeer | peer review 数据资源 | 多会议、多来源 peer review 统一数据层。 | [UKPLab/nlpeer](https://github.com/UKPLab/nlpeer) |
| PeerRead | peer review 数据集 | peer review 建模与历史对照的经典入口。 | [allenai/PeerRead](https://github.com/allenai/PeerRead) |
| PeerQA / PeerSum / HedgePeer | 审稿问答与元审数据 | 适合 reviewer question、meta-review 和 uncertainty 研究。 | [UKPLab/PeerQA](https://github.com/UKPLab/PeerQA)、[PeerSum](https://huggingface.co/datasets/oaimli/PeerSum)、[HedgePeer](https://github.com/Tirthankar-Ghosal/HedgePeer-Dataset) |
| AgentReview / MARG / ReviewRobot / AI Peer Review | LLM 审稿系统 | 适合做 automated reviewing、review dynamics 和 meta-review 生成。 | [ahren09/agentreview](https://github.com/ahren09/agentreview)、[allenai/marg-reviewer](https://github.com/allenai/marg-reviewer)、[EagleW/ReviewRobot](https://github.com/EagleW/ReviewRobot)、[poldrack/ai-peer-review](https://github.com/poldrack/ai-peer-review) |
| OpenReview / NLP for Peer Review | 平台与合集 | 继续扩展公开 review 数据、任务和 benchmark 的主要入口。 | [OpenReview](https://openreview.net/)、[OAfzal/nlp-for-peer-review](https://github.com/OAfzal/nlp-for-peer-review) |

## 五、外部整合入口

| 资源 | 类型 | 更适合的用途 | 链接 |
| --- | --- | --- | --- |
| Awesome-AI-Scientist-Papers | 外部合集 | AI scientist、scientific reasoning 与 benchmark 的系统入口。 | [openags/Awesome-AI-Scientist-Papers](https://github.com/openags/Awesome-AI-Scientist-Papers) |
| Awesome-LLM-Scientific-Discovery | 外部合集 | scientific discovery、idea generation 与 AI4Science 资料入口。 | [HKUST-KnowComp/Awesome-LLM-Scientific-Discovery](https://github.com/HKUST-KnowComp/Awesome-LLM-Scientific-Discovery) |
| NLP for Peer Review | 外部合集 | 继续扩充 peer review 数据集、任务和基线。 | [OAfzal/nlp-for-peer-review](https://github.com/OAfzal/nlp-for-peer-review) |
| AI-4-Research / SurveyX | 外部合集 | 研究自动化、survey、scientific reasoning 和系统资源入口。 | [AI-4-Research/AI-4-Research.github.io](https://github.com/AI-4-Research/AI-4-Research.github.io)、[IAAR-Shanghai/SurveyX](https://github.com/IAAR-Shanghai/SurveyX) |

## 六、推荐组合

1. `OpenReview MCP + OpenAlex MCP + Paper Search MCP + llm4novelty`
   适合做 novelty retrieval、相似论文回查与 novelty auditing。
2. `AI Co-Scientist + HypoGeniC + ResearchAgent / VirSci`
   适合做 idea generation、多路线排序和 reviewer-style critique。
3. `PeerRead / NLPeer / PeerQA / PeerSum + ReviewAdvisor / AI Peer Review`
   适合做 review mining、meta-review 生成和审稿风格 benchmark。
4. `PaperQA2 + Zotero MCP + citation-management + OpenReview`
   适合把 novelty claim、证据核验和审稿意见回到原始材料。

## 七、仓库内延伸阅读

- [04-新颖性判断与综述](../04-新颖性判断与综述/README.md)
- [06-写作、审稿与投稿](../06-写作、审稿与投稿/README.md)
- [AI4Science与Scientific Discovery](./AI4Science与Scientific%20Discovery.md)
