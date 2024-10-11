# StablePrompt：利用强化学习为大型语言模型自动优化提示词

发布时间：2024年10月10日

`Agent` `人工智能`

> StablePrompt: Automatic Prompt Tuning using Reinforcement Learning for Large Language Models

# 摘要

> 随着 LLM 的广泛应用，如何为特定任务找到合适的提示变得愈发关键。尽管强化学习 (RL) 常用于提示优化，但其不稳定性和环境依赖性限制了实际应用。为此，我们推出了 StablePrompt，该方法在训练稳定性和搜索空间之间找到了平衡，有效缓解了 RL 的不稳定性，并生成了高性能的提示。我们将提示调整视为代理与目标 LLM 之间的在线 RL 问题，并引入了自适应近端策略优化 (APPO)。APPO 通过引入 LLM 锚模型，自适应地调整策略更新速率，从而在保留预训练 LLM 语言能力的同时，实现灵活的提示搜索。实验证明，StablePrompt 在文本分类、问答和文本生成等多项任务中均优于以往方法。代码已开源，详见 github。

> Finding appropriate prompts for the specific task has become an important issue as the usage of Large Language Models (LLM) has expanded. Reinforcement Learning (RL) is widely used for prompt tuning, but its inherent instability and environmental dependency make it difficult to use in practice. In this paper, we propose StablePrompt, which strikes a balance between training stability and search space, mitigating the instability of RL and producing high-performance prompts. We formulate prompt tuning as an online RL problem between the agent and target LLM and introduce Adaptive Proximal Policy Optimization (APPO). APPO introduces an LLM anchor model to adaptively adjust the rate of policy updates. This allows for flexible prompt search while preserving the linguistic ability of the pre-trained LLM. StablePrompt outperforms previous methods on various tasks including text classification, question answering, and text generation. Our code can be found in github.

[Arxiv](https://arxiv.org/abs/2410.07652)