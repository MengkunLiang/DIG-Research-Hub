# 通用 Agent 框架

这一页收的是“不是专门为科研而生，但很适合搭科研智能体”的开源框架。它们更像底座，而不是现成科研系统。

## 1. 主流通用框架

| 资源 | 定位 | 简述 | 链接 |
| --- | --- | --- | --- |
| LangGraph | 工作流编排 | 很适合做状态机、长流程、多阶段回退与人工 gate。 | [langchain-ai/langgraph](https://github.com/langchain-ai/langgraph) |
| AutoGen | 多 Agent 协作 | 微软系的经典多 Agent 框架，适合快速搭角色化协作流程。 | [microsoft/autogen](https://github.com/microsoft/autogen) |
| smolagents | 轻量 Agent | Hugging Face 的轻量框架，上手快，适合做实验原型。 | [huggingface/smolagents](https://github.com/huggingface/smolagents) |
| CrewAI | 角色协作框架 | 很适合快速搭“Scout / Reader / Writer / Reviewer”这类角色分工。 | [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) |
| PydanticAI | 结构化 Agent | 对结构化输出、类型约束、工具调用管理比较友好。 | [pydantic/pydantic-ai](https://github.com/pydantic/pydantic-ai) |
| DSPy | 程序化提示与优化 | 更适合做程序化 prompt、模块化优化和可评估链路。 | [stanfordnlp/dspy](https://github.com/stanfordnlp/dspy) |

## 2. 跟科研特别契合的点

| 框架 | 更适合的科研场景 |
| --- | --- |
| LangGraph | 有明确状态机和多阶段产物的系统，例如 `AutoLab`。 |
| AutoGen | 想快速验证多角色协作，例如 `Scout + Reader + Reviewer`。 |
| smolagents | 想做轻量实验、个人研究助手或课程 demo。 |
| CrewAI | 想快速做角色感强的“科研团队模拟”。 |
| PydanticAI | 强调 artifact、schema、结构化输出的科研工作流。 |
| DSPy | 需要做 prompt 程序化、自动搜索和性能优化的场景。 |

## 3. 其他值得关注的通用底座

| 资源 | 定位 | 链接 |
| --- | --- | --- |
| LlamaIndex | RAG / 数据工作流 | [run-llama/llama_index](https://github.com/run-llama/llama_index) |
| Haystack | 检索与问答编排 | [deepset-ai/haystack](https://github.com/deepset-ai/haystack) |
| CAMEL | 多 Agent 研究与协作 | [camel-ai/camel](https://github.com/camel-ai/camel) |
| LDP | Agent / 环境 / 优化器解耦 | [Future-House/ldp](https://github.com/Future-House/ldp) |

## 4. 给 ResearchOS 的选择建议

### 如果你更看重“严谨编排”

优先：

- `LangGraph`
- `PydanticAI`
- `DSPy`

### 如果你更看重“快速出原型”

优先：

- `AutoGen`
- `CrewAI`
- `smolagents`

### 如果你更看重“科研文献和知识工作流”

别把注意力全放在编排框架本身，应该同时配：

- `PaperQA2`
- `RTI`
- `OpenReview MCP`
- `OpenAlex MCP`

因为科研系统的瓶颈经常不在“有没有 Agent 框架”，而在“有没有可靠的学术数据与证据链”。
