# 简化 CLIP ：让大规模模型在消费级电脑上释放强大力量

发布时间：2024年11月22日

`LLM应用` `计算机视觉` `模型训练`

> Simplifying CLIP: Unleashing the Power of Large-Scale Models on Consumer-level Computers

# 摘要

> 对比语言-图像预训练（CLIP）凭借出色的零样本性能和对下游任务的优异可迁移性，备受关注。但训练这类大规模模型往往需要大量的计算和存储资源，这给使用消费级电脑的普通用户带来了阻碍。基于这一观察，本文探讨如何仅依靠一个 Nvidia RTX3090 GPU 和 1TB 的数据集存储空间来获得具有竞争力的性能。一方面，我们简化了 Transformer 块结构，将权重继承与多阶段知识蒸馏（WIKD）相结合，减少了参数，提高了训练和部署时的推理速度。另一方面，针对小数据集导致的收敛难题，我们为每个样本生成合成标题以进行数据增强，并设计了一种新颖的配对匹配（PM）损失，充分挖掘正、负图像-文本对之间的差异。大量实验表明，我们的模型能够达成新的前沿数据规模-参数-精度平衡，有助于在相关研究领域进一步推广 CLIP 模型。

> Contrastive Language-Image Pre-training (CLIP) has attracted a surge of attention for its superior zero-shot performance and excellent transferability to downstream tasks. However, training such large-scale models usually requires substantial computation and storage, which poses barriers for general users with consumer-level computers. Motivated by this observation, in this paper we investigate how to achieve competitive performance on only one Nvidia RTX3090 GPU and with one terabyte for storing dataset. On one hand, we simplify the transformer block structure and combine Weight Inheritance with multi-stage Knowledge Distillation (WIKD), thereby reducing the parameters and improving the inference speed during training along with deployment. On the other hand, confronted with the convergence challenge posed by small dataset, we generate synthetic captions for each sample as data augmentation, and devise a novel Pair Matching (PM) loss to fully exploit the distinguishment among positive and negative image-text pairs. Extensive experiments demonstrate that our model can achieve a new state-of-the-art datascale-parameter-accuracy tradeoff, which could further popularize the CLIP model in the related research community.

[Arxiv](https://arxiv.org/abs/2411.14789)