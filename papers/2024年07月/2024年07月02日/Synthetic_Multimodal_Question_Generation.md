# 多模态问题生成的合成技术

发布时间：2024年07月02日

`RAG`

> Synthetic Multimodal Question Generation

# 摘要

> 多模态检索增强生成（MMRAG）在多模态文档问答领域表现卓越，但评估其性能时面临高质量数据集的稀缺问题。为此，我们设计了SMMQG合成数据生成框架，该框架巧妙结合检索器、大型语言模型（LLM）和大型多模态模型（LMM），直接从多模态文档中生成符合特定风格和模态的问题与答案。我们利用SMMQG构建了一个包含1024个问题的MMRAG数据集，覆盖维基百科文档，并据此评估前沿模型，揭示了仅凭风格和模态特定数据才能洞察的模型性能。进一步地，我们通过人类研究验证了SMMQG生成数据的质量，结果显示其与MMQA众包基准不相上下，且下游评估结果高度吻合。

> Multimodal Retrieval Augmented Generation (MMRAG) is a powerful approach to question-answering over multimodal documents. A key challenge with evaluating MMRAG is the paucity of high-quality datasets matching the question styles and modalities of interest. In light of this, we propose SMMQG, a synthetic data generation framework. SMMQG leverages interplay between a retriever, large language model (LLM) and large multimodal model (LMM) to generate question and answer pairs directly from multimodal documents, with the questions conforming to specified styles and modalities. We use SMMQG to generate an MMRAG dataset of 1024 questions over Wikipedia documents and evaluate state-of-the-art models using it, revealing insights into model performance that are attainable only through style- and modality-specific evaluation data. Next, we measure the quality of data produced by SMMQG via a human study. We find that the quality of our synthetic data is on par with the quality of the crowdsourced benchmark MMQA and that downstream evaluation results using both datasets strongly concur.

[Arxiv](https://arxiv.org/abs/2407.02233)