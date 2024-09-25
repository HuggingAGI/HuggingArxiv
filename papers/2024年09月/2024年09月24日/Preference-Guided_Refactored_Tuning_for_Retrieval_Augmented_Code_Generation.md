# 基于偏好的检索增强代码生成重构调优

发布时间：2024年09月24日

`RAG` `软件开发` `人工智能`

> Preference-Guided Refactored Tuning for Retrieval Augmented Code Generation

# 摘要

> 检索增强代码生成通过大型语言模型和检索器提供相关代码和文档，显著提升了代码生成能力。然而，现有方法存在信息冗余和偏好差距两大问题：冗余信息浪费资源并可能误导生成器；检索器和生成器因优化目标不同而偏好不同代码，导致设计次优。此外，预训练期间的参数化知识差异也影响了生成器的偏好。为解决这些问题，我们提出了RRG框架，通过在检索器和生成器之间引入代码重构模块，将检索到的代码重构为更简洁、高效的版本，从而消除冗余信息，提升生成器接收到的上下文质量，降低推理成本，生成更准确的结果。实验证明，RRG有效弥合了检索器和生成器之间的偏好差距，显著提升了性能，EM提升28%，BLEU提升13%，CodeBLEU提升6.8%。

> Retrieval-augmented code generation utilizes Large Language Models as the generator and significantly expands their code generation capabilities by providing relevant code, documentation, and more via the retriever. The current approach suffers from two primary limitations: 1) information redundancy. The indiscriminate inclusion of redundant information can result in resource wastage and may misguide generators, affecting their effectiveness and efficiency. 2) preference gap. Due to different optimization objectives, the retriever strives to procure code with higher ground truth similarity, yet this effort does not substantially benefit the generator. The retriever and the generator may prefer different golden code, and this gap in preference results in a suboptimal design. Additionally, differences in parameterization knowledge acquired during pre-training result in varying preferences among different generators.
  To address these limitations, in this paper, we propose RRG (Retrieve, Refactor, Generate), a novel framework for effective and efficient code generation. This framework introduces a code refactorer module between the retriever and the generator to bridge them. The refactoring process transforms the raw retrieved code into a more concise, efficient, and model-friendly version. It eliminates redundant information and noise, reducing the input length. Consequently, the generator receives higher-quality context, enabling it to produce more accurate results with lower inference costs. We conducted comprehensive experiments on multiple datasets. In the experiments, we confirmed the existence of a preference gap between the retriever and the generator, and RRG effectively bridges this gap. Specifically, RRG achieved significant performance improvements, with increases of up to 28% on EM, 13% on BLEU, and 6.8% on CodeBLEU.

[Arxiv](https://arxiv.org/abs/2409.15895)