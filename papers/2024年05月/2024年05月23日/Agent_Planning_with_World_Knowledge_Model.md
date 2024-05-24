# 基于世界知识模型的智能代理规划

发布时间：2024年05月23日

`Agent

这篇论文主要探讨了如何通过引入参数化世界知识模型（WKM）来增强大型语言模型（LLMs）作为代理模型在执行交互式规划任务时的性能。论文中提到的WKM模仿人类心理模型，预先提供全局知识并在任务中动态更新局部知识，以优化代理规划。这种方法旨在减少试错和幻觉行动，增强代理对真实物理世界的理解。因此，这篇论文更符合Agent分类，因为它专注于改进和应用代理模型以更好地理解和规划真实世界任务。` `人工智能` `机器人技术`

> Agent Planning with World Knowledge Model

# 摘要

> 近期，大型语言模型（LLMs）作为代理模型在执行交互式规划任务方面取得了显著进展，但仍受限于对真实物理世界理解的不足，导致全球规划中盲目试错和局部规划中产生幻觉行动。为此，本文提出了参数化世界知识模型（WKM），模仿人类心理模型，预先提供全局知识，并在任务中动态更新局部知识，以优化代理规划。我们训练代理模型从专家和采样数据中自主学习，并利用WKM为全局和局部规划提供知识支持。实验证明，我们的方法在多个复杂数据集上超越了现有技术，有效减少了试错和幻觉行动，增强了代理对世界的理解。此外，我们还发现：1）我们的任务知识能有效泛化至新任务；2）即使较弱的WKM也能指导强大的代理模型；3）统一的WKM训练展现出广阔的发展前景。相关代码将公开于https://github.com/zjunlp/WKM。

> Recent endeavors towards directly using large language models (LLMs) as agent models to execute interactive planning tasks have shown commendable results. Despite their achievements, however, they still struggle with brainless trial-and-error in global planning and generating hallucinatory actions in local planning due to their poor understanding of the ''real'' physical world. Imitating humans' mental world knowledge model which provides global prior knowledge before the task and maintains local dynamic knowledge during the task, in this paper, we introduce parametric World Knowledge Model (WKM) to facilitate agent planning. Concretely, we steer the agent model to self-synthesize knowledge from both expert and sampled trajectories. Then we develop WKM, providing prior task knowledge to guide the global planning and dynamic state knowledge to assist the local planning. Experimental results on three complex real-world simulated datasets with three state-of-the-art open-source LLMs, Mistral-7B, Gemma-7B, and Llama-3-8B, demonstrate that our method can achieve superior performance compared to various strong baselines. Besides, we analyze to illustrate that our WKM can effectively alleviate the blind trial-and-error and hallucinatory action issues, providing strong support for the agent's understanding of the world. Other interesting findings include: 1) our instance-level task knowledge can generalize better to unseen tasks, 2) weak WKM can guide strong agent model planning, and 3) unified WKM training has promising potential for further development. Code will be available at https://github.com/zjunlp/WKM.

[Arxiv](https://arxiv.org/abs/2405.14205)