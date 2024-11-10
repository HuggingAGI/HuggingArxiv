# Bio-xLSTM：生物和化学序列的生成建模、表示和上下文学习

发布时间：2024年11月06日

`LLM应用` `生物化学` `医疗健康`

> Bio-xLSTM: Generative modeling, representation and in-context learning of biological and chemical sequences

# 摘要

> 摘要：用于生物和化学序列的语言模型能够实现诸如药物发现、蛋白质工程和精准医疗等关键应用。目前，这些语言模型主要基于 Transformer 架构。虽然 Transformer 取得了令人瞩目的成果，但其对序列长度的二次运行时依赖使得它们在长基因组序列以及蛋白质和化学序列的上下文学习中的应用变得复杂。最近，循环 xLSTM 架构在自然语言领域中已被证明与 Transformer 和现代状态空间模型（SSM）架构相比表现良好。与 SSM 类似，xLSTM 对序列长度具有线性运行时依赖，并允许在推理时进行常量内存解码，这使其成为对生物和化学序列中的长程依赖进行建模的主要候选者。在这项工作中，我们针对这些领域定制了 xLSTM，并提出了一套称为 Bio-xLSTM 的架构变体。在基因组学、蛋白质和化学这三个大领域进行了广泛的实验，以评估 xLSTM 对生物和化学序列建模的能力。结果表明，基于 Bio-xLSTM 的模型 a）可以作为 DNA、蛋白质和化学序列的熟练生成模型，b）为这些模式学习丰富的表示，c）可以对蛋白质和小分子进行上下文学习。

> 
Abstract:Language models for biological and chemical sequences enable crucial applications such as drug discovery, protein engineering, and precision medicine. Currently, these language models are predominantly based on Transformer architectures. While Transformers have yielded impressive results, their quadratic runtime dependency on the sequence length complicates their use for long genomic sequences and in-context learning on proteins and chemical sequences. Recently, the recurrent xLSTM architecture has been shown to perform favorably compared to Transformers and modern state-space model (SSM) architectures in the natural language domain. Similar to SSMs, xLSTMs have a linear runtime dependency on the sequence length and allow for constant-memory decoding at inference time, which makes them prime candidates for modeling long-range dependencies in biological and chemical sequences. In this work, we tailor xLSTM towards these domains and propose a suite of architectural variants called Bio-xLSTM. Extensive experiments in three large domains, genomics, proteins, and chemistry, were performed to assess xLSTM's ability to model biological and chemical sequences. The results show that models based on Bio-xLSTM a) can serve as proficient generative models for DNA, protein, and chemical sequences, b) learn rich representations for those modalities, and c) can perform in-context learning for proteins and small molecules.
    

[Arxiv](https://arxiv.org/pdf/2411.04165)