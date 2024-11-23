# 利用优化的样本计算分配来拓展 LLM 推理

发布时间：2024年10月29日

`LLM应用` `语言模型` `代码生成`

> Scaling LLM Inference with Optimized Sample Compute Allocation

# 摘要

> 采样是大型语言模型（LLMs）众多推理时算法的基础操作。要在有限计算量下高效地扩展推理，找到样本计算预算的最优分配极为关键：我们该采用何种采样配置（模型、温度、语言等）？每种配置应生成多少样本？我们将这些选择构建为一个学习问题，并提出 OSCA 算法，它通过寻找不同推理配置的最优组合来优化样本计算分配。我们的实验显示，凭借我们所学到的混合分配，在代码生成上，能以少 128 倍的计算量实现比最佳单一配置更优的准确性，在 4 个推理任务中以少 25 倍的计算量达成更好的准确性。OSCA 在单轮任务之外的智能体工作流中同样有效，在 SWE-Bench 上以比默认配置少 3 倍的计算量获得了更出色的准确性。我们的代码和生成内容已在 https://github.com/LeiLiLab/OSCA 发布。

> Sampling is a basic operation in many inference-time algorithms of large language models (LLMs). To scale up inference efficiently with a limited compute, it is crucial to find an optimal allocation for sample compute budgets: Which sampling configurations (model, temperature, language, etc.) do we use? How many samples do we generate in each configuration? We formulate these choices as a learning problem and propose OSCA, an algorithm that Optimizes Sample Compute Allocation by finding an optimal mix of different inference configurations. Our experiments show that with our learned mixed allocation, we can achieve accuracy better than the best single configuration with 128x less compute on code generation and 25x less compute on 4 reasoning tasks. OSCA is also shown to be effective in agentic workflows beyond single-turn tasks, achieving a better accuracy on SWE-Bench with 3x less compute than the default configuration. Our code and generations are released at https://github.com/LeiLiLab/OSCA.

[Arxiv](https://arxiv.org/abs/2410.22480)