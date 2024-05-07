# 探究并衡量大型语言模型在不同规模和精度层面的性能表现

发布时间：2024年05月05日

`LLM理论` `机器学习`

> Quantifying the Capabilities of LLMs across Scale and Precision

# 摘要

> 规模被普遍认为是提升大型语言模型（LLMs）性能的关键因素，促使模型参数量从亿级跃升至万亿级。然而，这些庞然大物的高计算需求也限制了它们在资源紧张环境下的实用性、部署和故障排查。为了克服这一挑战，研究者们通常采用两种策略：一是转而使用较小型的LLMs（如7B参数的Llama代替70B参数的Llama）；二是通过量化技术降低内存需求。尽管这些方法在资源利用上取得了成效，但它们对模型性能的具体影响仍需深入探究。本研究全面评估了模型规模和量化技术对性能的影响，涉及从7亿到70亿参数的两大开源指令模型家族。通过在自然语言理解、推理、虚假信息识别和幻觉等多个任务上的广泛零样本实验，我们发现大型模型普遍优于小型模型，规模对于提升性能至关重要。我们还观察到，大型模型在精度降低时表现出惊人的韧性，即便在4位量化条件下，它们在众多任务上仍能保持高准确度，相比在相似内存需求下使用小型模型的高精确度方案，大型模型提供了更佳的解决策略。

> Scale is often attributed as one of the factors that cause an increase in the performance of LLMs, resulting in models with billion and trillion parameters. One of the limitations of such large models is the high computational requirements that limit their usage, deployment, and debugging in resource-constrained scenarios. Two commonly used alternatives to bypass these limitations are to use the smaller versions of LLMs (e.g. Llama 7B instead of Llama 70B) and lower the memory requirements by using quantization. While these approaches effectively address the limitation of resources, their impact on model performance needs thorough examination. In this study, we perform a comprehensive evaluation to investigate the effect of model scale and quantization on the performance. We experiment with two major families of open-source instruct models ranging from 7 billion to 70 billion parameters. Our extensive zero-shot experiments across various tasks including natural language understanding, reasoning, misinformation detection, and hallucination reveal that larger models generally outperform their smaller counterparts, suggesting that scale remains an important factor in enhancing performance. We found that larger models show exceptional resilience to precision reduction and can maintain high accuracy even at 4-bit quantization for numerous tasks and they serve as a better solution than using smaller models at high precision under similar memory requirements.

[Arxiv](https://arxiv.org/abs/2405.03146)