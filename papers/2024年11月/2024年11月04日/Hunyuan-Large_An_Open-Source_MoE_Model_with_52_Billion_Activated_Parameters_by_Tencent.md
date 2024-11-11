# Hunyuan-Large：腾讯的一个具有 520 亿激活参数的开源 MoE 模型

发布时间：2024年11月04日

`LLM应用` `模型开发`

> Hunyuan-Large: An Open-Source MoE Model with 52 Billion Activated Parameters by Tencent

# 摘要

> 在本文中，我们介绍了 Hunyuan-Large，它是目前最大的基于 Transformer 的开源专家混合模型，总共拥有 3890 亿个参数和 520 亿个激活参数，能够处理多达 256K 个标记。我们对 Hunyuan-Large 在包括语言理解和生成、逻辑推理、数学问题解决、编码、长上下文和聚合任务等各种基准上的卓越性能进行了全面评估，它的表现优于 LLama3.1-70B，与规模大得多的 LLama3.1-405B 模型相比也表现出相当的性能。Hunyuan-Large 的关键实践包括比以前文献中规模大几个数量级的大规模合成数据、混合专家路由策略、键值缓存压缩技术和专家特定的学习率策略。此外，我们还研究了专家混合模型的缩放定律和学习率计划，为未来的模型开发和优化提供了有价值的见解和指导。Hunyuan-Large 的代码和检查点已发布，以促进未来的创新和应用。  代码: https://github.com/Tencent/Hunyuan-Large  模型: https://huggingface.co/tencent/Tencent-Hunyuan-Large

> In this paper, we introduce Hunyuan-Large, which is currently the largest open-source Transformer-based mixture of experts model, with a total of 389 billion parameters and 52 billion activation parameters, capable of handling up to 256K tokens. We conduct a thorough evaluation of Hunyuan-Large's superior performance across various benchmarks including language understanding and generation, logical reasoning, mathematical problem-solving, coding, long-context, and aggregated tasks, where it outperforms LLama3.1-70B and exhibits comparable performance when compared to the significantly larger LLama3.1-405B model. Key practice of Hunyuan-Large include large-scale synthetic data that is orders larger than in previous literature, a mixed expert routing strategy, a key-value cache compression technique, and an expert-specific learning rate strategy. Additionally, we also investigate the scaling laws and learning rate schedule of mixture of experts models, providing valuable insights and guidances for future model development and optimization. The code and checkpoints of Hunyuan-Large are released to facilitate future innovations and applications.
  Codes: https://github.com/Tencent/Hunyuan-Large
Models: https://huggingface.co/tencent/Tencent-Hunyuan-Large

[Arxiv](https://arxiv.org/abs/2411.02265)