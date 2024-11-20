# ACING：黑箱大型语言模型中用于指令学习的演员-评论家算法

发布时间：2024年11月19日

`LLM应用` `语言模型`

> ACING: Actor-Critic for Instruction Learning in Black-Box Large Language Models

# 摘要

> 大型语言模型（LLMs）解决任务的成效很大程度上取决于指令的质量，往往需要耗费大量人力进行微调，这凸显了自动指令优化的必要性。然而，面对模型参数和梯度不可获取的黑箱 LLMs，这种优化极具挑战。我们提出了 ACING，这是一种特定任务的提示优化方法，将其构建成无状态连续动作强化学习（RL）问题，即连续强盗设置。ACING 借助基于演员-评论家的方法来优化提示，从不可微的奖励信号中学习。我们通过在 30 个基于指令的任务上为 ChatGPT 优化提示来验证 ACING，它始终优于基线方法，中位数得分提升了 10 个百分点。此外，ACING 不但能追平甚至超越人工精心打造的专家指令，相较于人类基准，最高可提升 39 个百分点。

> The effectiveness of Large Language Models (LLMs) in solving tasks vastly depends on the quality of the instructions, which often require fine-tuning through extensive human effort. This highlights the need for automated instruction optimization; however, this optimization is particularly challenging when dealing with black-box LLMs, where model parameters and gradients remain inaccessible. We propose ACING, a task-specific prompt optimization approach framed as a stateless continuous-action Reinforcement Learning (RL) problem, known as the continuum bandit setting. ACING leverages an actor-critic-based method to optimize prompts, learning from non-differentiable reward signals. We validate ACING by optimizing prompts for ChatGPT on 30 instruction-based tasks. ACING consistently outperforms baseline methods, achieving a median score improvement of 10 percentage points. Furthermore, ACING not only recovers but also surpasses human-crafted expert instructions, achieving up to a 39 percentage point improvement against human benchmarks.

[Arxiv](https://arxiv.org/abs/2411.12736)