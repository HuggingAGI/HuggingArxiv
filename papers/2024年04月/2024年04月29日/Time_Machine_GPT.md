# 时光机器 GPT

发布时间：2024年04月29日

`分类：LLM理论` `时间序列预测`

> Time Machine GPT

# 摘要

> 大型语言模型（LLMs）多在内容广泛且忽略时间顺序的文本集合上进行训练，这种做法并未跟上语言演进的步伐。传统上，为了构建能够适应时间变化的语言模型，往往需要在特定时间段的数据上对静态模型进行额外的预训练。本文介绍了一种创新的方法：一系列在特定时间点的非预测性大型语言模型，称为时间机器 GPT（TiMaGPT）。这些模型被特别设计，以确保它们不会知晓任何关于未来的事实性信息和语言变迁。这一策略不仅有助于深入理解语言的演进，而且在动态情境下应用模型时至关重要，例如在时间序列预测中，对将来信息的预知可能会带来问题。我们为这些模型及其训练数据集提供了访问权限。

> Large language models (LLMs) are often trained on extensive, temporally indiscriminate text corpora, reflecting the lack of datasets with temporal metadata. This approach is not aligned with the evolving nature of language. Conventional methods for creating temporally adapted language models often depend on further pre-training static models on time-specific data. This paper presents a new approach: a series of point-in-time LLMs called Time Machine GPT (TiMaGPT), specifically designed to be nonprognosticative. This ensures they remain uninformed about future factual information and linguistic changes. This strategy is beneficial for understanding language evolution and is of critical importance when applying models in dynamic contexts, such as time-series forecasting, where foresight of future information can prove problematic. We provide access to both the models and training datasets.

[Arxiv](https://arxiv.org/abs/2404.18543)