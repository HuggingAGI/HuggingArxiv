# R^2AG：融合检索信息的增强生成技术

发布时间：2024年06月19日

`RAG

这篇论文主要讨论了检索增强生成（RAG）框架的改进，即R²AG框架，它旨在通过整合检索信息来弥合大型语言模型（LLMs）与检索器之间的语义鸿沟。论文的创新点在于利用检索器的细微特征，并通过R²-Former捕捉这些信息，设计了一种检索感知的提示策略，以改善LLMs的生成过程。这与Agent、LLM应用、LLM理论分类不符，而是直接关联到RAG的改进和应用，因此归类为RAG。` `信息检索`

> R^2AG: Incorporating Retrieval Information into Retrieval Augmented Generation

# 摘要

> 检索增强生成（RAG）已广泛应用于各种情境，旨在通过外部文档增强大型语言模型（LLMs）的能力。然而，由于训练目标和架构的不同，LLMs与检索器之间存在语义鸿沟，导致LLMs在生成过程中被动接受并需辨别检索器提供的文档。为此，本文创新性地提出了R²AG框架，通过整合检索信息来弥合这一鸿沟。R²AG巧妙地利用检索器的细微特征，并通过R²-Former捕捉这些信息，进而设计了一种检索感知的提示策略，将这些信息融入LLMs的生成过程。特别地，R²AG在LLMs和检索器固定的低资源环境下表现出色。通过跨五个数据集的广泛实验，R²AG展现了其有效性、鲁棒性和效率。分析表明，检索信息如同锚点，助力LLMs在生成中填补语义鸿沟。

> Retrieval augmented generation (RAG) has been applied in many scenarios to augment large language models (LLMs) with external documents provided by retrievers. However, a semantic gap exists between LLMs and retrievers due to differences in their training objectives and architectures. This misalignment forces LLMs to passively accept the documents provided by the retrievers, leading to incomprehension in the generation process, where the LLMs are burdened with the task of distinguishing these documents using their inherent knowledge. This paper proposes R$^2$AG, a novel enhanced RAG framework to fill this gap by incorporating Retrieval information into Retrieval Augmented Generation. Specifically, R$^2$AG utilizes the nuanced features from the retrievers and employs a R$^2$-Former to capture retrieval information. Then, a retrieval-aware prompting strategy is designed to integrate retrieval information into LLMs' generation. Notably, R$^2$AG suits low-source scenarios where LLMs and retrievers are frozen. Extensive experiments across five datasets validate the effectiveness, robustness, and efficiency of R$^2$AG. Our analysis reveals that retrieval information serves as an anchor to aid LLMs in the generation process, thereby filling the semantic gap.

![R^2AG：融合检索信息的增强生成技术](../../../paper_images/2406.13249/x1.png)

![R^2AG：融合检索信息的增强生成技术](../../../paper_images/2406.13249/x2.png)

![R^2AG：融合检索信息的增强生成技术](../../../paper_images/2406.13249/x3.png)

![R^2AG：融合检索信息的增强生成技术](../../../paper_images/2406.13249/x4.png)

![R^2AG：融合检索信息的增强生成技术](../../../paper_images/2406.13249/x5.png)

![R^2AG：融合检索信息的增强生成技术](../../../paper_images/2406.13249/x6.png)

![R^2AG：融合检索信息的增强生成技术](../../../paper_images/2406.13249/x7.png)

![R^2AG：融合检索信息的增强生成技术](../../../paper_images/2406.13249/x8.png)

[Arxiv](https://arxiv.org/abs/2406.13249)