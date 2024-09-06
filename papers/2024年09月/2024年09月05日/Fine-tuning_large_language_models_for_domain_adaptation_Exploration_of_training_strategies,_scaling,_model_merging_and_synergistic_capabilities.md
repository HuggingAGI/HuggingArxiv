# 微调大型语言模型以适应特定领域：深入探讨训练策略、模型扩展、合并技术及其协同效应

发布时间：2024年09月05日

`LLM应用` `材料科学` `生物材料`

> Fine-tuning large language models for domain adaptation: Exploration of training strategies, scaling, model merging and synergistic capabilities

# 摘要

> 大型语言模型（LLM）在材料科学和工程等领域的应用，依赖于能够使模型适应专业技术能力的微调策略。我们研究了继续预训练（CPT）、监督微调（SFT）以及直接偏好优化（DPO）和赔率比偏好优化（ORPO）等方法对微调LLM性能的影响。分析表明，这些策略如何影响模型表现，并发现合并多个微调模型能产生超越单个模型的新能力。实验包括Llama 3.1 8B和Mistral 7B等不同架构，观察到类似现象。我们还测试了1.7亿参数的小型LLM，发现其在模型合并下不一定具备涌现能力，暗示模型规模可能是关键。在人机聊天中，最小模型在推理、创造力等方面表现出色。此外，我们还基于生物材料设计概念开发了图像生成提示，用于创建新型微结构和建筑设计。

> The advancement of Large Language Models (LLMs) for domain applications in fields such as materials science and engineering depends on the development of fine-tuning strategies that adapt models for specialized, technical capabilities. In this work, we explore the effects of Continued Pretraining (CPT), Supervised Fine-Tuning (SFT), and various preference-based optimization approaches, including Direct Preference Optimization (DPO) and Odds Ratio Preference Optimization (ORPO), on fine-tuned LLM performance. Our analysis shows how these strategies influence model outcomes and reveals that the merging of multiple fine-tuned models can lead to the emergence of capabilities that surpass the individual contributions of the parent models. We find that model merging leads to new functionalities that neither parent model could achieve alone, leading to improved performance in domain-specific assessments. Experiments with different model architectures are presented, including Llama 3.1 8B and Mistral 7B models, where similar behaviors are observed. Exploring whether the results hold also for much smaller models, we use a tiny LLM with 1.7 billion parameters and show that very small LLMs do not necessarily feature emergent capabilities under model merging, suggesting that model scaling may be a key component. In open-ended yet consistent chat conversations between a human and AI models, our assessment reveals detailed insights into how different model variants perform and show that the smallest model achieves a high intelligence score across key criteria including reasoning depth, creativity, clarity, and quantitative precision. Other experiments include the development of image generation prompts based on disparate biological material design concepts, to create new microstructures, architectural concepts, and urban design based on biological materials-inspired construction principles.

[Arxiv](https://arxiv.org/abs/2409.03444)