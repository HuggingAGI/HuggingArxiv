# 技能融合：探索数据优化策略，以精调大型语言模型

发布时间：2024年06月13日

`Agent

这篇论文介绍了一种名为技能混合（MoS）的强化学习框架，用于优化大型语言模型（LLMs）在微调过程中的数据使用，以确保技能发展的全面性。这种方法涉及到自动优化数据集的使用，以提升模型性能，并且还开发了一种针对特定任务的微调方法MoSpec。这些特性表明，该论文主要关注的是如何通过智能代理（Agent）来优化和控制LLMs的学习过程，因此将其归类为Agent。` `人工智能` `机器学习`

> Mixture-of-Skills: Learning to Optimize Data Usage for Fine-Tuning Large Language Models

# 摘要

> 大型语言模型（LLMs）通过在多样化的广泛数据集上进行微调，培养了包括写作、推理、聊天、编程在内的多种技能。每项技能各具特色，而数据集的异质性和不平衡性使得微调过程充满挑战。我们提出了一种名为技能混合（MoS）的强化学习框架，它能自动优化微调过程中的数据使用，确保LLMs技能发展的全面性。通过在两个广泛使用的基准上对三种LLM进行实验，我们证明了MoS能显著提升模型性能。此外，我们还开发了MoSpec，一种针对特定任务的微调方法，有效利用了多种数据集。我们的研究强调了数据集再平衡的重要性，并展示了MoS在优化LLMs微调中数据使用的通用解决方案。

> Large language models (LLMs) are typically fine-tuned on diverse and extensive datasets sourced from various origins to develop a comprehensive range of skills, such as writing, reasoning, chatting, coding, and more. Each skill has unique characteristics, and these datasets are often heterogeneous and imbalanced, making the fine-tuning process highly challenging. Balancing the development of each skill while ensuring the model maintains its overall performance requires sophisticated techniques and careful dataset curation. In this work, we propose a general, model-agnostic, reinforcement learning framework, Mixture-of-Skills (MoS), that learns to optimize data usage automatically during the fine-tuning process. This framework ensures the optimal comprehensive skill development of LLMs by dynamically adjusting the focus on different datasets based on their current learning state. To validate the effectiveness of MoS, we conduct extensive experiments using three diverse LLM backbones on two widely used benchmarks and demonstrate that MoS substantially enhances model performance. Building on the success of MoS, we propose MoSpec, an adaptation for task-specific fine-tuning, which harnesses the utilities of various datasets for a specific purpose. Our work underlines the significance of dataset rebalancing and present MoS as a powerful, general solution for optimizing data usage in the fine-tuning of LLMs for various purposes.

[Arxiv](https://arxiv.org/abs/2406.08811)