# 摘要 2 附录：学术评论提升 LLM 的长上下文处理能力

发布时间：2024年11月07日

`LLM应用` `学术研究`

> Abstract2Appendix: Academic Reviews Enhance LLM Long-Context Capabilities

# 摘要

> 大型语言模型（LLMs）在各类任务中表现出色，然而处理长上下文阅读对它们而言仍具挑战。本研究探索借助高质量学术同行评审数据微调 LLMs 以提升其长上下文能力的成效。我们对直接偏好优化（DPO）方法和监督微调（SFT）方法加以比较，彰显了 DPO 的优势及数据效率。实验表明，仅用 2000 个样本，微调模型在 phi-3 上有 4.04 点的提升，在 Qasper 基准测试中提高了 2.6％。尽管存在数据规模和处理成本的限制，本研究凸显了 DPO 和高质量数据在推进 LLM 性能方面的潜力。
  另外，零样本基准测试结果显示，即便对于像 GPT-4o 这般强大的模型，聚合的高质量人类评论也远超 LLM 生成的响应。这意味着高质量人类评论在信息、推理和长上下文检索方面极为丰富，即便是最先进的模型也未完全具备这些能力。这些发现强调了利用人类评论进一步推动该领域发展的巨大作用。

> Large language models (LLMs) have shown remarkable performance across various tasks, yet their ability to handle long-context reading remains challenging. This study explores the effectiveness of leveraging high-quality academic peer review data for fine-tuning LLMs to enhance their long-context capabilities. We compare the Direct Preference Optimization (DPO) method with the Supervised Fine-Tuning (SFT) method, demonstrating DPO's superiority and data efficiency. Our experiments show that the fine-tuned model achieves a 4.04-point improvement over phi-3 and a 2.6\% increase on the Qasper benchmark using only 2000 samples. Despite facing limitations in data scale and processing costs, this study underscores the potential of DPO and high-quality data in advancing LLM performance.
  Additionally, the zero-shot benchmark results indicate that aggregated high-quality human reviews are overwhelmingly preferred over LLM-generated responses, even for the most capable models like GPT-4o. This suggests that high-quality human reviews are extremely rich in information, reasoning, and long-context retrieval, capabilities that even the most advanced models have not fully captured. These findings highlight the high utility of leveraging human reviews to further advance the field.

[Arxiv](https://arxiv.org/abs/2411.05232)