# 利用梯度优化技术，在大语言模型中探寻故障令牌的奥秘

发布时间：2024年10月19日

`LLM理论` `人工智能` `网络安全`

> Mining Glitch Tokens in Large Language Models via Gradient-based Discrete Optimization

# 摘要

> 大型语言模型中的故障令牌可能导致不可预测的行为，威胁模型的可靠性和安全性。现有检测方法多依赖手动观察，效率低下且难以适应不同模型架构。为此，我们推出了 GlitchMiner，一个基于梯度的离散优化框架，专为高效检测故障令牌而设计。GlitchMiner 通过基于熵的损失函数量化预测不确定性，并结合一阶泰勒近似与局部搜索策略，有效探索令牌空间。在多种主流 LLM 架构上的评估显示，GlitchMiner 在检测精度和适应性上均超越现有方法。相比之前的技术，GlitchMiner 在故障令牌检测的 precision@1000 上平均提升了 19.07%。GlitchMiner 不仅高效检测故障令牌，更为评估和缓解 LLM 潜在漏洞提供了有力工具，助力提升其整体安全性。

> Glitch tokens in Large Language Models (LLMs) can trigger unpredictable behaviors, compromising model reliability and safety. Existing detection methods often rely on manual observation to infer the prior distribution of glitch tokens, which is inefficient and lacks adaptability across diverse model architectures. To address these limitations, we introduce GlitchMiner, a gradient-based discrete optimization framework designed for efficient glitch token detection in LLMs. GlitchMiner leverages an entropy-based loss function to quantify the uncertainty in model predictions and integrates first-order Taylor approximation with a local search strategy to effectively explore the token space. Our evaluation across various mainstream LLM architectures demonstrates that GlitchMiner surpasses existing methods in both detection precision and adaptability. In comparison to the previous state-of-the-art, GlitchMiner achieves an average improvement of 19.07% in precision@1000 for glitch token detection. By enabling efficient detection of glitch tokens, GlitchMiner provides a valuable tool for assessing and mitigating potential vulnerabilities in LLMs, contributing to their overall security.

[Arxiv](https://arxiv.org/abs/2410.15052)