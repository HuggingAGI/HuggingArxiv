# RL-JACK：利用强化学习技术对大型语言模型发起的黑盒越狱攻击

发布时间：2024年06月12日

`Agent

这篇论文主要探讨了如何通过一种名为RL-JACK的新型黑盒攻击方法，利用深度强化学习（DRL）来生成越狱提示，以绕过大型语言模型（LLM）的安全对齐。这种方法将越狱过程视为一个搜索问题，并采用创新的RL策略来解决。因此，这篇论文更偏向于描述一个Agent（智能体）如何通过学习和策略优化来执行特定任务（即生成越狱提示），而不是专注于LLM的理论研究或应用。同时，它也不属于RAG（Retrieval-Augmented Generation）的范畴，因为RAG通常指的是一种结合了检索和生成能力的模型架构，而这里讨论的是一种攻击方法。` `网络安全` `人工智能安全`

> RL-JACK: Reinforcement Learning-powered Black-box Jailbreaking Attack against LLMs

# 摘要

> 现代大型语言模型（LLM）开发者为防止生成不道德或有害内容，通常会进行安全对齐。然而，最新研究发现，通过精心设计的越狱提示，可以绕过这种安全对齐。这些提示构建了包含有害问题的对话场景，从而误导LLM回应这些问题。现有的越狱攻击方法因其随机性而效率低下。为此，我们提出了一种名为RL-JACK的新型黑盒攻击方法，它利用深度强化学习（DRL）来生成越狱提示。我们将此过程视为一个搜索问题，并采用创新的RL策略来解决。我们的方法特别设计了LLM辅助的动作空间和新型奖励函数，以提高学习效率并实现成功的越狱。实验证明，RL-JACK在对抗包括开源和商业模型在内的六个SOTA LLM时，效果显著优于现有方法。此外，RL-JACK展现出对多种防御措施的韧性，并能在不同模型间转移。我们还验证了该方法对关键超参数变化的稳健性。

> Modern large language model (LLM) developers typically conduct a safety alignment to prevent an LLM from generating unethical or harmful content. Recent studies have discovered that the safety alignment of LLMs can be bypassed by jailbreaking prompts. These prompts are designed to create specific conversation scenarios with a harmful question embedded. Querying an LLM with such prompts can mislead the model into responding to the harmful question. The stochastic and random nature of existing genetic methods largely limits the effectiveness and efficiency of state-of-the-art (SOTA) jailbreaking attacks. In this paper, we propose RL-JACK, a novel black-box jailbreaking attack powered by deep reinforcement learning (DRL). We formulate the generation of jailbreaking prompts as a search problem and design a novel RL approach to solve it. Our method includes a series of customized designs to enhance the RL agent's learning efficiency in the jailbreaking context. Notably, we devise an LLM-facilitated action space that enables diverse action variations while constraining the overall search space. We propose a novel reward function that provides meaningful dense rewards for the agent toward achieving successful jailbreaking. Through extensive evaluations, we demonstrate that RL-JACK is overall much more effective than existing jailbreaking attacks against six SOTA LLMs, including large open-source models and commercial models. We also show the RL-JACK's resiliency against three SOTA defenses and its transferability across different models. Finally, we validate the insensitivity of RL-JACK to the variations in key hyper-parameters.

[Arxiv](https://arxiv.org/abs/2406.08725)