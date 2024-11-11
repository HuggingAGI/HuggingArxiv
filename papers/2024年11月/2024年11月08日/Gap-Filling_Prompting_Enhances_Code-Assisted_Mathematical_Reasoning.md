# 填空提示增强了代码辅助的数学推理。

发布时间：2024年11月08日

`LLM应用` `语言模型`

> Gap-Filling Prompting Enhances Code-Assisted Mathematical Reasoning

# 摘要

> 尽管大型语言模型（LLMs）在数学推理等任务中表现出色，但它们的实际应用受到高计算需求和专有限制的限制。思维链（CoT）和思维程序（PoT）微调是将LLM知识转移到小型语言模型（SLMs）的常见方法。然而，CoT在SLMs中经常导致计算错误，而PoT则显示出更大的潜力。虽然大多数基于PoT的方法侧重于直接的问题到代码转换或仅从问题中提取关键信息，然后为其提供代码解决方案，但这项工作强调填补问题中的空白，以清晰地说明解决方案路径，当此类信息未明确提供时，SLM可能难以理解。因此，本文介绍了填补空白提示（GFP），这是一种新颖的两步提示策略，旨在增强SLMs的问题解决过程。第一步识别这些空白并提供填补它们的提示，而第二步将提示添加到问题中以生成最终的代码解决方案。在两个基准数据集上的实验结果表明，GFP显著提高了SLMs的数学推理能力。

> Despite the strong performance of large language models (LLMs) in tasks like mathematical reasoning, their practical use is limited by high computational demands and proprietary restrictions. Chain-of-thought (CoT) and program-of-thought (PoT) fine-tuning are common methods to transfer LLM knowledge to small language models (SLMs). However, CoT often leads to calculation errors in SLMs, while PoT has shown more promise. While most PoT-based approaches focus on direct problem-to-code conversion or extracting only the key information from questions and then providing code solution for it, this work emphasizes filling the gaps in the question to clearly illustrate the solution path, which can be challenging for an SLM to understand when such information is not explicitly provided. Therefore, this paper introduces Gap-Filling Prompting (GFP), a novel two-step prompting strategy designed to enhance the problem-solving process for SLMs. The first step identifies these gaps and provides hints for filling them, while the second step adds the hints to the question to generate a final code solution. Experimental results on two benchmark datasets demonstrate that GFP significantly improves the mathematical reasoning abilities of SLMs.

[Arxiv](https://arxiv.org/abs/2411.05407)