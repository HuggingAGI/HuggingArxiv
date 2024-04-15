# 探索大型语言模型中的分词原理

发布时间：2024年04月12日

`LLM理论` `语言模型` `分词算法`

> Toward a Theory of Tokenization in LLMs

# 摘要

> 虽然众多研究努力绕过分词这一语言建模的难题（Clark等，2022；Xue等，2022），但普遍认为分词是打造尖端性能语言模型的关键第一步。本文从理论视角切入，通过分析变换器处理简单数据生成过程的表现，探讨了分词的必要性。我们发现，在缺乏分词的情况下，变换器在训练时难以掌握准确分布，预测字符仅能依赖单字模型（Makkuva等，2024）。而一旦引入分词，变换器便能突破限制，高效地模拟序列概率，获得较小的交叉熵损失。基于这一发现，我们进一步分析了变换器在有无分词情况下的端到端交叉熵损失。研究表明，只要分词得当，变换器即便学习最简单的单字模型（基于分词），也能近乎完美地模拟k阶马尔可夫源中的序列概率。本研究通过观察变换器在马尔可夫数据上的表现，为分词在实际应用中的合理性提供了有力论证。

> While there has been a large body of research attempting to circumvent tokenization for language modeling (Clark et al., 2022; Xue et al., 2022), the current consensus is that it is a necessary initial step for designing state-of-the-art performant language models. In this paper, we investigate tokenization from a theoretical point of view by studying the behavior of transformers on simple data generating processes. When trained on data drawn from certain simple $k^{\text{th}}$-order Markov processes for $k > 1$, transformers exhibit a surprising phenomenon - in the absence of tokenization, they empirically fail to learn the right distribution and predict characters according to a unigram model (Makkuva et al., 2024). With the addition of tokenization, however, we empirically observe that transformers break through this barrier and are able to model the probabilities of sequences drawn from the source near-optimally, achieving small cross-entropy loss. With this observation as starting point, we study the end-to-end cross-entropy loss achieved by transformers with and without tokenization. With the appropriate tokenization, we show that even the simplest unigram models (over tokens) learnt by transformers are able to model the probability of sequences drawn from $k^{\text{th}}$-order Markov sources near optimally. Our analysis provides a justification for the use of tokenization in practice through studying the behavior of transformers on Markovian data.

[Arxiv](https://arxiv.org/abs/2404.08335)