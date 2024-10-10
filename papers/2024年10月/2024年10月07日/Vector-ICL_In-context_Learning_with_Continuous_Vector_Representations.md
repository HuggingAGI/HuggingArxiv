# Vector-ICL：基于连续向量表示的上下文学习

发布时间：2024年10月07日

`LLM应用` `人工智能` `数据科学`

> Vector-ICL: In-context Learning with Continuous Vector Representations

# 摘要

> 大型语言模型（LLM）在文本数据上的 in-context learning（ICL）能力令人瞩目。我们探索这些能力是否能扩展到来自不同领域的连续向量，这些向量由黑箱预训练编码器生成。通过轻量级投影器将输入数据与 LLM 的嵌入空间对齐，我们发现 LLM 能有效处理和学习这些投影向量，我们称之为 Vector-ICL。特别是，通用语言建模目标预训练的投影器能实现 Vector-ICL，而任务特定微调进一步提升了性能。在跨文本重建、数值函数回归、文本分类、摘要、分子描述、时间序列分类、图分类和 fMRI 解码等多任务和模态的实验中，Vector-ICL 通常超越了 few-shot ICL 和特定领域模型或微调。进一步的分析和案例研究显示，LLM 处理向量表示的潜力超越了传统基于标记的范式。

> Large language models (LLMs) have shown remarkable in-context learning (ICL) capabilities on textual data. We explore whether these capabilities can be extended to continuous vectors from diverse domains, obtained from black-box pretrained encoders. By aligning input data with an LLM's embedding space through lightweight projectors, we observe that LLMs can effectively process and learn from these projected vectors, which we term Vector-ICL. In particular, we find that pretraining projectors with general language modeling objectives enables Vector-ICL, while task-specific finetuning further enhances performance. In our experiments across various tasks and modalities, including text reconstruction, numerical function regression, text classification, summarization, molecule captioning, time-series classification, graph classification, and fMRI decoding, Vector-ICL often surpasses both few-shot ICL and domain-specific model or tuning. We further conduct analyses and case studies, indicating the potential of LLMs to process vector representations beyond traditional token-based paradigms.

[Arxiv](https://arxiv.org/abs/2410.05629)