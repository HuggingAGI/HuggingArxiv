# 语义相似度视角下的核语言熵：为大型语言模型提供细粒度不确定性量化

发布时间：2024年05月30日

`LLM理论

这篇论文主要关注的是大型语言模型（LLMs）中的不确定性量化问题，特别是语义不确定性的捕捉。论文提出了核语言熵（KLE）作为一种新颖的不确定性估计方法，并从理论和实验两个方面进行了验证。这种方法不仅适用于白盒LLMs，也适用于黑盒LLMs，并且通过定义正半定单位迹核来编码LLM输出的语义相似性，使用冯·诺依曼熵来量化不确定性。因此，这篇论文的内容更偏向于LLM的理论研究，而不是具体的应用、Agent设计或RAG（Retrieval-Augmented Generation）技术。` `人工智能安全`

> Kernel Language Entropy: Fine-grained Uncertainty Quantification for LLMs from Semantic Similarities

# 摘要

> 在大规模语言模型（LLMs）中，量化不确定性对于安全和可靠性至关重要的应用至关重要。通过检测事实错误的模型响应（通常称为幻觉），不确定性可以用来提高LLMs的可信度。我们关注的重点是捕捉模型的语义不确定性，即LLM输出的意义的不确定性，而非词汇或句法变化的不确定性。为此，我们提出了核语言熵（KLE），这是一种新颖的不确定性估计方法，适用于白盒和黑盒LLMs。KLE通过定义正半定单位迹核来编码LLM输出的语义相似性，并使用冯·诺依曼熵来量化不确定性。它考虑了答案（或语义簇）之间的成对语义依赖关系，提供了比基于答案硬聚类的前期方法更细粒度的不确定性估计。理论上，我们证明了KLE推广了之前称为语义熵的最新方法，并通过实验证明了它在多个自然语言生成数据集和LLM架构上提高了不确定性量化性能。

> Uncertainty quantification in Large Language Models (LLMs) is crucial for applications where safety and reliability are important. In particular, uncertainty can be used to improve the trustworthiness of LLMs by detecting factually incorrect model responses, commonly called hallucinations. Critically, one should seek to capture the model's semantic uncertainty, i.e., the uncertainty over the meanings of LLM outputs, rather than uncertainty over lexical or syntactic variations that do not affect answer correctness. To address this problem, we propose Kernel Language Entropy (KLE), a novel method for uncertainty estimation in white- and black-box LLMs. KLE defines positive semidefinite unit trace kernels to encode the semantic similarities of LLM outputs and quantifies uncertainty using the von Neumann entropy. It considers pairwise semantic dependencies between answers (or semantic clusters), providing more fine-grained uncertainty estimates than previous methods based on hard clustering of answers. We theoretically prove that KLE generalizes the previous state-of-the-art method called semantic entropy and empirically demonstrate that it improves uncertainty quantification performance across multiple natural language generation datasets and LLM architectures.

![语义相似度视角下的核语言熵：为大型语言模型提供细粒度不确定性量化](../../../paper_images/2405.20003/x1.png)

![语义相似度视角下的核语言熵：为大型语言模型提供细粒度不确定性量化](../../../paper_images/2405.20003/x2.png)

![语义相似度视角下的核语言熵：为大型语言模型提供细粒度不确定性量化](../../../paper_images/2405.20003/x3.png)

![语义相似度视角下的核语言熵：为大型语言模型提供细粒度不确定性量化](../../../paper_images/2405.20003/x4.png)

![语义相似度视角下的核语言熵：为大型语言模型提供细粒度不确定性量化](../../../paper_images/2405.20003/x5.png)

![语义相似度视角下的核语言熵：为大型语言模型提供细粒度不确定性量化](../../../paper_images/2405.20003/x6.png)

![语义相似度视角下的核语言熵：为大型语言模型提供细粒度不确定性量化](../../../paper_images/2405.20003/x7.png)

![语义相似度视角下的核语言熵：为大型语言模型提供细粒度不确定性量化](../../../paper_images/2405.20003/x8.png)

![语义相似度视角下的核语言熵：为大型语言模型提供细粒度不确定性量化](../../../paper_images/2405.20003/x9.png)

![语义相似度视角下的核语言熵：为大型语言模型提供细粒度不确定性量化](../../../paper_images/2405.20003/x10.png)

![语义相似度视角下的核语言熵：为大型语言模型提供细粒度不确定性量化](../../../paper_images/2405.20003/x11.png)

![语义相似度视角下的核语言熵：为大型语言模型提供细粒度不确定性量化](../../../paper_images/2405.20003/x12.png)

![语义相似度视角下的核语言熵：为大型语言模型提供细粒度不确定性量化](../../../paper_images/2405.20003/x13.png)

![语义相似度视角下的核语言熵：为大型语言模型提供细粒度不确定性量化](../../../paper_images/2405.20003/x14.png)

![语义相似度视角下的核语言熵：为大型语言模型提供细粒度不确定性量化](../../../paper_images/2405.20003/x15.png)

![语义相似度视角下的核语言熵：为大型语言模型提供细粒度不确定性量化](../../../paper_images/2405.20003/x16.png)

![语义相似度视角下的核语言熵：为大型语言模型提供细粒度不确定性量化](../../../paper_images/2405.20003/x17.png)

![语义相似度视角下的核语言熵：为大型语言模型提供细粒度不确定性量化](../../../paper_images/2405.20003/x18.png)

![语义相似度视角下的核语言熵：为大型语言模型提供细粒度不确定性量化](../../../paper_images/2405.20003/x19.png)

![语义相似度视角下的核语言熵：为大型语言模型提供细粒度不确定性量化](../../../paper_images/2405.20003/x20.png)

[Arxiv](https://arxiv.org/abs/2405.20003)