# 通过密集段落检索优化令牌控制

发布时间：2024年05月13日

`RAG

理由：这篇论文主要讨论了RAG（Retrieval-Augmented Generation）技术在LLMs（大型语言模型）中的应用，特别是在解决幻觉问题和改进信息检索方面的应用。论文中提到的DPR模型和控制令牌的引入，都是为了优化RAG技术在特定任务上的表现。因此，这篇论文更符合RAG分类，因为它专注于RAG技术的改进和应用。` `信息检索`

> Control Token with Dense Passage Retrieval

# 摘要

> 本研究针对LLMs中的幻觉问题，采用了一种名为RAG的技术，该技术通过在提示中嵌入相关信息来提供准确答案。但RAG在信息检索上存在局限。为此，我们引入了DPR模型，专门用于检索与用户查询相关的领域特定文档。尽管DPR有所改进，但其在文档检索上的准确性仍有欠缺。通过加入控制令牌，我们大幅提升了DPR模型的性能，使其在Top-1和Top-20的准确率上分别提升了13%和4%，远超标准DPR模型。

> This study addresses the hallucination problem in large language models (LLMs). We adopted Retrieval-Augmented Generation(RAG) (Lewis et al., 2020), a technique that involves embedding relevant information in the prompt to obtain accurate answers. However, RAG also faced inherent issues in retrieving correct information. To address this, we employed the Dense Passage Retrieval(DPR) (Karpukhin et al., 2020) model for fetching domain-specific documents related to user queries. Despite this, the DPR model still lacked accuracy in document retrieval. We enhanced the DPR model by incorporating control tokens, achieving significantly superior performance over the standard DPR model, with a 13% improvement in Top-1 accuracy and a 4% improvement in Top-20 accuracy.

[Arxiv](https://arxiv.org/abs/2405.13008)