# 挖掘 LLMs 语法知识，优化可接受性判断

发布时间：2024年08月18日

`LLM应用` `语言处理`

> How to Make the Most of LLMs' Grammatical Knowledge for Acceptability Judgments

# 摘要

> 语言模型的语法能力常通过最小对测试来评估，但现有方法仅简单对比句子概率。大型语言模型（LLMs）在此领域的潜力尚未充分挖掘。我们探索如何全面利用LLMs的语法知识。实验涵盖九种中英判断方法，发现“模板内LP”和“是/否概率计算”方法表现卓越，超越传统手段。这些方法各具特色，如“是/否概率计算”能抵御长度偏差。因此，我们提倡采用多元判断方法，以全面评估LLMs的语法实力。

> The grammatical knowledge of language models (LMs) is often measured using a benchmark of linguistic minimal pairs, where LMs are presented with a pair of acceptable and unacceptable sentences and required to judge which is acceptable. The existing dominant approach, however, naively calculates and compares the probabilities of paired sentences using LMs. Additionally, large language models (LLMs) have yet to be thoroughly examined in this field. We thus investigate how to make the most of LLMs' grammatical knowledge to comprehensively evaluate it. Through extensive experiments of nine judgment methods in English and Chinese, we demonstrate that a probability readout method, in-template LP, and a prompting-based method, Yes/No probability computing, achieve particularly high performance, surpassing the conventional approach. Our analysis reveals their different strengths, e.g., Yes/No probability computing is robust against token-length bias, suggesting that they harness different aspects of LLMs' grammatical knowledge. Consequently, we recommend using diverse judgment methods to evaluate LLMs comprehensively.

[Arxiv](https://arxiv.org/abs/2408.09639)