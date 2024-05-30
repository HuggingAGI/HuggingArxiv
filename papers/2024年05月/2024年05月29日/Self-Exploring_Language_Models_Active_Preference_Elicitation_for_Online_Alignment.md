# 语言模型的自我探索：通过主动偏好诱导实现在线对齐

发布时间：2024年05月29日

`LLM理论

理由：这篇论文探讨了通过人类反馈强化学习（RLHF）优化大型语言模型（LLMs）的方法，提出了自探索语言模型（SELM）算法，这是一种理论上的创新，旨在改进模型与人类意图的对齐。论文中提到的双层优化目标、重新参数化的奖励函数以及SELM算法的开发，都是对LLM理论的深入研究和贡献。此外，论文通过实验验证了SELM算法的有效性，并公开了相关代码和模型，这进一步证明了其理论性质。因此，这篇论文应归类于LLM理论。` `人工智能`

> Self-Exploring Language Models: Active Preference Elicitation for Online Alignment

# 摘要

> 通过人类反馈强化学习（RLHF）实现的偏好优化，成功地使大型语言模型（LLMs）与人类意图保持一致。不同于传统的离线对齐方法，通过收集人类或AI对模型输出的实时反馈，能够迭代地改进奖励模型和LLMs的对齐效果。然而，为了构建一个全面准确的奖励模型，需要系统性地探索自然语言的广阔领域，生成多样化的响应。仅依赖标准奖励最大化LLMs的随机抽样无法满足这一需求。为此，我们提出了一种双层优化目标，倾向于探索可能带来高奖励的响应，主动拓展分布外的探索区域。通过重新参数化的奖励函数解决内部优化问题，我们开发了自探索语言模型（SELM），该算法无需独立的奖励模型，而是通过直接目标迭代更新LLM。与直接偏好优化（DPO）相比，SELM减少了对外推的无差别偏好，提高了探索效率。实验证明，在Zephyr-7B-SFT和Llama-3-8B-Instruct模型上进行微调后，SELM在MT-Bench和AlpacaEval 2.0等指令遵循基准以及多种学术基准上均显著提升了性能。相关代码和模型已公开在https://github.com/shenao-zhang/SELM。

> Preference optimization, particularly through Reinforcement Learning from Human Feedback (RLHF), has achieved significant success in aligning Large Language Models (LLMs) to adhere to human intentions. Unlike offline alignment with a fixed dataset, online feedback collection from humans or AI on model generations typically leads to more capable reward models and better-aligned LLMs through an iterative process. However, achieving a globally accurate reward model requires systematic exploration to generate diverse responses that span the vast space of natural language. Random sampling from standard reward-maximizing LLMs alone is insufficient to fulfill this requirement. To address this issue, we propose a bilevel objective optimistically biased towards potentially high-reward responses to actively explore out-of-distribution regions. By solving the inner-level problem with the reparameterized reward function, the resulting algorithm, named Self-Exploring Language Models (SELM), eliminates the need for a separate RM and iteratively updates the LLM with a straightforward objective. Compared to Direct Preference Optimization (DPO), the SELM objective reduces indiscriminate favor of unseen extrapolations and enhances exploration efficiency. Our experimental results demonstrate that when finetuned on Zephyr-7B-SFT and Llama-3-8B-Instruct models, SELM significantly boosts the performance on instruction-following benchmarks such as MT-Bench and AlpacaEval 2.0, as well as various standard academic benchmarks in different settings. Our code and models are available at https://github.com/shenao-zhang/SELM.

![语言模型的自我探索：通过主动偏好诱导实现在线对齐](../../../paper_images/2405.19332/x1.png)

![语言模型的自我探索：通过主动偏好诱导实现在线对齐](../../../paper_images/2405.19332/zephyr_heatmap.png)

![语言模型的自我探索：通过主动偏好诱导实现在线对齐](../../../paper_images/2405.19332/llama3_heatmap.png)

![语言模型的自我探索：通过主动偏好诱导实现在线对齐](../../../paper_images/2405.19332/alpha_alpaca.png)

![语言模型的自我探索：通过主动偏好诱导实现在线对齐](../../../paper_images/2405.19332/reward_dist.png)

![语言模型的自我探索：通过主动偏好诱导实现在线对齐](../../../paper_images/2405.19332/reward_dist_shift.png)

![语言模型的自我探索：通过主动偏好诱导实现在线对齐](../../../paper_images/2405.19332/ird_chosen.png)

![语言模型的自我探索：通过主动偏好诱导实现在线对齐](../../../paper_images/2405.19332/ird_rejected.png)

![语言模型的自我探索：通过主动偏好诱导实现在线对齐](../../../paper_images/2405.19332/ablation_labelupdate.png)

![语言模型的自我探索：通过主动偏好诱导实现在线对齐](../../../paper_images/2405.19332/ablation_datasetupdate.png)

[Arxiv](https://arxiv.org/abs/2405.19332)