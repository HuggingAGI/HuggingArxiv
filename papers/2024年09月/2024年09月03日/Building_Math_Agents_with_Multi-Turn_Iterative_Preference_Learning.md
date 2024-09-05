# 打造多轮迭代偏好学习的数学智能体

发布时间：2024年09月03日

`LLM应用` `人工智能`

> Building Math Agents with Multi-Turn Iterative Preference Learning

# 摘要

> 最新研究显示，结合外部工具如代码解释器并运用多轮链式思维推理，能显著提升大型语言模型的数学解题能力。尽管现有研究多聚焦于合成数据与监督微调，本文则探索直接偏好学习的互补路径，以期进一步提升模型效能。然而，传统直接偏好学习算法因设计初衷为单轮对话，未能充分应对多轮推理与工具整合的复杂挑战。为此，我们创新提出多轮直接偏好学习框架，该框架巧妙利用代码解释器反馈，并针对轨迹级偏好进行优化，具体实现包括多轮DPO与多轮KTO。通过在GSM8K与MATH数据集上运用增强提示集训练多种语言模型，我们验证了该框架的卓越成效。实验结果令人振奋：监督微调后的Gemma-1.1-it-7B模型，在GSM8K上性能跃升至83.9%，在MATH上提升至51.2%；而Gemma-2-it-9B模型，在GSM8K上达到86.3%，在MATH上亦攀升至54.5%。

> Recent studies have shown that large language models' (LLMs) mathematical problem-solving capabilities can be enhanced by integrating external tools, such as code interpreters, and employing multi-turn Chain-of-Thought (CoT) reasoning. While current methods focus on synthetic data generation and Supervised Fine-Tuning (SFT), this paper studies the complementary direct preference learning approach to further improve model performance. However, existing direct preference learning algorithms are originally designed for the single-turn chat task, and do not fully address the complexities of multi-turn reasoning and external tool integration required for tool-integrated mathematical reasoning tasks. To fill in this gap, we introduce a multi-turn direct preference learning framework, tailored for this context, that leverages feedback from code interpreters and optimizes trajectory-level preferences. This framework includes multi-turn DPO and multi-turn KTO as specific implementations. The effectiveness of our framework is validated through training of various language models using an augmented prompt set from the GSM8K and MATH datasets. Our results demonstrate substantial improvements: a supervised fine-tuned Gemma-1.1-it-7B model's performance increased from 77.5% to 83.9% on GSM8K and from 46.1% to 51.2% on MATH. Similarly, a Gemma-2-it-9B model improved from 84.1% to 86.3% on GSM8K and from 51.0% to 54.5% on MATH.

[Arxiv](https://arxiv.org/abs/2409.02392)