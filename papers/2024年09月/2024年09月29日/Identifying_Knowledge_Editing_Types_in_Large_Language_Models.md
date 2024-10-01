# 探索大规模语言模型中的知识编辑类型

发布时间：2024年09月29日

`LLM应用` `网络安全` `人工智能`

> Identifying Knowledge Editing Types in Large Language Models

# 摘要

> 知识编辑已成为更新大型语言模型（LLM）知识的高效方法，备受研究关注。然而，防止其恶意滥用的有效措施尚缺，可能导致LLM生成有害内容，误导用户。为此，我们提出了\textbf{K}nowledge \textbf{E}diting \textbf{T}ype \textbf{I}dentification（KETI）任务，旨在识别LLM中的恶意编辑。我们创建了KETIBench基准，包含五种恶意更新和一种良性更新，并开发了四个经典分类模型和三个基于BERT的模型作为基线标识符。实验结果显示，所有基线标识符均表现良好，证明了识别恶意编辑的可行性。此外，标识符性能与编辑方法无关，且具有跨域泛化能力，可识别未知来源的编辑。所有数据和代码已公开，详见https://github.com/xpq-tech/KETI。注意：本文包含有毒文本示例。

> Knowledge editing has emerged as an efficient approach for updating the knowledge of large language models (LLMs), attracting increasing attention in recent research. However, there is a notable lack of effective measures to prevent the malicious misuse of this technology, which could lead to harmful edits in LLMs. These malicious modifications have the potential to cause LLMs to generate toxic content, misleading users into inappropriate actions. To address this issue, we introduce a novel task, \textbf{K}nowledge \textbf{E}diting \textbf{T}ype \textbf{I}dentification (KETI), aimed at identifying malicious edits in LLMs. As part of this task, we present KETIBench, a benchmark that includes five types of malicious updates and one type of benign update. Furthermore, we develop four classical classification models and three BERT-based models as baseline identifiers for both open-source and closed-source LLMs. Our experimental results, spanning 42 trials involving two models and three knowledge editing methods, demonstrate that all seven baseline identifiers achieve decent identification performance, highlighting the feasibility of identifying malicious edits in LLMs. Additional analyses reveal that the performance of the identifiers is independent of the efficacy of the knowledge editing methods and exhibits cross-domain generalization, enabling the identification of edits from unknown sources. All data and code are available in https://github.com/xpq-tech/KETI. Warning: This paper contains examples of toxic text.

[Arxiv](https://arxiv.org/abs/2409.19663)