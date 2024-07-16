# DistillSeq：利用知识蒸馏技术，为大型语言模型设计的安全对齐测试框架

发布时间：2024年07月14日

`LLM应用` `人工智能` `网络安全`

> DistillSeq: A Framework for Safety Alignment Testing in Large Language Models using Knowledge Distillation

# 摘要

> 大型语言模型（LLM）在自然语言理解、翻译乃至代码生成等多个领域展现了非凡能力。然而，LLM 产生有害内容的风险不容忽视，这要求我们对其进行严格测试和全面评估，确保其安全且负责任地使用。但大规模测试 LLM 耗资巨大，因此，在测试阶段寻找节约成本的策略至关重要。我们的方法首先将审查知识从大型模型转移至小型模型，然后采用两种策略生成恶意查询：一是基于语法树的方法，二是利用 LLM 的方法。最后，我们设计了一个顺序过滤-测试流程，以识别易引发有毒反应的测试案例。研究显示，DistillSeq 在 GPT-3.5、GPT-4.0、Vicuna-13B 和 Llama-13B 上的应用，使得攻击成功率显著提升，平均增加了 93.0%。这表明 DistillSeq 在减少测试 LLM 所需时间和资源方面具有显著优势。

> Large Language Models (LLMs) have showcased their remarkable capabilities in diverse domains, encompassing natural language understanding, translation, and even code generation. The potential for LLMs to generate harmful content is a significant concern. This risk necessitates rigorous testing and comprehensive evaluation of LLMs to ensure safe and responsible use. However, extensive testing of LLMs requires substantial computational resources, making it an expensive endeavor. Therefore, exploring cost-saving strategies during the testing phase is crucial to balance the need for thorough evaluation with the constraints of resource availability. To address this, our approach begins by transferring the moderation knowledge from an LLM to a small model. Subsequently, we deploy two distinct strategies for generating malicious queries: one based on a syntax tree approach, and the other leveraging an LLM-based method. Finally, our approach incorporates a sequential filter-test process designed to identify test cases that are prone to eliciting toxic responses. Our research evaluated the efficacy of DistillSeq across four LLMs: GPT-3.5, GPT-4.0, Vicuna-13B, and Llama-13B. In the absence of DistillSeq, the observed attack success rates on these LLMs stood at 31.5% for GPT-3.5, 21.4% for GPT-4.0, 28.3% for Vicuna-13B, and 30.9% for Llama-13B. However, upon the application of DistillSeq, these success rates notably increased to 58.5%, 50.7%, 52.5%, and 54.4%, respectively. This translated to an average escalation in attack success rate by a factor of 93.0% when compared to scenarios without the use of DistillSeq. Such findings highlight the significant enhancement DistillSeq offers in terms of reducing the time and resource investment required for effectively testing LLMs.

![DistillSeq：利用知识蒸馏技术，为大型语言模型设计的安全对齐测试框架](../../../paper_images/2407.10106/x1.png)

![DistillSeq：利用知识蒸馏技术，为大型语言模型设计的安全对齐测试框架](../../../paper_images/2407.10106/x2.png)

![DistillSeq：利用知识蒸馏技术，为大型语言模型设计的安全对齐测试框架](../../../paper_images/2407.10106/x3.png)

![DistillSeq：利用知识蒸馏技术，为大型语言模型设计的安全对齐测试框架](../../../paper_images/2407.10106/x4.png)

[Arxiv](https://arxiv.org/abs/2407.10106)