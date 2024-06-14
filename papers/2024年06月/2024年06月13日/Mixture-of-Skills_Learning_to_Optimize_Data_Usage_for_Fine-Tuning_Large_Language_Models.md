# 技能融合：探索数据优化策略，以精调大型语言模型

发布时间：2024年06月13日

`LLM应用

这篇论文摘要描述了一个名为技能混合（MoS）框架的提出，该框架利用强化学习来自动优化数据使用，以确保大型语言模型（LLMs）在微调过程中能够动态调整学习重点，从而实现技能的全面发展。此外，论文还介绍了MoSpec，这是一种针对特定任务微调的方法，能够有效利用多源数据。这些内容主要关注于LLMs的实际应用和优化，特别是在微调过程中的数据使用和技能发展，因此属于LLM应用分类。` `人工智能` `机器学习`

> Mixture-of-Skills: Learning to Optimize Data Usage for Fine-Tuning Large Language Models

# 摘要

> 大型语言模型（LLMs）通过在多样化的数据集上微调，掌握了写作、推理、聊天、编程等多种技能。然而，这些数据集的异质性和不平衡性给微调带来了巨大挑战。我们提出的技能混合（MoS）框架，利用强化学习自动优化数据使用，确保LLMs在微调过程中动态调整学习重点，实现技能全面发展。实验证明，MoS在多个基准测试中显著提升了模型性能。此外，我们开发的MoSpec针对特定任务微调，有效利用了多源数据。本研究强调了数据集平衡的重要性，并展示了MoS在优化LLMs微调中的广泛应用潜力。

> Large language models (LLMs) are typically fine-tuned on diverse and extensive datasets sourced from various origins to develop a comprehensive range of skills, such as writing, reasoning, chatting, coding, and more. Each skill has unique characteristics, and these datasets are often heterogeneous and imbalanced, making the fine-tuning process highly challenging. Balancing the development of each skill while ensuring the model maintains its overall performance requires sophisticated techniques and careful dataset curation. In this work, we propose a general, model-agnostic, reinforcement learning framework, Mixture-of-Skills (MoS), that learns to optimize data usage automatically during the fine-tuning process. This framework ensures the optimal comprehensive skill development of LLMs by dynamically adjusting the focus on different datasets based on their current learning state. To validate the effectiveness of MoS, we conduct extensive experiments using three diverse LLM backbones on two widely used benchmarks and demonstrate that MoS substantially enhances model performance. Building on the success of MoS, we propose MoSpec, an adaptation for task-specific fine-tuning, which harnesses the utilities of various datasets for a specific purpose. Our work underlines the significance of dataset rebalancing and present MoS as a powerful, general solution for optimizing data usage in the fine-tuning of LLMs for various purposes.

[Arxiv](https://arxiv.org/abs/2406.08811)