# GFlowNet 微调以实现数学推理任务中的多种正确解法

发布时间：2024年10月26日

`LLM应用`

> GFlowNet Fine-tuning for Diverse Correct Solutions in Mathematical Reasoning Tasks

# 摘要

> 数学推理问题堪称最具挑战性的问题之列，因为通常得理解基本定律才能解决。定律是通用的，可最终答案的推导会因处理问题的方式而异。训练大型语言模型（LLMs）时，学会生成多种解决方案的能力对于加快其在数学教育中的运用至关重要。为此，我们用生成流网络（GFlowNet）来训练 LLMs。和追求奖励最大化的强化学习（RL）不同，GFlowNet 微调旨在通过训练分布与奖励函数成正比的 LLM 来寻找多样的解决方案。在数值实验中，我们从准确性和多样性的角度评估了 GFlowNet 微调与奖励最大化的 RL。结果显示，GFlowNet 微调能从多样的中间推理步骤得出正确的最终答案，这表明替代解决方案的生成能力得到了提升。

> Mathematical reasoning problems are among the most challenging, as they typically require an understanding of fundamental laws to solve. The laws are universal, but the derivation of the final answer changes depending on how a problem is approached. When training large language models (LLMs), learning the capability of generating such multiple solutions is essential to accelerate their use in mathematical education. To this end, we train LLMs using generative flow network (GFlowNet). Different from reward-maximizing reinforcement learning (RL), GFlowNet fine-tuning seeks to find diverse solutions by training the LLM whose distribution is proportional to a reward function. In numerical experiments, we evaluate GFlowNet fine-tuning and reward-maximizing RL in terms of accuracy and diversity. The results show that GFlowNet fine-tuning derives correct final answers from diverse intermediate reasoning steps, indicating the improvement of the capability of alternative solution generation.

[Arxiv](https://arxiv.org/abs/2410.20147)