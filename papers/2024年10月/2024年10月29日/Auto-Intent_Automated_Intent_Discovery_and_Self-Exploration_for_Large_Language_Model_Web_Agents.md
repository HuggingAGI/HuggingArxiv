# Auto-Intent：针对大型语言模型网络代理的自动意图发现与自我探索

发布时间：2024年10月29日

`Agent` `网络导航` `人工智能`

> Auto-Intent: Automated Intent Discovery and Self-Exploration for Large Language Model Web Agents

# 摘要

> 在本文中，我们引入了 Auto-Intent 这一方法，它能让预训练的大型语言模型（LLM）无需直接微调就能成为目标领域的代理，我们的实践重点是网络导航任务。我们的方法先是以高度紧凑的形式（最多三个字），无监督地从目标领域的演示中挖掘出潜在意图。基于提取的意图，我们训练意图预测器，使其能依据代理过去的观察和行动来预测下一个意图。特别地，我们提出了一种自我探索方式，将前 k 个可能的意图预测作为预训练的 LLM 代理的提示，从而增强了决策能力。Auto-Intent 显著提升了 GPT-{3.5, 4} 和 Llama-3.1-{70B, 405B} 代理在 Mind2Web 的大规模真实网站导航基准和 WebArena 的在线导航任务中的表现，并实现了从 Mind2Web 到其他基准的跨基准泛化。

> In this paper, we introduce Auto-Intent, a method to adapt a pre-trained large language model (LLM) as an agent for a target domain without direct fine-tuning, where we empirically focus on web navigation tasks. Our approach first discovers the underlying intents from target domain demonstrations unsupervisedly, in a highly compact form (up to three words). With the extracted intents, we train our intent predictor to predict the next intent given the agent's past observations and actions. In particular, we propose a self-exploration approach where top-k probable intent predictions are provided as a hint to the pre-trained LLM agent, which leads to enhanced decision-making capabilities. Auto-Intent substantially improves the performance of GPT-{3.5, 4} and Llama-3.1-{70B, 405B} agents on the large-scale real-website navigation benchmarks from Mind2Web and online navigation tasks from WebArena with its cross-benchmark generalization from Mind2Web.

[Arxiv](https://arxiv.org/abs/2410.22552)