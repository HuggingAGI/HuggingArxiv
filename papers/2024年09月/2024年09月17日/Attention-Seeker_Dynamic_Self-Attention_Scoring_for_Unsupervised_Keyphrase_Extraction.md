# Attention-Seeker：动态自注意力评分，助力无监督关键词提取

发布时间：2024年09月17日

`LLM应用` `文本分析`

> Attention-Seeker: Dynamic Self-Attention Scoring for Unsupervised Keyphrase Extraction

# 摘要

> 本文介绍的 Attention-Seeker 是一种无监督关键词提取方法，通过利用大型语言模型的自注意力图来评估候选短语的重要性。该方法能够自动识别模型对文本关键主题关注的层、头和注意力向量，并据此评分候选短语。与传统需要手动调参的模型不同，Attention-Seeker 能自动适应输入文本，极大提升了实用性。在 Inspec、SemEval2010、SemEval2017 和 Krapivin 四个公开数据集上的测试显示，即使不进行参数调整，Attention-Seeker 也超越了多数基线模型，在三个数据集上达到最先进水平，尤其擅长从长文档中提取关键词。

> This paper proposes Attention-Seeker, an unsupervised keyphrase extraction method that leverages self-attention maps from a Large Language Model to estimate the importance of candidate phrases. Our approach identifies specific components - such as layers, heads, and attention vectors - where the model pays significant attention to the key topics of the text. The attention weights provided by these components are then used to score the candidate phrases. Unlike previous models that require manual tuning of parameters (e.g., selection of heads, prompts, hyperparameters), Attention-Seeker dynamically adapts to the input text without any manual adjustments, enhancing its practical applicability. We evaluate Attention-Seeker on four publicly available datasets: Inspec, SemEval2010, SemEval2017, and Krapivin. Our results demonstrate that, even without parameter tuning, Attention-Seeker outperforms most baseline models, achieving state-of-the-art performance on three out of four datasets, particularly excelling in extracting keyphrases from long documents.

[Arxiv](https://arxiv.org/abs/2409.10907)