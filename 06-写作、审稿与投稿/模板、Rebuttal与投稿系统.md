# 模板、Rebuttal与投稿系统

这一页专门补足 `06-写作、审稿与投稿` 的模板、response、submission system 和 preflight 检查层。重点不只是列模板，而是把“真正适合在投稿末端直接使用”的公开资源、官方入口和辅助工具集中起来。

## 一、官方模板与作者工具链

| 资源 | 类型 | 核心价值 | 链接 |
| --- | --- | --- | --- |
| ACM Primary Article Templates / acmart | 官方模板 | 适合 ACM 会议和期刊文稿，配合 TAPS 工作流使用。 | [ACM Primary Article Templates](https://www.acm.org/publications/proceedings-template)、[acmart on CTAN](https://ctan.org/pkg/acmart) |
| IEEE Author Center / Template Selector | 官方作者工具 | 集中提供 Word / LaTeX 模板、template selector、PDF checker、reference tools 等。 | [IEEE Author Center](https://ieeeauthorcenter.ieee.org/)、[Template Selector](https://template-selector.ieee.org/) |
| IEEEtran | 官方 LaTeX 类 | 适合 IEEE 期刊和会议文稿。 | [IEEEtran on CTAN](https://ctan.org/pkg/ieeetran) |
| ACL Style Files / ACLPUB / aclpubcheck | 官方模板与检查工具 | 适合 ACL 系列 venue 的 style、camera-ready 和预提交检查。 | [ACL Style Files](https://github.com/acl-org/acl-style-files)、[ACLPUB](https://github.com/acl-org/aclpub)、[aclpubcheck](https://github.com/acl-org/aclpubcheck) |
| ICML Author Instructions | 官方作者指南 | 集中给出 format、anonymization、style 和 author checklist 要求。 | [ICML Author Instructions](https://icml.cc/Conferences/2025/AuthorInstructions) |
| NeurIPS Call / FAQ / OpenReview | 官方作者指南 | style files、FAQ、submission 和 author response 都围绕官方页面和 OpenReview 流程展开。 | [NeurIPS Call for Papers](https://neurips.cc/Conferences/2025/CallForPapers)、[NeurIPS FAQs](https://neurips.cc/Conferences/2025/PaperInformation/Faq) |
| CVPR / ICCV Author Guidelines | 官方指南 | 适合计算机视觉类 venue 的 format、supplementary 和 camera-ready 规范。 | [CVPR Author Guidelines](https://cvpr.thecvf.com/Conferences/2025/AuthorGuidelines)、[ICCV Author Guidelines](https://iccv.thecvf.com/Conferences/2025/AuthorGuidelines) |
| Springer Nature Template | 官方模板入口 | 适合期刊与图书章节 LaTeX/Word 写作。 | [Springer Nature Overleaf Templates](https://www.overleaf.com/latex/templates/tagged/springer) |
| Elsevier elsarticle | 官方 LaTeX 模板 | 适合 Elsevier 期刊写作与转换。 | [elsarticle on CTAN](https://ctan.org/pkg/elsarticle) |
| JOSS paper.md / Whedon | software paper 流程 | 适合软件论文、GitHub 驱动 review 和 paper.md 样式投稿。 | [JOSS Paper Format](https://joss.readthedocs.io/en/latest/paper.html)、[openjournals/whedon](https://github.com/openjournals/whedon) |

## 二、模板生态、文稿工程与格式转换

| 资源 | 类型 | 核心价值 | 链接 |
| --- | --- | --- | --- |
| Overleaf Template Gallery | 官方模板库 | 适合快速找会议、期刊和出版社模板。 | [Overleaf Templates](https://www.overleaf.com/latex/templates) |
| Auto-Resubmit | 模板迁移工具 | 适合在 ACL、EMNLP、NeurIPS、ICML、ICLR、CVPR 等模板间迁移。 | [LilanOvO/Auto-Resubmit](https://github.com/LilanOvO/Auto-Resubmit) |
| MyST Templates | 可编程模板生态 | 适合 preprint、journal、book、thesis 等模板化出版。 | [myst-templates](https://github.com/myst-templates) |
| rticles | journal article 模板集合 | 适合 R Markdown / Quarto 路线下快速切模板。 | [rstudio/rticles](https://github.com/rstudio/rticles) |
| Curvenote / Stencila | programmable publishing | 适合 notebook、markdown、semantics 和 multi-format publishing。 | [curvenote/curvenote](https://github.com/curvenote/curvenote)、[stencila/stencila](https://github.com/stencila/stencila) |
| Fidus Writer | 学术协作编辑器 | 适合 citations、公式、协作评论和 journal 工作流。 | [fiduswriter/fiduswriter](https://github.com/fiduswriter/fiduswriter) |
| Typst / Quarto / Pandoc | 结构化文稿工程 | 适合轻量排版、跨格式转换和多输出通路。 | [Typst](https://github.com/typst/typst)、[Quarto](https://quarto.org/)、[Pandoc](https://pandoc.org/) |
| Tectonic / latexmk | build 工具链 | 适合脚本化构建、CI 和自动编译。 | [tectonic-typesetting/tectonic](https://github.com/tectonic-typesetting/tectonic)、[latexmk](https://ctan.org/pkg/latexmk) |
| arxiv-latex-cleaner | 提交前清理 | 适合裁剪图片、移除无关文件并生成 arXiv / submission package。 | [google-research/arxiv-latex-cleaner](https://github.com/google-research/arxiv-latex-cleaner) |

## 三、Rebuttal、response letter 与投稿检查模板

| 资源 | 类型 | 核心价值 | 链接 |
| --- | --- | --- | --- |
| review-response-template | response template | 适合 point-by-point 回复 reviewer comments。 | [klb2/review-response-template](https://github.com/klb2/review-response-template) |
| Journal Response Letter Template | response letter 模板 | 适合期刊 revise-and-resubmit 场景。 | [shellywhen/Journal-Response-Letter-Template-Latex](https://github.com/shellywhen/Journal-Response-Letter-Template-Latex) |
| latex-response-reviewers | reviewers reply 模板 | 适合 LaTeX 路线下写 response to reviewers。 | [firefly-cpp/latex-response-reviewers](https://github.com/firefly-cpp/latex-response-reviewers) |
| CV rebuttal template | rebuttal 模板 | 适合计算机视觉类会议 rebuttal 初稿。 | [guanyingc/cv_rebuttal_template](https://github.com/guanyingc/cv_rebuttal_template) |
| submission_checklist | 投稿检查清单 | 适合把投稿末端步骤转成 checklist。 | [philippbayer/submission_checklist](https://github.com/philippbayer/submission_checklist) |
| Open Research reviewer response | response drafting 工具 | 适合快速形成 response draft 和 concerns mapping。 | [Open Research](https://www.open-research.info/) |
| AI Peer Review | critique / meta-review 工具 | 适合生成 meta-review、concerns table 和 response points。 | [poldrack/ai-peer-review](https://github.com/poldrack/ai-peer-review) |

## 四、投稿、评审与出版系统

| 资源 | 类型 | 核心价值 | 链接 |
| --- | --- | --- | --- |
| OpenReview | submission + open review 平台 | 适合会议投稿、审稿、author response 和公开讨论。 | [OpenReview](https://openreview.net/) |
| Microsoft CMT | conference management system | 常见于会议投稿、审稿和 meta-review 流程。 | [Microsoft CMT](https://cmt3.research.microsoft.com/) |
| Editorial Manager | manuscript submission system | 常见于期刊投稿、revision 和 editor communication。 | [Editorial Manager](https://www.editorialmanager.com/) |
| ScholarOne Manuscripts | manuscript submission system | 常见于期刊投稿、review 和 revision 流程。 | [ScholarOne Manuscripts](https://clarivate.com/products/scientific-and-academic-research/research-publishing/scholarone/) |
| Open Journal Systems | 开源投稿平台 | 适合期刊运营、投稿、同行评审和出版管理。 | [pkp/ojs](https://github.com/pkp/ojs) |
| arXiv Submit | preprint 提交平台 | 适合预印本上传、版本更新和 source package 提交。 | [arXiv Submit](https://arxiv.org/submit) |
| JOSS / Whedon | open review publication | 适合软件论文和 GitHub 驱动 review。 | [Journal of Open Source Software](https://joss.theoj.org/)、[openjournals/whedon](https://github.com/openjournals/whedon) |

## 五、venue / journal 选择与 preflight 支持

| 资源 | 类型 | 核心价值 | 链接 |
| --- | --- | --- | --- |
| Springer Journal Suggester | journal recommendation | 适合根据标题、摘要和主题找期刊。 | [Springer Journal Suggester](https://journalsuggester.springer.com/) |
| Elsevier JournalFinder | journal recommendation | 适合按 title / abstract 寻找 Elsevier 期刊。 | [Elsevier JournalFinder](https://journalfinder.elsevier.com/) |
| Wiley Journal Finder | journal recommendation | 适合按摘要和主题匹配 Wiley 期刊。 | [Wiley Journal Finder](https://journalfinder.wiley.com/search?type=match) |
| IEEE Publication Recommender | venue recommendation | 适合在 IEEE 出版体系内找更匹配的 venue。 | [IEEE Publication Recommender](https://publication-recommender.ieee.org/home) |
| IEEE PDF Checker / Reference Preparation Assistant | preflight 工具 | 适合 PDF 合规检查和参考文献格式准备。 | [IEEE PDF Checker](https://ieee-pdf-express.org/)、[Reference Preparation Assistant](https://ieeeauthorcenter.ieee.org/create-your-ieee-article/use-authoring-tools-and-ieee-article-templates/reference-preparation-assistant/) |
| aclpubcheck | venue-specific preflight | 适合 ACL 系列 venue 的格式和提交前检查。 | [aclpubcheck](https://github.com/acl-org/aclpubcheck) |

## 六、几条常用路线

1. 会议论文路线：
   `OpenDraft / ScholarCopilot -> official template -> OpenReview / CMT -> response template -> camera-ready checker`
2. 期刊 revise-and-resubmit 路线：
   `PaperQA2 / citation-management -> Journal Response Letter Template -> Editorial Manager / ScholarOne`
3. software paper 路线：
   `paper.md -> JOSS / Whedon -> GitHub-based review`
4. preprint 路线：
   `Quarto / Typst / LaTeX -> arxiv-latex-cleaner -> arXiv Submit`
