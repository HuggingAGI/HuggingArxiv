# 大型语言模型最后一英里微调的强化学习，无需人类反馈

发布时间：2024年08月29日

`Agent` `人工智能`

> Reinforcement Learning without Human Feedback for Last Mile Fine-Tuning of Large Language Models

# 摘要

> 强化学习在预训练模型后，通过似然最大化预测文本中的下一个标记，然后将语言模型与人类偏好对齐。在特定领域部署前，模型常需在任务特定数据上进一步微调。由于最后一步缺乏人类偏好，通常采用似然最大化作为默认方法。然而，强化学习不仅有助于与人类导出的奖励函数对齐，还有其他优势。例如，似然最大化虽是一种模仿学习，仅在理想条件下训练模型，而强化学习则不限于最佳状态下的动作演示，而是在探索策略空间时训练模型应对多种场景。此外，强化学习还能训练模型避免不良动作，抑制竞争但低效的行为。本研究开发了一个基于强化学习的微调框架，旨在测试其性能提升效果。实验聚焦于抽象摘要，但该框架具有广泛适用性。与传统似然最大化相比，该框架在原始预测上取得了更佳结果。对于特定测试数据，通过后处理最大似然输出可弥合性能差距。尽管如此，该框架为模型优化开辟了新途径，尤其适用于后处理复杂或效果不佳的情况，并可扩展至更复杂的不良输出类别，如幻觉，进行惩罚和训练。

> Reinforcement learning is used to align language models with human preference signals after first pre-training the model to predict the next token of text within a large corpus using likelihood maximization. Before being deployed in a specific domain, models are often further fine-tuned on task specific data. Since human preferences are often unavailable for the last step, it is performed using likelihood maximization as that is the typical default method. However, reinforcement learning has other advantages besides facilitating alignment to a human derived reward function. For one, whereas likelihood maximization is a form of imitation learning in which the model is trained on what to do under ideal conditions, reinforcement learning is not limited to demonstrating actions just for optimally reached states and trains a model what to do under a range of scenarios as it explores the policy space. In addition, it also trains a model what not to do, suppressing competitive but poor actions. This work develops a framework for last-mile fine-tuning using reinforcement learning and tests whether it garners performance gains. The experiments center on abstractive summarization, but the framework is general and broadly applicable. Use of the procedure produced significantly better results than likelihood maximization when comparing raw predictions. For the specific data tested, the gap could be bridged by employing post-processing of the maximum likelihood outputs. Nonetheless, the framework offers a new avenue for model optimization in situations where post-processing may be less straightforward or effective, and it can be extended to include more complex classes of undesirable outputs to penalize and train against, such as hallucinations.

[Arxiv](https://arxiv.org/abs/2408.16753)