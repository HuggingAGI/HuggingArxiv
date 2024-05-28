# NV-Embed：提升大型语言模型作为通用嵌入模型训练技术的革新方法

发布时间：2024年05月27日

`LLM应用

这篇论文介绍了NV-Embed模型，这是一种基于解码器的LLM嵌入模型，它在通用文本嵌入任务中超越了BERT和T5。论文详细描述了模型的创新架构和训练策略，包括潜在注意力层的使用和两阶段对比指令调优方法。这些改进不仅提升了模型的多功能性，还保持了其简洁可复现的特点。此外，论文还报告了NV-Embed模型在多个基准测试中的优异表现，包括MTEB和BEIR。最后，论文提到模型将在Hugging Face平台上开源。这些内容主要关注于LLM的具体应用和性能提升，因此归类为LLM应用。` `机器学习`

> NV-Embed: Improved Techniques for Training LLMs as Generalist Embedding Models

# 摘要

> 基于解码器的LLM嵌入模型在通用文本嵌入任务中已超越BERT和T5，我们推出的NV-Embed模型通过创新架构和训练策略，不仅提升了LLM的多功能性，还保持了其简洁可复现的特点。我们提出的潜在注意力层有效提升了检索和下游任务的准确性。在训练上，我们采用了两阶段对比指令调优，第一阶段专注于检索数据集，第二阶段则融合了多种非检索数据集，全面提升了模型性能。NV-Embed模型在MTEB基准上以69.32分创下新高，涵盖56项任务，包括检索、分类等，并在BEIR的15项检索任务中以59.36分位居榜首。我们将在https://huggingface.co/nvidia/NV-Embed-v1开源此模型。

> Decoder-only large language model (LLM)-based embedding models are beginning to outperform BERT or T5-based embedding models in general-purpose text embedding tasks, including dense vector-based retrieval. In this work, we introduce the NV-Embed model with a variety of architectural designs and training procedures to significantly enhance the performance of LLM as a versatile embedding model, while maintaining its simplicity and reproducibility. For model architecture, we propose a latent attention layer to obtain pooled embeddings, which consistently improves retrieval and downstream task accuracy compared to mean pooling or using the last <EOS> token embedding from LLMs. To enhance representation learning, we remove the causal attention mask of LLMs during contrastive training. For model training, we introduce a two-stage contrastive instruction-tuning method. It first applies contrastive training with instructions on retrieval datasets, utilizing in-batch negatives and curated hard negative examples. At stage-2, it blends various non-retrieval datasets into instruction tuning, which not only enhances non-retrieval task accuracy but also improves retrieval performance. Combining these techniques, our NV-Embed model, using only publicly available data, has achieved a record-high score of 69.32, ranking No. 1 on the Massive Text Embedding Benchmark (MTEB) (as of May 24, 2024), with 56 tasks, encompassing retrieval, reranking, classification, clustering, and semantic textual similarity tasks. Notably, our model also attains the highest score of 59.36 on 15 retrieval tasks in the MTEB benchmark (also known as BEIR). We will open-source the model at: https://huggingface.co/nvidia/NV-Embed-v1.

![NV-Embed：提升大型语言模型作为通用嵌入模型训练技术的革新方法](../../../paper_images/2405.17428/Latent_attention2.png)

[Arxiv](https://arxiv.org/abs/2405.17428)