# 为视频大型语言模型（Video-LMMs）设计的一套复杂视频推理与鲁棒性评估工具。

发布时间：2024年05月06日

`LLM应用` `视频理解` `人工智能`

> Complex Video Reasoning and Robustness Evaluation Suite for Video-LMMs

# 摘要

> 近期大型语言模型（LLMs）的突破性进展催生了视频大型多模态模型（Video-LMMs），这些模型能够胜任多样化的视频理解任务，并有望应用于机器人、AI助理、医学影像和自动驾驶汽车等领域。Video-LMMs在日常生活中的日益普及凸显了评估其在模拟复杂现实世界环境中人类般的推理和交互能力的重要性。然而，目前的Video-LMMs评估标准多集中于基础视频理解，而忽略了对现实世界复杂视频推理能力及用户文本查询下模型鲁棒性的考量。本文提出了复杂视频推理与鲁棒性评估套件（CVRR-ES），这是一个全新的基准，全面检测Video-LMMs在11个真实世界视频维度的表现。我们测试了9种最新模型，包括开源和闭源版本，发现大多数Video-LMMs在处理复杂视频时面临鲁棒性和推理的挑战。基于深入分析，我们提出了一种无需训练的双重步骤上下文提示（DSCP）技术，以提升现有Video-LMMs的性能。我们的研究为开发下一代以人为本、具备更高鲁棒性和推理能力的AI系统提供了深刻见解。相关数据集和代码已在 https://mbzuai-oryx.github.io/CVRR-Evaluation-Suite/ 公开发布。

> Recent advancements in Large Language Models (LLMs) have led to the development of Video Large Multi-modal Models (Video-LMMs) that can handle a wide range of video understanding tasks. These models have the potential to be deployed in real-world applications such as robotics, AI assistants, medical imaging, and autonomous vehicles. The widespread adoption of Video-LMMs in our daily lives underscores the importance of ensuring and evaluating their robust performance in mirroring human-like reasoning and interaction capabilities in complex, real-world contexts. However, existing benchmarks for Video-LMMs primarily focus on general video comprehension abilities and neglect assessing their reasoning capabilities over complex videos in the real-world context, and robustness of these models through the lens of user prompts as text queries. In this paper, we present the Complex Video Reasoning and Robustness Evaluation Suite (CVRR-ES), a novel benchmark that comprehensively assesses the performance of Video-LMMs across 11 diverse real-world video dimensions. We evaluate 9 recent models, including both open-source and closed-source variants, and find that most of the Video-LMMs, {especially open-source ones,} struggle with robustness and reasoning when dealing with complex videos. Based on our analysis, we develop a training-free Dual-Step Contextual Prompting (DSCP) technique to enhance the performance of existing Video-LMMs. Our findings provide valuable insights for building the next generation of human-centric AI systems with advanced robustness and reasoning capabilities. Our dataset and code are publicly available at: https://mbzuai-oryx.github.io/CVRR-Evaluation-Suite/.

[Arxiv](https://arxiv.org/abs/2405.03690)