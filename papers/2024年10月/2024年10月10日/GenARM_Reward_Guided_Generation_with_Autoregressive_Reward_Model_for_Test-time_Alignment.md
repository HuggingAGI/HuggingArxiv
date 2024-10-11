# GenARM：自回归奖励模型引导的生成，专为测试时对齐设计

发布时间：2024年10月10日

`LLM理论` `人工智能`

> GenARM: Reward Guided Generation with Autoregressive Reward Model for Test-time Alignment

# 摘要

> 大型语言模型（LLM）虽然能力强大，但需与人类偏好精准对齐。传统方法通过微调模型来适应人类偏好，但成本高昂且需频繁更新以应对多样化的用户需求。测试时对齐方法则通过奖励模型（RM）引导冻结的LLM，无需重新训练。然而，现有方法依赖于评估完整响应的轨迹级RM，不适用于需从部分响应预测下一个令牌的自回归生成。为此，我们提出了GenARM，一种利用自回归奖励模型的新型测试时对齐方法，旨在高效预测下一个令牌奖励。理论证明，GenARM能在KL正则化强化学习框架内引导LLM达到传统RM的效果。实验显示，GenARM不仅超越了现有测试时对齐方法，还与训练时方法性能相当。此外，GenARM支持从弱到强的指导，使大型LLM与小型RM对齐，无需高昂的训练成本。它还支持多目标对齐，实时调整偏好维度，满足多样用户需求，无需重新训练。

> Large Language Models (LLMs) exhibit impressive capabilities but require careful alignment with human preferences. Traditional training-time methods finetune LLMs using human preference datasets but incur significant training costs and require repeated training to handle diverse user preferences. Test-time alignment methods address this by using reward models (RMs) to guide frozen LLMs without retraining. However, existing test-time approaches rely on trajectory-level RMs which are designed to evaluate complete responses, making them unsuitable for autoregressive text generation that requires computing next-token rewards from partial responses. To address this, we introduce GenARM, a test-time alignment approach that leverages the Autoregressive Reward Model--a novel reward parametrization designed to predict next-token rewards for efficient and effective autoregressive generation. Theoretically, we demonstrate that this parametrization can provably guide frozen LLMs toward any distribution achievable by traditional RMs within the KL-regularized reinforcement learning framework. Experimental results show that GenARM significantly outperforms prior test-time alignment baselines and matches the performance of training-time methods. Additionally, GenARM enables efficient weak-to-strong guidance, aligning larger LLMs with smaller RMs without the high costs of training larger models. Furthermore, GenARM supports multi-objective alignment, allowing real-time trade-offs between preference dimensions and catering to diverse user preferences without retraining.

[Arxiv](https://arxiv.org/abs/2410.08193)