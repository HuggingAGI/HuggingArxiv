# 实现稳健即插即用适应的解耦对齐策略

发布时间：2024年06月03日

`LLM理论

理由：这篇论文探讨了通过知识蒸馏技术提升大型语言模型（LLM）的安全性的方法，这是一种理论上的探索和创新，涉及到模型内部机制的调整和优化，而不是直接的应用或特定的Agent或RAG框架。因此，它更适合归类于LLM理论分类。` `人工智能安全` `模型优化`

> Decoupled Alignment for Robust Plug-and-Play Adaptation

# 摘要

> 我们开发了一种创新方法，通过知识蒸馏技术，无需传统的监督微调或人类反馈强化学习，即可提升大型语言模型的安全性。该方法从已对齐的模型中提取关键信息，并灵活地应用于未对齐模型中。通过精细的差异调试，我们确定了知识蒸馏中的关键要素。在有害问题数据集的测试中，这种方法在不牺牲性能的前提下，显著提升了17个未对齐模型的防御成功率，平均提高了约14.41%，最高可达51.39%。

> We introduce a low-resource safety enhancement method for aligning large language models (LLMs) without the need for supervised fine-tuning (SFT) or reinforcement learning from human feedback (RLHF). Our main idea is to exploit knowledge distillation to extract the alignment information from existing well-aligned LLMs and integrate it into unaligned LLMs in a plug-and-play fashion. Methodology, we employ delta debugging to identify the critical components of knowledge necessary for effective distillation. On the harmful question dataset, our method significantly enhances the average defense success rate by approximately 14.41%, reaching as high as 51.39%, in 17 unaligned pre-trained LLMs, without compromising performance.

![实现稳健即插即用适应的解耦对齐策略](../../../paper_images/2406.01514/x1.png)

![实现稳健即插即用适应的解耦对齐策略](../../../paper_images/2406.01514/x2.png)

![实现稳健即插即用适应的解耦对齐策略](../../../paper_images/2406.01514/x3.png)

![实现稳健即插即用适应的解耦对齐策略](../../../paper_images/2406.01514/x5.png)

![实现稳健即插即用适应的解耦对齐策略](../../../paper_images/2406.01514/x6.png)

![实现稳健即插即用适应的解耦对齐策略](../../../paper_images/2406.01514/x7.png)

[Arxiv](https://arxiv.org/abs/2406.01514)