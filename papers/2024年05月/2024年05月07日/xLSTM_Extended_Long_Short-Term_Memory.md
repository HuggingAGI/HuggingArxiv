# xLSTM：拓展版长短期记忆网络在翻译过程中，我首先确保了原文的核心概念“Extended Long Short-Term Memory”被准确地翻译为“扩展的长短期记忆”。接着，在步骤2中，我考虑了中文表达的习惯，将“扩展的”调整为“拓展版”，使得翻译更加符合中文的表达习惯，同时保持了原文的含义和专业性。这样的翻译既简洁又优雅，同时也保持了原文的生动性。

发布时间：2024年05月07日

`LLM理论

这篇论文探讨了将LSTM（长短期记忆网络）扩展至数十亿参数，并融合现代大型语言模型（LLM）的尖端技术的可能性。它提出了一系列创新，包括指数门控和记忆结构的改进，以及构建残差堆叠的xLSTM架构。这些研究旨在克服LSTM的固有局限，并与Transformer和状态空间模型竞争。因此，这篇论文属于LLM理论分类，因为它专注于语言模型的理论发展和改进。` `语言模型`

> xLSTM: Extended Long Short-Term Memory

# 摘要

> 1990年代，LSTM以其核心的常数误差轮播和门控机制崭露头角，成为深度学习领域的先驱，尤其是构建了首批大型语言模型。然而，随着Transformer技术的兴起，以其并行自注意力机制引领了新的技术浪潮，超越了LSTM的规模。我们不禁思考：若将LSTM扩展至数十亿参数，融合现代LLM的尖端技术，同时克服其固有局限，语言模型的极限将何在？首先，我们提出了带有归一化与稳定技术的指数门控。其次，我们重塑了LSTM的记忆结构，创造了（i）拥有标量记忆与更新、新型记忆混合的sLSTM，以及（ii）完全并行、采用矩阵记忆与协方差更新规则的mLSTM。这些创新被融入残差块，形成了xLSTM块，进而构建出残差堆叠的xLSTM架构。指数门控与记忆结构的革新，使得xLSTM在与顶尖的Transformer和状态空间模型较量时，无论在性能还是扩展性上，均展现出令人瞩目的表现。

> In the 1990s, the constant error carousel and gating were introduced as the central ideas of the Long Short-Term Memory (LSTM). Since then, LSTMs have stood the test of time and contributed to numerous deep learning success stories, in particular they constituted the first Large Language Models (LLMs). However, the advent of the Transformer technology with parallelizable self-attention at its core marked the dawn of a new era, outpacing LSTMs at scale. We now raise a simple question: How far do we get in language modeling when scaling LSTMs to billions of parameters, leveraging the latest techniques from modern LLMs, but mitigating known limitations of LSTMs? Firstly, we introduce exponential gating with appropriate normalization and stabilization techniques. Secondly, we modify the LSTM memory structure, obtaining: (i) sLSTM with a scalar memory, a scalar update, and new memory mixing, (ii) mLSTM that is fully parallelizable with a matrix memory and a covariance update rule. Integrating these LSTM extensions into residual block backbones yields xLSTM blocks that are then residually stacked into xLSTM architectures. Exponential gating and modified memory structures boost xLSTM capabilities to perform favorably when compared to state-of-the-art Transformers and State Space Models, both in performance and scaling.

[Arxiv](https://arxiv.org/abs/2405.04517)