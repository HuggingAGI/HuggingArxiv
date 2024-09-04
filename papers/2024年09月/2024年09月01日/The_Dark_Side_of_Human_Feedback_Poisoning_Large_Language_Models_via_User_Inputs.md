# 人类反馈的阴暗面：用户输入如何毒害大型语言模型

发布时间：2024年09月01日

`LLM理论` `网络安全` `人工智能`

> The Dark Side of Human Feedback: Poisoning Large Language Models via User Inputs

# 摘要

> 大型语言模型（LLM）因其基于人类反馈的精细对齐过程，在自然语言处理领域表现卓越。然而，这种对齐技术虽提升了训练效率，却也为用户引导的中毒攻击提供了可乘之机。本文深入探讨了LLM训练流程中的潜在安全漏洞，揭示了一种通过用户提示实施的隐蔽且高效的中毒攻击。即便在未知目标模型的黑盒环境下，该攻击也能悄然改变奖励机制，影响特定关键词的模型表现，且不易被察觉。我们设计了两种恶意提示生成策略：一是选择性机制，诱导模型产生高奖励的有毒回应；二是生成性机制，通过优化前缀操控模型输出。实验表明，仅需少量恶意提示，特定触发词便能显著提升模型毒性评分。这一发现警示我们，无论采用何种奖励模型或基础语言模型，只要训练数据包含用户提示，LLM就可能面临隐蔽攻击的风险，且这种风险难以避免。

> Large Language Models (LLMs) have demonstrated great capabilities in natural language understanding and generation, largely attributed to the intricate alignment process using human feedback. While alignment has become an essential training component that leverages data collected from user queries, it inadvertently opens up an avenue for a new type of user-guided poisoning attacks. In this paper, we present a novel exploration into the latent vulnerabilities of the training pipeline in recent LLMs, revealing a subtle yet effective poisoning attack via user-supplied prompts to penetrate alignment training protections. Our attack, even without explicit knowledge about the target LLMs in the black-box setting, subtly alters the reward feedback mechanism to degrade model performance associated with a particular keyword, all while remaining inconspicuous. We propose two mechanisms for crafting malicious prompts: (1) the selection-based mechanism aims at eliciting toxic responses that paradoxically score high rewards, and (2) the generation-based mechanism utilizes optimizable prefixes to control the model output. By injecting 1\% of these specially crafted prompts into the data, through malicious users, we demonstrate a toxicity score up to two times higher when a specific trigger word is used. We uncover a critical vulnerability, emphasizing that irrespective of the reward model, rewards applied, or base language model employed, if training harnesses user-generated prompts, a covert compromise of the LLMs is not only feasible but potentially inevitable.

[Arxiv](https://arxiv.org/abs/2409.00787)