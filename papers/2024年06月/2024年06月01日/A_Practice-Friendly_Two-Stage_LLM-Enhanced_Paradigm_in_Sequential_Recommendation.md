# 序列推荐中的实践友好型两阶段LLM增强范式

发布时间：2024年06月01日

`LLM应用

这篇论文探讨了如何通过一种创新的两阶段LLM增强范式（TSLRec）来优化序列推荐系统（SRS）。它特别关注于如何在不依赖于物品侧的丰富文本信息和实例级监督微调（SFT）的情况下，更高效地向LLM注入协同信息。这种方法通过用户级SFT任务和LLM推断物品的潜在类别来实现，最终生成结合协同信息与推理能力的增强嵌入，以辅助未来SRS模型的训练。因此，这篇论文属于LLM应用类别，因为它展示了LLM在实际应用中的具体使用和优化方法。` `推荐系统` `电子商务`

> A Practice-Friendly Two-Stage LLM-Enhanced Paradigm in Sequential Recommendation

# 摘要

> 大型语言模型（LLM）的整合训练范式正逐步革新序列推荐系统（SRS），并已显现出潜力。但现有的大多数LLM增强方法依赖于物品侧的丰富文本信息和实例级监督微调（SFT），以向LLM注入协同信息，这在多场景下效率不高且受限。为此，本文提出了一种创新的两阶段LLM增强范式（TSLRec），旨在优化SRS。在信息重建阶段，我们利用预训练SRS模型，设计了用户级SFT任务，以更高效地注入协同信息，并兼容有限文本信息。我们让LLM推断物品的潜在类别，并基于用户交互序列重构其对各类别的偏好分布。在信息增强阶段，我们将物品输入LLM，生成结合协同信息与推理能力的增强嵌入，这些嵌入将辅助未来SRS模型的训练。最后，我们在三个SRS基准数据集上验证了TSLRec的有效性与效率。

> The training paradigm integrating large language models (LLM) is gradually reshaping sequential recommender systems (SRS) and has shown promising results. However, most existing LLM-enhanced methods rely on rich textual information on the item side and instance-level supervised fine-tuning (SFT) to inject collaborative information into LLM, which is inefficient and limited in many applications. To alleviate these problems, this paper proposes a novel practice-friendly two-stage LLM-enhanced paradigm (TSLRec) for SRS. Specifically, in the information reconstruction stage, we design a new user-level SFT task for collaborative information injection with the assistance of a pre-trained SRS model, which is more efficient and compatible with limited text information. We aim to let LLM try to infer the latent category of each item and reconstruct the corresponding user's preference distribution for all categories from the user's interaction sequence. In the information augmentation stage, we feed each item into LLM to obtain a set of enhanced embeddings that combine collaborative information and LLM inference capabilities. These embeddings can then be used to help train various future SRS models. Finally, we verify the effectiveness and efficiency of our TSLRec on three SRS benchmark datasets.

![序列推荐中的实践友好型两阶段LLM增强范式](../../../paper_images/2406.00333/x1.png)

![序列推荐中的实践友好型两阶段LLM增强范式](../../../paper_images/2406.00333/x2.png)

![序列推荐中的实践友好型两阶段LLM增强范式](../../../paper_images/2406.00333/x3.png)

![序列推荐中的实践友好型两阶段LLM增强范式](../../../paper_images/2406.00333/x4.png)

![序列推荐中的实践友好型两阶段LLM增强范式](../../../paper_images/2406.00333/x5.png)

[Arxiv](https://arxiv.org/abs/2406.00333)