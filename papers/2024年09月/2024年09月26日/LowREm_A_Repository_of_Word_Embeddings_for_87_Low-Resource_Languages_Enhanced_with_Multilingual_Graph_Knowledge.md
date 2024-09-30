# LowREm：一个专为 87 种低资源语言设计的词嵌入库，融合了多语言图知识，助力语言处理。

发布时间：2024年09月26日

`LLM应用` `低资源语言`

> LowREm: A Repository of Word Embeddings for 87 Low-Resource Languages Enhanced with Multilingual Graph Knowledge

# 摘要

> 虽然基于 LLM 的上下文嵌入适用于多种语言，但对低资源语言的支持却往往不足。由于数据稀缺和计算成本高昂，为这些语言训练 LLM 极具挑战。尤其对于资源极度匮乏的语言，静态词嵌入仍是一个可行的选择。然而，目前缺乏一个包含多种语言静态嵌入的综合资源库。为此，我们推出了 LowREm，一个涵盖 87 种低资源语言的静态嵌入集中库。此外，我们还创新性地提出了一种方法，通过融合多语言图知识来增强 GloVe 嵌入。实验证明，我们的增强嵌入在情感分析任务中优于 XLM-R 提取的上下文嵌入。所有代码和数据均已公开，访问地址为 https://huggingface.co/DFKI。

> Contextualized embeddings based on large language models (LLMs) are available for various languages, but their coverage is often limited for lower resourced languages. Training LLMs for such languages is often difficult due to insufficient data and high computational cost. Especially for very low resource languages, static word embeddings thus still offer a viable alternative. There is, however, a notable lack of comprehensive repositories with such embeddings for diverse languages. To address this, we present LowREm, a centralized repository of static embeddings for 87 low-resource languages. We also propose a novel method to enhance GloVe-based embeddings by integrating multilingual graph knowledge, utilizing another source of knowledge. We demonstrate the superior performance of our enhanced embeddings as compared to contextualized embeddings extracted from XLM-R on sentiment analysis. Our code and data are publicly available under https://huggingface.co/DFKI.

[Arxiv](https://arxiv.org/abs/2409.18193)