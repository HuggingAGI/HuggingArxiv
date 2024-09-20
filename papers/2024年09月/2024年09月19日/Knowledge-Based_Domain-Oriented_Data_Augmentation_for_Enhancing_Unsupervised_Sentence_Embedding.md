# 利用知识驱动的领域导向数据增强技术，提升无监督句子嵌入的效果。

发布时间：2024年09月19日

`LLM应用` `数据增强`

> Knowledge-Based Domain-Oriented Data Augmentation for Enhancing Unsupervised Sentence Embedding

# 摘要

> 近期，无监督句子嵌入模型在自然语言处理任务中备受瞩目。利用大型语言模型 (LLM) 进行数据增强，以往研究已取得显著成效。然而，这些策略多依赖于广泛通用语料库，忽视了少样本领域数据的精细处理。合成的数据往往缺乏细节，甚至可能引入噪声。为此，我们提出了一种基于管道的新型数据增强方法，利用 LLM 生成领域特定数据集。通过实体和数量感知增强，结合实体知识图谱，生成具有细粒度语义区别的样本，提升训练样本的多样性与相关性。同时，我们设计了高斯衰减梯度辅助的对比句子嵌入 (GCSE) 模型，有效减少合成数据噪声，增强模型辨别力。实验证明，我们的方法在少量合成数据和较少 LLM 参数下，仍能实现顶尖的语义文本相似性性能，展现了其在多样化应用中的高效与稳健。

> Recently, unsupervised sentence embedding models have received significant attention in downstream natural language processing tasks. Using large language models (LLMs) for data augmentation has led to considerable improvements in previous studies. Nevertheless, these strategies emphasize data augmentation with extensive generic corpora, neglecting the consideration of few-shot domain data. The synthesized data lacks fine-grained information and may introduce negative sample noise. This study introduces a novel pipeline-based data augmentation method that leverages LLM to synthesize the domain-specific dataset. It produces both positive and negative samples through entity- and quantity-aware augmentation, utilizing an entity knowledge graph to synthesize samples with fine-grained semantic distinctions, increasing training sample diversity and relevance. We then present a Gaussian-decayed gradient-assisted Contrastive Sentence Embedding (GCSE) model to reduce synthetic data noise and improve model discrimination to reduce negative sample noise. Experimental results demonstrate that our approach achieves state-of-the-art semantic textual similarity performance with fewer synthetic data samples and lesser LLM parameters, demonstrating its efficiency and robustness in varied backbones.

[Arxiv](https://arxiv.org/abs/2409.12887)