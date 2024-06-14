# RL-JACK：利用强化学习技术对大型语言模型发起的黑盒越狱攻击

发布时间：2024年06月12日

`Agent

理由：这篇论文主要介绍了一种新型的黑盒攻击方法RL-JACK，该方法利用深度强化学习（DRL）来生成越狱提示，以绕过大型语言模型（LLM）的安全措施。这种方法可以被视为一个智能代理（Agent），因为它通过学习策略来执行特定的任务（即生成越狱提示）。论文中提到的RL-JACK的设计和实验结果表明，它能够有效地对抗现有的安全措施，并在不同的LLM模型上展现出可转移性，这进一步强调了其作为智能代理的特性。因此，这篇论文更适合归类为Agent。` `人工智能`

> RL-JACK: Reinforcement Learning-powered Black-box Jailbreaking Attack against LLMs

# 摘要

> 现代大型语言模型（LLM）开发者常进行安全对齐，以防生成有害内容。然而，最新研究发现，通过精心设计的越狱提示，可以绕过这种安全措施，引导LLM回应有害问题。现有的越狱攻击方法因随机性而效率低下。为此，我们提出了一种名为RL-JACK的新型黑盒攻击，它利用深度强化学习（DRL）来生成越狱提示。我们将此过程视为搜索问题，并设计了专门的RL策略来解决。我们的方法特别设计了LLM辅助的动作空间和创新的奖励函数，以提高学习效率和越狱成功率。实验证明，RL-JACK在对抗六大SOTA LLM时表现出色，且能有效抵御多种防御措施，并展现出跨模型的可转移性。此外，RL-JACK对关键超参数的变化表现出良好的鲁棒性。

> Modern large language model (LLM) developers typically conduct a safety alignment to prevent an LLM from generating unethical or harmful content. Recent studies have discovered that the safety alignment of LLMs can be bypassed by jailbreaking prompts. These prompts are designed to create specific conversation scenarios with a harmful question embedded. Querying an LLM with such prompts can mislead the model into responding to the harmful question. The stochastic and random nature of existing genetic methods largely limits the effectiveness and efficiency of state-of-the-art (SOTA) jailbreaking attacks. In this paper, we propose RL-JACK, a novel black-box jailbreaking attack powered by deep reinforcement learning (DRL). We formulate the generation of jailbreaking prompts as a search problem and design a novel RL approach to solve it. Our method includes a series of customized designs to enhance the RL agent's learning efficiency in the jailbreaking context. Notably, we devise an LLM-facilitated action space that enables diverse action variations while constraining the overall search space. We propose a novel reward function that provides meaningful dense rewards for the agent toward achieving successful jailbreaking. Through extensive evaluations, we demonstrate that RL-JACK is overall much more effective than existing jailbreaking attacks against six SOTA LLMs, including large open-source models and commercial models. We also show the RL-JACK's resiliency against three SOTA defenses and its transferability across different models. Finally, we validate the insensitivity of RL-JACK to the variations in key hyper-parameters.

[Arxiv](https://arxiv.org/abs/2406.08725)