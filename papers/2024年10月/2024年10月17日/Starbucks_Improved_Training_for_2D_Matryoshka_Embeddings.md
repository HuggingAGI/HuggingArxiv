# 星巴克：优化了2D套娃嵌入的训练方法

发布时间：2024年10月17日

`LLM理论` `信息检索`

> Starbucks: Improved Training for 2D Matryoshka Embeddings

# 摘要

> 我们提出了一种名为Starbucks的新训练策略，用于Matryoshka类嵌入模型，涵盖微调和预训练阶段。在微调阶段，通过固定层-维度对列表并计算所有对的损失，显著提升了2D Matryoshka模型的效果，使其与单独训练的模型不相上下。此外，引入的预训练策略通过掩码自编码器语言建模，为模型提供了更强的基础。实验结果显示，这些策略使Starbucks模型在语义文本相似性和检索任务中表现出色，超越了单独训练的模型。

> Effective approaches that can scale embedding model depth (i.e. layers) and embedding size allow for the creation of models that are highly scalable across different computational resources and task requirements. While the recently proposed 2D Matryoshka training approach can efficiently produce a single embedding model such that its sub-layers and sub-dimensions can measure text similarity, its effectiveness is significantly worse than if smaller models were trained separately. To address this issue, we propose Starbucks, a new training strategy for Matryoshka-like embedding models, which encompasses both the fine-tuning and pre-training phases. For the fine-tuning phase, we discover that, rather than sampling a random sub-layer and sub-dimensions for each training steps, providing a fixed list of layer-dimension pairs, from small size to large sizes, and computing the loss across all pairs significantly improves the effectiveness of 2D Matryoshka embedding models, bringing them on par with their separately trained counterparts. To further enhance performance, we introduce a new pre-training strategy, which applies masked autoencoder language modelling to sub-layers and sub-dimensions during pre-training, resulting in a stronger backbone for subsequent fine-tuning of the embedding model. Experimental results on both semantic text similarity and retrieval benchmarks demonstrate that the proposed pre-training and fine-tuning strategies significantly improved the effectiveness over 2D Matryoshka models, enabling Starbucks models to perform more efficiently and effectively than separately trained models.

[Arxiv](https://arxiv.org/abs/2410.13230)