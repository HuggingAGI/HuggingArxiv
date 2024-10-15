# BlackDAN：一种黑盒多目标策略，专为有效且情境化的破解大型语言模型而设计。

发布时间：2024年10月13日

`LLM应用` `网络安全` `人工智能`

> BlackDAN: A Black-Box Multi-Objective Approach for Effective and Contextual Jailbreaking of Large Language Models

# 摘要

> 尽管 LLM 在多任务中表现出色，但仍面临越狱攻击等安全风险。现有策略多聚焦于攻击成功率，忽视了响应相关性和隐蔽性等关键因素。为此，我们推出了 BlackDAN，一个多目标优化的黑箱攻击框架。BlackDAN 利用 NSGA-II 算法，综合优化攻击成功率、隐蔽性和语义相关性，生成高质量且不易被检测的越狱提示。实验证明，BlackDAN 在提升攻击成功率和鲁棒性的同时，确保了响应的相关性和隐蔽性，超越了传统单一目标方法。

> While large language models (LLMs) exhibit remarkable capabilities across various tasks, they encounter potential security risks such as jailbreak attacks, which exploit vulnerabilities to bypass security measures and generate harmful outputs. Existing jailbreak strategies mainly focus on maximizing attack success rate (ASR), frequently neglecting other critical factors, including the relevance of the jailbreak response to the query and the level of stealthiness. This narrow focus on single objectives can result in ineffective attacks that either lack contextual relevance or are easily recognizable. In this work, we introduce BlackDAN, an innovative black-box attack framework with multi-objective optimization, aiming to generate high-quality prompts that effectively facilitate jailbreaking while maintaining contextual relevance and minimizing detectability. BlackDAN leverages Multiobjective Evolutionary Algorithms (MOEAs), specifically the NSGA-II algorithm, to optimize jailbreaks across multiple objectives including ASR, stealthiness, and semantic relevance. By integrating mechanisms like mutation, crossover, and Pareto-dominance, BlackDAN provides a transparent and interpretable process for generating jailbreaks. Furthermore, the framework allows customization based on user preferences, enabling the selection of prompts that balance harmfulness, relevance, and other factors. Experimental results demonstrate that BlackDAN outperforms traditional single-objective methods, yielding higher success rates and improved robustness across various LLMs and multimodal LLMs, while ensuring jailbreak responses are both relevant and less detectable.

[Arxiv](https://arxiv.org/abs/2410.09804)