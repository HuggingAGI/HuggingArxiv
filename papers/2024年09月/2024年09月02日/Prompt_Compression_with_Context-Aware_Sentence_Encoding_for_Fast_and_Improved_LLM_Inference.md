# 通过上下文感知句子编码实现提示压缩，加速并提升 LLM 推理性能

发布时间：2024年09月02日

`LLM应用` `软件开发` `人工智能`

> Prompt Compression with Context-Aware Sentence Encoding for Fast and Improved LLM Inference

# 摘要

> 大型语言模型 (LLM) 的研究新潮流聚焦于压缩上下文长度，以降低计算成本并保留回答问题所需的关键信息。基于标记的移除方法虽显著，但高压缩比下易丢失语义，且计算效率受限。为此，我们创新提出上下文感知提示压缩 (CPC)，通过句子级压缩技术，利用新型上下文感知句子编码器为每个句子打分，精准识别与问题相关性。为训练此编码器，我们构建了包含问题、相关句与无关句的新数据集，通过对比学习强化上下文感知能力。实验表明，CPC 在提示压缩上大幅领先现有技术，推理速度提升高达 10.93 倍，尤其在短上下文约束下表现更佳。我们已公开代码与数据集，助力快速复现与深入研究：https://github.com/Workday/cpc。

> Large language models (LLMs) have triggered a new stream of research focusing on compressing the context length to reduce the computational cost while ensuring the retention of helpful information for LLMs to answer the given question. Token-based removal methods are one of the most prominent approaches in this direction, but risk losing the semantics of the context caused by intermediate token removal, especially under high compression ratios, while also facing challenges in computational efficiency. In this work, we propose context-aware prompt compression (CPC), a sentence-level prompt compression technique where its key innovation is a novel context-aware sentence encoder that provides a relevance score for each sentence for a given question. To train this encoder, we generate a new dataset consisting of questions, positives, and negative pairs where positives are sentences relevant to the question, while negatives are irrelevant context sentences. We train the encoder in a contrastive setup to learn context-aware sentence representations. Our method considerably outperforms prior works on prompt compression on benchmark datasets and is up to 10.93x faster at inference compared to the best token-level compression method. We also find better improvement for shorter length constraints in most benchmarks, showing the effectiveness of our proposed solution in the compression of relevant information in a shorter context. Finally, we release the code and the dataset for quick reproducibility and further development: https://github.com/Workday/cpc.

[Arxiv](https://arxiv.org/abs/2409.01227)