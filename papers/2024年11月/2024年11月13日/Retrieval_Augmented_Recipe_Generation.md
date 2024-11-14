# 检索增强的食谱生成

发布时间：2024年11月13日

`LLM应用` `图像识别`

> Retrieval Augmented Recipe Generation

# 摘要

> 鉴于从食物图像生成食谱的潜在应用，近年来这一领域受到了研究人员的极大关注。现有的食谱生成工作主要采用两阶段训练方法，首先生成食材，然后从图像和食材中获取指令。在各种视觉和语言任务中取得显著成功的大型多模态模型（LMMs），为直接从图像生成食材和指令带来了希望。然而，LMMs 在食谱生成过程中仍然面临常见的幻觉问题，导致性能不佳。为了解决这个问题，我们提出了一种用于食谱生成的检索增强大型多模态模型。我们首先引入随机多样化检索增强（SDRA），从现有数据存储中检索与图像语义相关的食谱作为补充，将它们集成到提示中，为输入图像添加多样和丰富的上下文。此外，提出了自一致性集成投票机制，以确定最有信心的预测食谱作为最终输出。它计算生成的食谱候选之间的一致性，这些候选使用不同的检索食谱作为生成的上下文。大量实验验证了我们提出的方法的有效性，该方法在 Recipe1M 数据集的食谱生成任务中展示了最先进（SOTA）的性能。

> Given the potential applications of generating recipes from food images, this area has garnered significant attention from researchers in recent years. Existing works for recipe generation primarily utilize a two-stage training method, first generating ingredients and then obtaining instructions from both the image and ingredients. Large Multi-modal Models (LMMs), which have achieved notable success across a variety of vision and language tasks, shed light to generating both ingredients and instructions directly from images. Nevertheless, LMMs still face the common issue of hallucinations during recipe generation, leading to suboptimal performance. To tackle this, we propose a retrieval augmented large multimodal model for recipe generation. We first introduce Stochastic Diversified Retrieval Augmentation (SDRA) to retrieve recipes semantically related to the image from an existing datastore as a supplement, integrating them into the prompt to add diverse and rich context to the input image. Additionally, Self-Consistency Ensemble Voting mechanism is proposed to determine the most confident prediction recipes as the final output. It calculates the consistency among generated recipe candidates, which use different retrieval recipes as context for generation. Extensive experiments validate the effectiveness of our proposed method, which demonstrates state-of-the-art (SOTA) performance in recipe generation tasks on the Recipe1M dataset.

[Arxiv](https://arxiv.org/abs/2411.08715)