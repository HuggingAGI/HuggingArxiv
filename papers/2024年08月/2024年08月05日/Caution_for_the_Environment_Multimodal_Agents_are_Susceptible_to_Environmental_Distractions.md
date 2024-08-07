# 环境警报：多模态智能体易受外界干扰影响

发布时间：2024年08月05日

`Agent` `软件开发` `网络安全`

> Caution for the Environment: Multimodal Agents are Susceptible to Environmental Distractions

# 摘要

> 本文探讨了多模态大型语言模型 (MLLM) 在图形用户界面 (GUI) 环境中的可靠性，重点关注这些代理是否易受环境上下文干扰。我们设计了一种场景，用户和代理均为良性，环境虽非恶意但含无关内容。通过模拟数据集，我们评估了多种 MLLM 代理，发现即便是最先进的模型也易受干扰。尽管现有研究多聚焦于代理的行动准确性，我们的实验显示，这些代理极易因环境干扰而表现失常。进一步地，我们从对抗角度出发，通过环境注入实验，揭示了这种失常行为可能带来的潜在风险。

> This paper investigates the faithfulness of multimodal large language model (MLLM) agents in the graphical user interface (GUI) environment, aiming to address the research question of whether multimodal GUI agents can be distracted by environmental context. A general setting is proposed where both the user and the agent are benign, and the environment, while not malicious, contains unrelated content. A wide range of MLLMs are evaluated as GUI agents using our simulated dataset, following three working patterns with different levels of perception. Experimental results reveal that even the most powerful models, whether generalist agents or specialist GUI agents, are susceptible to distractions. While recent studies predominantly focus on the helpfulness (i.e., action accuracy) of multimodal agents, our findings indicate that these agents are prone to environmental distractions, resulting in unfaithful behaviors. Furthermore, we switch to the adversarial perspective and implement environment injection, demonstrating that such unfaithfulness can be exploited, leading to unexpected risks.

![环境警报：多模态智能体易受外界干扰影响](../../../paper_images/2408.02544/x1.png)

![环境警报：多模态智能体易受外界干扰影响](../../../paper_images/2408.02544/x2.png)

![环境警报：多模态智能体易受外界干扰影响](../../../paper_images/2408.02544/x3.png)

![环境警报：多模态智能体易受外界干扰影响](../../../paper_images/2408.02544/x4.png)

[Arxiv](https://arxiv.org/abs/2408.02544)