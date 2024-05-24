# 隐式上下文学习探究

发布时间：2024年05月23日

`LLM应用

理由：这篇论文介绍了一种名为Implicit In-context Learning (I2CL)的新方法，旨在改进大型语言模型(LLMs)的In-context Learning (ICL)能力。I2CL通过在模型激活空间内融入演示示例来克服传统ICL的局限，并引入了“任务-ids”的新概念以提升任务相似性识别和促进有效的迁移学习。这种方法直接应用于LLMs的实际使用中，以提高其性能和鲁棒性，因此属于LLM应用类别。` `机器学习`

> Implicit In-context Learning

# 摘要

> In-context Learning (ICL) 通过在测试查询前添加演示示例，赋予大型语言模型 (LLMs) 在推理时适应新任务的能力。尽管ICL功能强大，但它相比零-shot学习带来了更多的计算和内存负担，且易受演示示例选择和顺序的影响。为此，我们提出了Implicit In-context Learning (I2CL)，一种创新方法，通过在模型激活空间内融入演示示例来克服传统ICL的局限。I2CL首先生成一个浓缩的上下文向量，然后在推理中通过将此向量与查询激活结合注入模型残差流来发挥作用。实证研究表明，I2CL在保持零-shot成本的同时达到了few-shot性能，并对演示示例的变化表现出鲁棒性。此外，I2CL引入了“任务-ids”的新概念，提升了任务相似性识别并促进了有效的迁移学习。我们深入分析了I2CL的机制及其对ICL领域的深远影响，并公开了源代码，详情请访问：https://github.com/LzVv123456/I2CL。

> In-context Learning (ICL) empowers large language models (LLMs) to adapt to unseen tasks during inference by prefixing a few demonstration examples prior to test queries. Despite its versatility, ICL incurs substantial computational and memory overheads compared to zero-shot learning and is susceptible to the selection and order of demonstration examples. In this work, we introduce Implicit In-context Learning (I2CL), an innovative paradigm that addresses the challenges associated with traditional ICL by absorbing demonstration examples within the activation space. I2CL first generates a condensed vector representation, namely a context vector, from the demonstration examples. It then integrates the context vector during inference by injecting a linear combination of the context vector and query activations into the model's residual streams. Empirical evaluation on nine real-world tasks across three model architectures demonstrates that I2CL achieves few-shot performance with zero-shot cost and exhibits robustness against the variation of demonstration examples. Furthermore, I2CL facilitates a novel representation of "task-ids", enhancing task similarity detection and enabling effective transfer learning. We provide a comprehensive analysis of I2CL, offering deeper insights into its mechanisms and broader implications for ICL. The source code is available at: https://github.com/LzVv123456/I2CL.

[Arxiv](https://arxiv.org/abs/2405.14660)