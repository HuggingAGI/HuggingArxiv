# 探索 LLM 后训练中合成数据的理论理解：反瓶颈视角

发布时间：2024年10月02日

`LLM理论` `人工智能` `数据科学`

> Towards a Theoretical Understanding of Synthetic Data in LLM Post-Training: A Reverse-Bottleneck Perspective

# 摘要

> 合成数据因高质量、特定数据的稀缺性，已成为 LLM 训练后任务的关键资源。尽管生成方法多样，但实际效果与理论理解间仍有差距。为此，我们首先详细建模了合成数据生成过程，并从反瓶颈角度分析，揭示了训练后模型泛化能力与生成模型信息增益的关键关系。此外，我们提出了通过互信息 (GGMI) 的泛化增益概念，阐明了其与信息增益的关联。这一理论分析不仅为合成数据生成奠定了基础，还揭示了其与模型泛化能力的紧密联系，为生成技术的设计和训练后过程的优化提供了新视角。代码已通过匿名 GitHub 仓库开源，地址为 https://anonymous.4open.science/r/Understanding-Synthetic。

> Synthetic data has become a pivotal resource in post-training tasks for large language models (LLMs) due to the scarcity of high-quality, specific data. While various methods have been developed to generate synthetic data, there remains a discernible gap between the practical effects of synthetic data and our theoretical comprehension. To address this challenge, we commence by presenting a detailed modeling of the prevalent synthetic data generation process. Building upon this modeling, we demonstrate that the generalization capability of the post-trained model is critically determined by the information gain derived from the generative model, as analyzed from a novel reverse-bottleneck perspective. Moreover, we introduce the concept of Generalization Gain via Mutual Information (GGMI) and elucidate the relationship between generalization gain and information gain. This analysis serves as a theoretical foundation for synthetic data generation and further highlights its connection with the generalization capability of post-trained models, offering an understanding about the design of synthetic data generation techniques and the optimization of the post-training process. We open source our code through an anonymous GitHub repository at https://anonymous.4open.science/r/Understanding-Synthetic.

[Arxiv](https://arxiv.org/abs/2410.01720)