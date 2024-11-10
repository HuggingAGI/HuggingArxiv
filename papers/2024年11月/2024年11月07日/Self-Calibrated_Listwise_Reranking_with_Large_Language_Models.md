# 具有大型语言模型的自校准列表式重排序

发布时间：2024年11月07日

`LLM应用` `重排序`

> Self-Calibrated Listwise Reranking with Large Language Models

# 摘要

> 大型语言模型（LLMs）具有先进的语言能力，已通过序列到序列的方法用于重排序任务。在这种模式中，多个段落以列表方式进行重排序，并生成文本重排序排列。然而，由于 LLMs 的上下文窗口有限，这种重排序模式需要滑动窗口策略来迭代处理更大的候选集。这不仅增加了计算成本，还限制了 LLM 充分捕获所有候选者的所有比较信息。为了应对这些挑战，我们提出了一种新颖的自校准列表式重排序方法，旨在利用 LLMs 生成用于排序的全局相关性得分。为了实现这一目标，我们首先提出了相关性感知的列表式重排序框架，该框架结合了明确的列表视图相关性得分，以提高重排序效率，并能够在整个候选集中进行全局比较。其次，为了确保计算得分的可比性，我们提出了自校准训练，使用 LLM 自身内部生成的点视图相关性评估来校准列表视图相关性评估。在 BEIR 基准和 TREC 深度学习轨道上的大量实验和综合分析证明了我们提出的方法的有效性和效率。

> Large language models (LLMs), with advanced linguistic capabilities, have been employed in reranking tasks through a sequence-to-sequence approach. In this paradigm, multiple passages are reranked in a listwise manner and a textual reranked permutation is generated. However, due to the limited context window of LLMs, this reranking paradigm requires a sliding window strategy to iteratively handle larger candidate sets. This not only increases computational costs but also restricts the LLM from fully capturing all the comparison information for all candidates. To address these challenges, we propose a novel self-calibrated listwise reranking method, which aims to leverage LLMs to produce global relevance scores for ranking. To achieve it, we first propose the relevance-aware listwise reranking framework, which incorporates explicit list-view relevance scores to improve reranking efficiency and enable global comparison across the entire candidate set. Second, to ensure the comparability of the computed scores, we propose self-calibrated training that uses point-view relevance assessments generated internally by the LLM itself to calibrate the list-view relevance assessments. Extensive experiments and comprehensive analysis on the BEIR benchmark and TREC Deep Learning Tracks demonstrate the effectiveness and efficiency of our proposed method.

[Arxiv](https://arxiv.org/abs/2411.04602)