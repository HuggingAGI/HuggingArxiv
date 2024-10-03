# 探究 RLHF 方法论

发布时间：2024年10月02日

`LLM理论` `人工智能`

> Investigating on RLHF methodology

# 摘要

> 本文探讨了大型语言模型如何根据人类偏好进行调整。我们详细介绍了训练模拟人类偏好的偏好模型的关键要素，以及实现最佳效果的方法。同时，我们还分享了使用强化学习微调大型语言模型的经验，包括遇到的挑战及解决方案。此外，我们引入了直接偏好优化方法，使模型无需独立偏好模型即可与人类偏好对齐。最后，我们提出了一种通过困惑度过滤收集偏好数据集的创新方法，大大简化了数据集创建过程并降低了成本。

> In this article, we investigate the alignment of Large Language Models according to human preferences. We discuss the features of training a Preference Model, which simulates human preferences, and the methods and details we found essential for achieving the best results. We also discuss using Reinforcement Learning to fine-tune Large Language Models and describe the challenges we faced and the ways to overcome them. Additionally, we present our experience with the Direct Preference Optimization method, which enables us to align a Large Language Model with human preferences without creating a separate Preference Model. As our contribution, we introduce the approach for collecting a preference dataset through perplexity filtering, which makes the process of creating such a dataset for a specific Language Model much easier and more cost-effective.

[Arxiv](https://arxiv.org/abs/2410.01789)