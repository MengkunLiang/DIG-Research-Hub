# 写作协作与投稿 MCP

这一页聚焦“写作协作、引用回查、review 语境、LaTeX / Markdown 转换和投稿末端”这一层 MCP。

## 1. 协作写作与文稿工程

| 资源 | 场景 | 简述 | 链接 |
| --- | --- | --- | --- |
| OverleafMCP | Overleaf 项目协作 | 适合把 Overleaf 项目接入 agent 工作流。 | [mjyoo2/OverleafMCP](https://github.com/mjyoo2/OverleafMCP) |
| LaTeX MCP Server | LaTeX 工作流 | 适合围绕 LaTeX 工程做社区化实验接入。 | [Yeok-c/latex-mcp-server](https://github.com/Yeok-c/latex-mcp-server) |
| markdown2pdf-mcp | Markdown to PDF | 适合把 rebuttal、response 或 supplement 快速转成 PDF。 | [tigranbs/markdown2pdf-mcp](https://github.com/tigranbs/markdown2pdf-mcp) |
| GitHub MCP Server | 仓库与版本管理 | 适合查看文稿仓库、supplementary、release 和 revision 历史。 | [github/github-mcp-server](https://github.com/github/github-mcp-server) |
| GitMCP | 模板与指南读取 | 适合抓模板仓库、README 和 author guide。 | [idosal/git-mcp](https://github.com/idosal/git-mcp) |

## 2. 引用、文献库与附件预处理

| 资源 | 场景 | 简述 | 链接 |
| --- | --- | --- | --- |
| Zotero MCP | 文献库管理 | 适合条目、BibTeX、PDF、笔记与 group library 访问。 | [54yyyu/zotero-mcp](https://github.com/54yyyu/zotero-mcp) |
| Zotero MCP Server | 本地文库 API | 适合本地 Zotero API 访问与库内回查。 | [masaki39/zotero-mcp](https://github.com/masaki39/zotero-mcp) |
| MarkItDown | 附件预处理 | 适合把 PDF、Word、Excel、PPT 等附件转成 Markdown。 | [microsoft/markitdown](https://github.com/microsoft/markitdown) |
| Notion MCP Server | 写作与项目笔记 | 适合把 outline、meeting notes 和 revision plan 放进统一工作流。 | [makenotion/notion-mcp-server](https://github.com/makenotion/notion-mcp-server) |

## 3. review、投稿与公开讨论语境

| 资源 | 场景 | 简述 | 链接 |
| --- | --- | --- | --- |
| OpenReview MCP | 投稿与评审生态 | 适合跟踪公开评论、author response 和 review 风格。 | [openreview/openreview-mcp](https://github.com/openreview/openreview-mcp) |
| Paper Search MCP | 相关工作补检 | 适合针对 reviewer concern 补论文与相关工作。 | [openags/paper-search-mcp](https://github.com/openags/paper-search-mcp) |
| OpenAlex MCP | landscape 与引用网络 | 适合补作者、机构、主题和引文图谱。 | [hbiaou/openalex-mcp](https://github.com/hbiaou/openalex-mcp) |
| Crossref MCP | DOI 与正式出版元数据 | 适合核对引用、DOI 和正式出版状态。 | [botanicastudios/crossref-mcp](https://github.com/botanicastudios/crossref-mcp) |

## 4. 适合写作与投稿链路保留的组合方式

| 组合 | 适用链路 | 说明 |
| --- | --- | --- |
| `overleaf + zotero + github` | 论文协作与 revision | 适合把写作、引用和版本控制放在同一链路。 |
| `openreview + paper-search + openalex` | rebuttal 与 related work 补检 | 适合围绕 reviewer concern 做补查与 response。 |
| `markitdown + notion + zotero` | response 资料整理 | 适合把评审意见、附件和条目整理成 response 草案。 |
| `markdown2pdf + github + overleaf` | response / supplement 交付 | 适合在 Markdown、PDF 和 LaTeX 之间快速转换。 |

## 5. 选择这类 MCP 时的注意点

1. 涉及 Overleaf、Zotero 和 Notion 的 MCP，优先使用最小权限配置。
2. 对 Markdown / PDF / LaTeX 转换类 MCP，需要额外关注公式、表格和引用的一致性。
3. 对 OpenReview 类 MCP，适合用于公开讨论与评审语境，不应替代正式投稿系统本身。
