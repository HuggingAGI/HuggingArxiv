# MEOW：利用反转事实的记忆监督，实现 LLM 的遗忘机制

发布时间：2024年09月18日

`LLM理论` `网络安全` `人工智能`

> MEOW: MEMOry Supervised LLM Unlearning Via Inverted Facts

# 摘要

> 大型语言模型（LLM）能记住敏感信息，引发滥用担忧。LLM Unlearning 作为一种事后解决方案，旨在移除这些信息，但面临三大挑战：效用损失、效率低下和鲁棒性不足。为此，我们提出 MEOW，一种基于梯度下降的简单有效方法。通过生成反转事实集，设计新度量 MEMO 量化记忆，并基于 MEMO 信号微调模型，MEOW 在遗忘质量上显著提升，且未显著影响模型效用。在 ToFU 基准测试中，MEOW 表现出色，不仅在 NLU 和 NLG 任务中保持稳定，甚至在 NLU 性能上略有提升。

> Large Language Models (LLMs) can memorize sensitive information, raising concerns about potential misuse. LLM Unlearning, a post-hoc approach to remove this information from trained LLMs, offers a promising solution to mitigate these risks. However, previous practices face three key challenges: 1. Utility: successful unlearning often causes catastrophic collapse on unrelated tasks. 2. Efficiency: many methods either involve adding similarly sized models, which slows down unlearning or inference, or require retain data that are difficult to obtain. 3. Robustness: even effective methods may still leak data via extraction techniques. To address these challenges, we propose MEOW, a simple yet effective gradient descent-based unlearning method. Specifically, we use an offline LLM to generate a set of inverted facts. Then, we design a new metric, MEMO, to quantify memorization in LLMs. Finally, based on the signals provided by MEMO, we select the most appropriate set of inverted facts and finetune the model based on them. We evaluate MEOW on the commonly used unlearn benchmark, ToFU, with Llama2-7B-Chat and Phi-1.5B, and test it on both NLU and NLG tasks. Results demonstrate significant improvement of MEOW in forget quality without substantial loss in model utility. Meanwhile, MEOW does not exhibit significant degradation in NLU or NLG capabilities, and there is even a slight improvement in NLU performance.

[Arxiv](https://arxiv.org/abs/2409.11844)