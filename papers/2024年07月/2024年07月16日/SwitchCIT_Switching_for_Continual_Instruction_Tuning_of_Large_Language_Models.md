# SwitchCIT：针对大型语言模型的持续指令调优进行智能切换

发布时间：2024年07月16日

`LLM理论` `人工智能`

> SwitchCIT: Switching for Continual Instruction Tuning of Large Language Models

# 摘要

> LLM 在通用语言理解等领域表现卓越，但针对特定指令任务的优化可能不足。持续指令调优是确保 LLM 适应新任务和领域的关键，从而在多样应用中保持其效用。然而，在连续任务训练中，模型可能遭遇灾难性遗忘，影响先前任务的性能。我们提出一种切换机制，通过参数高效调优模型来解决这一问题，并通过实验验证了其在不同自然语言生成任务中持续指令调优的有效性。

> Large language models (LLMs) have exhibited impressive capabilities in various domains, particularly in general language understanding. However these models, trained on massive text data, may not be finely optimized for specific tasks triggered by instructions. Continual instruction tuning is crucial to adapt LLMs to evolving tasks and domains, ensuring their effectiveness and relevance across a wide range of applications. In the context of continual instruction tuning, where models are sequentially trained on different tasks, catastrophic forgetting can occur, leading to performance degradation on previously learned tasks. This work addresses the catastrophic forgetting in continual instruction learning for LLMs through a switching mechanism for routing computations to parameter-efficient tuned models. We demonstrate the effectiveness of our method through experiments on continual instruction tuning of different natural language generation tasks.

![SwitchCIT：针对大型语言模型的持续指令调优进行智能切换](../../../paper_images/2407.11780/illustration_switch.jpg)

![SwitchCIT：针对大型语言模型的持续指令调优进行智能切换](../../../paper_images/2407.11780/forgeting_sft.png)

![SwitchCIT：针对大型语言模型的持续指令调优进行智能切换](../../../paper_images/2407.11780/forgeting_replay.png)

![SwitchCIT：针对大型语言模型的持续指令调优进行智能切换](../../../paper_images/2407.11780/forgeting_ours.png)

[Arxiv](https://arxiv.org/abs/2407.11780)