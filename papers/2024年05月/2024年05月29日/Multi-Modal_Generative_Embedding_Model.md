# 多模态生成式嵌入模型

发布时间：2024年05月29日

`LLM应用

这篇论文介绍了一种名为MM-GEM的多模态生成嵌入模型，它集成了生成和嵌入目标于单一大型语言模型中。该模型通过引入PoolAggregator提升了效率和细粒度处理能力，并在跨模态检索、零样本分类和图像描述生成等任务上表现出色。这些特性表明该论文关注的是大型语言模型在实际应用中的表现和优化，因此属于LLM应用分类。` `多模态学习` `图像处理`

> Multi-Modal Generative Embedding Model

# 摘要

> 多模态任务通常涉及生成或嵌入问题，现有模型通过分离语言模块来分别处理。我们追求极简，提出了一种集成生成与嵌入目标于单一大型语言模型的多模态生成嵌入模型（MM-GEM），并引入了PoolAggregator以提升效率和细粒度处理能力。令人意外的是，生成与嵌入目标在MM-GEM中和谐共存，该模型在跨模态检索和零样本分类等任务上表现出色，同时擅长图像描述生成，并能高效执行区域级图像描述与检索。此外，MM-GEM中的先进文本模型在长文本与图像检索的Recall@1上实现了超过5%的提升。

> Most multi-modal tasks can be formulated into problems of either generation or embedding. Existing models usually tackle these two types of problems by decoupling language modules into a text decoder for generation, and a text encoder for embedding. To explore the minimalism of multi-modal paradigms, we attempt to achieve only one model per modality in this work. We propose a Multi-Modal Generative Embedding Model (MM-GEM), whereby the generative and embedding objectives are encapsulated in one Large Language Model. We also propose a PoolAggregator to boost efficiency and enable the ability of fine-grained embedding and generation. A surprising finding is that these two objectives do not significantly conflict with each other. For example, MM-GEM instantiated from ViT-Large and TinyLlama shows competitive performance on benchmarks for multimodal embedding models such as cross-modal retrieval and zero-shot classification, while has good ability of image captioning. Additionally, MM-GEM can seamlessly execute region-level image caption generation and retrieval tasks. Besides, the advanced text model in MM-GEM brings over 5% improvement in Recall@1 for long text and image retrieval.

![多模态生成式嵌入模型](../../../paper_images/2405.19333/x1.png)

![多模态生成式嵌入模型](../../../paper_images/2405.19333/x2.png)

![多模态生成式嵌入模型](../../../paper_images/2405.19333/x3.png)

[Arxiv](https://arxiv.org/abs/2405.19333)