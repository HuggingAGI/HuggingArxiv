# 不仅仅是准确性：计算机视觉损失在大型语言模型微调中的应用

发布时间：2024年09月20日

`LLM理论` `机器学习`

> Beyond Accuracy Optimization: Computer Vision Losses for Large Language Model Fine-Tuning

# 摘要

> LLM 在多任务中表现出色，但现有训练方法依赖于标准交叉熵损失、大量数据或人工反馈，这些方法成本高、复杂且资源密集。本研究探索了在自然语言生成中应用成熟的语义分割损失函数，旨在开发一种灵活、实用且可扩展的微调方案。实验表明，传统交叉熵损失并非最佳选择，而采用 Focal 或 Lovász 等替代损失函数的模型，在无需额外数据或人工干预的情况下，精确匹配率提升了 42%。这一发现为更高效、更易实现的训练方法开辟了新路径。

> Large Language Models (LLMs) have demonstrated impressive performance across various tasks. However, current training approaches combine standard cross-entropy loss with extensive data, human feedback, or ad hoc methods to enhance performance. These solutions are often not scalable or feasible due to their associated costs, complexity, or resource requirements. This study investigates the use of established semantic segmentation loss functions in natural language generation to create a versatile, practical, and scalable solution for fine-tuning different architectures. We evaluate their effectiveness in solving Math Word Problems and question answering across different models of varying sizes. For the analyzed tasks, we found that the traditional Cross-Entropy loss represents a sub-optimal choice, while models trained to minimize alternative (task-dependent) losses, such as Focal or Lovász, achieve a mean improvement of +42% on exact match without requiring additional data or human feedback. These findings suggest a promising pathway for more efficient and accessible training processes.

[Arxiv](https://arxiv.org/abs/2409.13641)