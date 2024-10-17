# 通过推理时的跨语言干预，弥合大型语言模型中的语言鸿沟

发布时间：2024年10月16日

`LLM应用` `跨语言技术`

> Bridging the Language Gaps in Large Language Models with Inference-Time Cross-Lingual Intervention

# 摘要

> 大型语言模型 (LLM) 在自然语言处理中表现出色，但在不同语言间存在显著性能差异。现有方法多依赖资源密集的预训练或微调。为此，我们提出推理时跨语言干预 (INCLINE)，通过在推理过程中对齐低性能语言与高性能语言的内部表示，提升 LLM 在低性能语言上的表现。INCLINE 首先通过最小二乘优化学习对齐矩阵，然后在推理时应用这些矩阵将低性能语言的表示转换为高性能语言的空间。实验表明，INCLINE 在多种任务和语言中显著优于现有基线，且成本效益高，适用范围广。我们还公开了代码，以推动相关研究：https://github.com/weixuan-wang123/INCLINE。

> Large Language Models (LLMs) have shown remarkable capabilities in natural language processing but exhibit significant performance gaps among different languages. Most existing approaches to address these disparities rely on pretraining or fine-tuning, which are resource-intensive. To overcome these limitations without incurring significant costs, we propose Inference-Time Cross-Lingual Intervention (INCLINE), a novel framework that enhances LLM performance on low-performing (source) languages by aligning their internal representations with those of high-performing (target) languages during inference. INCLINE initially learns alignment matrices using parallel sentences from source and target languages through a Least-Squares optimization, and then applies these matrices during inference to transform the low-performing language representations toward the high-performing language space. Extensive experiments on nine benchmarks with five LLMs demonstrate that INCLINE significantly improves performance across diverse tasks and languages, compared to recent strong baselines. Our analysis demonstrates that INCLINE is highly cost-effective and applicable to a wide range of applications. In addition, we release the code to foster research along this line: https://github.com/weixuan-wang123/INCLINE.

[Arxiv](https://arxiv.org/abs/2410.12462)