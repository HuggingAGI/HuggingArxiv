# 融合去噪自编码器与对比学习，精调Transformer模型

发布时间：2024年05月23日

`LLM应用

这篇论文摘要描述了一种针对大型预训练Transformer模型的优化策略，用于提高其在分类任务中的性能。研究中采用了去噪自编码器（DAE）、对比学习（CL）和数据增强策略等方法，旨在调整和优化模型的输出表示，以更好地匹配目标类别。这些方法的应用和优化过程直接关联到大型语言模型（LLM）的实际应用，特别是在处理分类挑战时的具体策略和效果验证。因此，这篇论文更符合LLM应用的分类。` `机器学习`

> Combining Denoising Autoencoders with Contrastive Learning to fine-tune Transformer Models

# 摘要

> 近期，大型预训练Transformer模型在迁移学习领域的应用已成为自然语言处理（NLP）的一大趋势，衍生出基于提示、适配器或与无监督方法结合等多种创新。本研究提出了一种三阶段策略，旨在优化基础模型以应对分类挑战。首先，通过去噪自编码器（DAE）的深度训练，我们调整模型以适应数据特性。接着，利用对比学习（CL）聚类技术，我们精细调整输出空间的表示，使其与目标类别相匹配。此外，我们还创新性地引入了一种数据增强策略，专为监督对比学习设计，以平衡数据集的不均。最后，通过微调，我们确保模型能够准确识别预设类别。这些阶段不仅为模型提供了关键信息，还相互补充，助力模型完成最终任务。我们通过多数据集的广泛实验验证了这些方法的有效性，并进行了消融研究，与其他技术结合方式进行了对比分析。

> Recently, using large pretrained Transformer models for transfer learning tasks has evolved to the point where they have become one of the flagship trends in the Natural Language Processing (NLP) community, giving rise to various outlooks such as prompt-based, adapters or combinations with unsupervised approaches, among many others. This work proposes a 3 Phase technique to adjust a base model for a classification task. First, we adapt the model's signal to the data distribution by performing further training with a Denoising Autoencoder (DAE). Second, we adjust the representation space of the output to the corresponding classes by clustering through a Contrastive Learning (CL) method. In addition, we introduce a new data augmentation approach for Supervised Contrastive Learning to correct the unbalanced datasets. Third, we apply fine-tuning to delimit the predefined categories. These different phases provide relevant and complementary knowledge to the model to learn the final task. We supply extensive experimental results on several datasets to demonstrate these claims. Moreover, we include an ablation study and compare the proposed method against other ways of combining these techniques.

[Arxiv](https://arxiv.org/abs/2405.14437)