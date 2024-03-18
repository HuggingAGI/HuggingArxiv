# [WebCiteS 是一种创新技术，专注于对中文网页搜索结果进行带引文的查询焦点摘要。该技术旨在通过考虑引用信息，提升搜索结果摘要的质量和针对性。]

发布时间：2024年03月04日

`LLM应用`

> WebCiteS: Attributed Query-Focused Summarization on Chinese Web Search Results with Citations

> 提升LLMs的溯源能力意义重大，为此，我们探索了一种有效途径——让LLMs能引用支撑其生成内容的外部资料。尽管已有相关数据集和评估方法，但在这一领域仍存在明显局限。本文中，我们定义了“带归属查询焦点摘要”任务，并引入了名为WebCiteS的中文数据集，内含7000篇人工标注并附带引用的摘要，这些摘要源自真实用户的查询和网络搜索结果，对于模型训练与评估具有重要价值。然而，以往的归属评估工作未明确区分事实依据错误和引用错误，且在自动化验证部分依赖多来源信息的句子时力有不逮。为了解决这些问题，我们精心设计了详尽的评估指标，并使自动评估工具具备将句子拆解为子论点以实现精确验证的能力。通过对开源及专有模型在WebCiteS上的全面评测，我们揭示了LLMs在正确引用出处方面的艰巨挑战，从而强调了持续改进的重要性。为了推动该关键领域深入研究，我们将公开发布此数据集及配套代码。

> Enhancing the attribution in large language models (LLMs) is a crucial task. One feasible approach is to enable LLMs to cite external sources that support their generations. However, existing datasets and evaluation methods in this domain still exhibit notable limitations. In this work, we formulate the task of attributed query-focused summarization (AQFS) and present WebCiteS, a Chinese dataset featuring 7k human-annotated summaries with citations. WebCiteS derives from real-world user queries and web search results, offering a valuable resource for model training and evaluation. Prior works in attribution evaluation do not differentiate between groundedness errors and citation errors. They also fall short in automatically verifying sentences that draw partial support from multiple sources. We tackle these issues by developing detailed metrics and enabling the automatic evaluator to decompose the sentences into sub-claims for fine-grained verification. Our comprehensive evaluation of both open-source and proprietary models on WebCiteS highlights the challenge LLMs face in correctly citing sources, underscoring the necessity for further improvement. The dataset and code will be open-sourced to facilitate further research in this crucial field.

[Arxiv](https://arxiv.org/abs/2403.01774)