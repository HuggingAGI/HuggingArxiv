# 炼金术：借助符号变异，提升定理证明的威力

发布时间：2024年10月21日

`LLM应用` `计算机科学` `人工智能`

> Alchemy: Amplifying Theorem-Proving Capability through Symbolic Mutation

# 摘要

> 形式证明的编写对专家来说也颇具挑战。神经定理证明 (NTP) 的进步虽有望加速此过程，但互联网上的形式语料库远少于一般文本，给 NTP 带来了数据稀缺的难题。为此，我们提出了 Alchemy 框架，通过符号变异生成形式定理。具体而言，我们识别并应用可调用的定理来变异 Mathlib 中的候选定理，使其数量从 110k 激增至 6M。随后，我们对增强后的语料库进行预训练和微调，应用于大型语言模型。实验显示，我们的方法在 Leandojo 基准上提升了 5% 的性能，且合成数据在 miniF2F 基准上也取得了 2.5% 的提升。此外，我们对合成数据和训练范式进行了深入分析，为构建强大的定理证明器提供了重要指导。

> Formal proofs are challenging to write even for experienced experts. Recent progress in Neural Theorem Proving (NTP) shows promise in expediting this process. However, the formal corpora available on the Internet are limited compared to the general text, posing a significant data scarcity challenge for NTP. To address this issue, this work proposes Alchemy, a general framework for data synthesis that constructs formal theorems through symbolic mutation. Specifically, for each candidate theorem in Mathlib, we identify all invocable theorems that can be used to rewrite or apply to it. Subsequently, we mutate the candidate theorem by replacing the corresponding term in the statement with its equivalent form or antecedent. As a result, our method increases the number of theorems in Mathlib by an order of magnitude, from 110k to 6M. Furthermore, we perform continual pretraining and supervised finetuning on this augmented corpus for large language models. Experimental results demonstrate the effectiveness of our approach, achieving a 5% absolute performance improvement on Leandojo benchmark. Additionally, our synthetic data achieve a 2.5% absolute performance gain on the out-of-distribution miniF2F benchmark. To provide further insights, we conduct a comprehensive analysis of synthetic data composition and the training paradigm, offering valuable guidance for developing a strong theorem prover.

[Arxiv](https://arxiv.org/abs/2410.15748)