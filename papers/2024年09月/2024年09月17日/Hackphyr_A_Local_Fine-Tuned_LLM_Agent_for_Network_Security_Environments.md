# Hackphyr：专为网络安全环境定制的本地微调 LLM 代理

发布时间：2024年09月17日

`Agent` `网络安全` `人工智能`

> Hackphyr: A Local Fine-Tuned LLM Agent for Network Security Environments

# 摘要

> 大型语言模型 (LLM) 在网络安全等领域展现了巨大潜力，但基于商业云的 LLM 因隐私、成本和网络限制而不受欢迎。本文介绍的 Hackphyr 是一个本地微调的 LLM，专为网络安全环境中的红队代理设计。其 70 亿参数模型在单 GPU 上运行，性能媲美 GPT-4。Hackphyr 在复杂新场景中显著超越 GPT-3.5-turbo 和 Q-learning 代理。为提升性能，我们创建了新的网络安全数据集。最后，通过全面分析代理行为，揭示了其规划能力和潜在缺陷，深化了对网络安全中 LLM 代理的理解。

> Large Language Models (LLMs) have shown remarkable potential across various domains, including cybersecurity. Using commercial cloud-based LLMs may be undesirable due to privacy concerns, costs, and network connectivity constraints. In this paper, we present Hackphyr, a locally fine-tuned LLM to be used as a red-team agent within network security environments. Our fine-tuned 7 billion parameter model can run on a single GPU card and achieves performance comparable with much larger and more powerful commercial models such as GPT-4. Hackphyr clearly outperforms other models, including GPT-3.5-turbo, and baselines, such as Q-learning agents in complex, previously unseen scenarios. To achieve this performance, we generated a new task-specific cybersecurity dataset to enhance the base model's capabilities. Finally, we conducted a comprehensive analysis of the agents' behaviors that provides insights into the planning abilities and potential shortcomings of such agents, contributing to the broader understanding of LLM-based agents in cybersecurity contexts

[Arxiv](https://arxiv.org/abs/2409.11276)