# 我们提出了一种以知识为核心的基准框架，并进行了增强生成的实证研究。

发布时间：2024年09月02日

`RAG` `人工智能` `数据挖掘`

> A Knowledge-Centric Benchmarking Framework and Empirical Study for Retrieval-Augmented Generation

# 摘要

> RAG 通过整合检索机制，使生成模型能够访问和利用外部知识源，从而提升了性能。然而，在处理现实查询和减少幻觉方面，RAG 仍面临重大挑战。KDD Cup 2024 CRAG 竞赛通过引入网页和模拟 API 作为知识源，增加了 LLM 处理信息前的 HTML 解析复杂性，凸显了这些问题。本文提出了一种新的 RAG 基准，旨在应对这些挑战。我们全面评估了 RAG 过程，包括知识源选择、检索、组织和推理，并揭示了自动化知识源选择和噪声块对推理的影响。此外，我们还分析了超参数对 RAG 性能的影响。为推动研究，我们公开了实验结果、代码和 CRAG 数据集的解析版本\footnote{https://github.com/USTCAGI/RAG-X}，为 RAG 方法的发展和未来研究奠定了坚实基础。

> Retrieval-Augmented Generation (RAG) enhances generative models by integrating retrieval mechanisms, which allow these models to access and utilize external knowledge sources. Despite its advantages, RAG encounters significant challenges, particularly in effectively handling real-world queries and mitigating hallucinations. The KDD Cup 2024 CRAG competition brings these issues to the forefront by incorporating both web pages and a mock API as knowledge sources, adding the complexity of parsing HTML before large language models (LLMs) can process the information. In this paper, we propose a novel RAG benchmark designed to address these challenges. Our work provides a comprehensive set of experimental results, offering valuable insights for the study of RAG. We thoroughly examine the entire RAG process, including knowledge source selection, retrieval, organization, and reasoning. Key findings from our study include the impact of automated knowledge source selection using agents and the influence of noise chunks on RAG reasoning. Additionally, we conduct detailed experiments to analyze the effects of various hyperparameters on RAG performance. To support further research, we have made our results, the associated code, and a parsed version of the CRAG dataset publicly available\footnote{https://github.com/USTCAGI/RAG-X}, contributing to the advancement of RAG methodologies and establishing a solid foundation for future work in this domain.

[Arxiv](https://arxiv.org/abs/2409.13694)