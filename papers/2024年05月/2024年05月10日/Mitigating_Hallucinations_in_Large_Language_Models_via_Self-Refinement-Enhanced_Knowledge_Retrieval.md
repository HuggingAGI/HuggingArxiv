# 借助自精细化知识检索，大型语言模型幻觉得以缓解

发布时间：2024年05月10日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在医疗领域的应用，特别是在减少幻觉和提高回答的事实性方面的挑战。它提出了一种名为自我精炼增强的知识图谱检索（Re-KGR）的方法，旨在通过识别和减少高幻觉潜力令牌的验证轮次，以及通过后处理阶段的知识检索来纠正不准确内容，从而提高LLMs在医疗领域回答的事实性。这种方法的目的是在减少检索工作量的同时提升LLMs的性能。因此，这篇论文属于LLM应用分类，因为它关注的是LLMs在特定领域（医疗）的应用和改进。` `知识图谱`

> Mitigating Hallucinations in Large Language Models via Self-Refinement-Enhanced Knowledge Retrieval

# 摘要

> 大型语言模型（LLMs）在多个领域展现了卓越能力，但易产生幻觉，这在医疗等关键领域应用中构成挑战。本研究提出自我精炼增强的知识图谱检索（Re-KGR），旨在减少医疗领域检索工作量的同时提升LLMs回答的事实性。我们利用下一令牌预测概率分布的属性，识别并减少高幻觉潜力令牌的验证轮次，并通过后处理阶段的知识检索来纠正不准确内容，提高回答的真实性。实验证明，我们的方法在真实性方面得分最高，有效提升了LLMs的事实能力。

> Large language models (LLMs) have demonstrated remarkable capabilities across various domains, although their susceptibility to hallucination poses significant challenges for their deployment in critical areas such as healthcare. To address this issue, retrieving relevant facts from knowledge graphs (KGs) is considered a promising method. Existing KG-augmented approaches tend to be resource-intensive, requiring multiple rounds of retrieval and verification for each factoid, which impedes their application in real-world scenarios.
  In this study, we propose Self-Refinement-Enhanced Knowledge Graph Retrieval (Re-KGR) to augment the factuality of LLMs' responses with less retrieval efforts in the medical field. Our approach leverages the attribution of next-token predictive probability distributions across different tokens, and various model layers to primarily identify tokens with a high potential for hallucination, reducing verification rounds by refining knowledge triples associated with these tokens. Moreover, we rectify inaccurate content using retrieved knowledge in the post-processing stage, which improves the truthfulness of generated responses. Experimental results on a medical dataset demonstrate that our approach can enhance the factual capability of LLMs across various foundational models as evidenced by the highest scores on truthfulness.

[Arxiv](https://arxiv.org/abs/2405.06545)