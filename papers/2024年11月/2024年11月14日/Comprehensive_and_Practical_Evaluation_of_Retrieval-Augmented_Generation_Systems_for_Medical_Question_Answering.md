# 针对医疗问答的检索增强生成系统的全面且实用的评估

发布时间：2024年11月14日

`RAG` `问答系统`

> Comprehensive and Practical Evaluation of Retrieval-Augmented Generation Systems for Medical Question Answering

# 摘要

> 检索增强生成（RAG）已成为提升大型语言模型（LLM）在医疗等知识密集型任务中的性能的有效途径。然而，医疗领域的敏感性要求系统必须完全准确且值得信赖。现有的 RAG 基准多聚焦于标准的检索-回答设定，却忽略了众多衡量可靠医疗系统关键方面的实际场景。本文针对此差距，为 RAG 环境下的医疗问答（QA）系统提供了一个涵盖充分性、集成性和鲁棒性的综合评估框架。我们推出了医疗检索增强生成基准（MedRGB），为四个医疗 QA 数据集补充了各类元素，用于测试 LLM 应对这些特定场景的能力。借助 MedRGB，我们在多种检索条件下对顶尖的商业 LLM 和开源模型展开了广泛评估。实验结果表明，当前模型处理检索文档中的噪声和错误信息的能力有限。我们进一步剖析了 LLM 的推理过程，为在这一关键医疗领域开发 RAG 系统提供了宝贵的见解和未来方向。

> Retrieval-augmented generation (RAG) has emerged as a promising approach to enhance the performance of large language models (LLMs) in knowledge-intensive tasks such as those from medical domain. However, the sensitive nature of the medical domain necessitates a completely accurate and trustworthy system. While existing RAG benchmarks primarily focus on the standard retrieve-answer setting, they overlook many practical scenarios that measure crucial aspects of a reliable medical system. This paper addresses this gap by providing a comprehensive evaluation framework for medical question-answering (QA) systems in a RAG setting for these situations, including sufficiency, integration, and robustness. We introduce Medical Retrieval-Augmented Generation Benchmark (MedRGB) that provides various supplementary elements to four medical QA datasets for testing LLMs' ability to handle these specific scenarios. Utilizing MedRGB, we conduct extensive evaluations of both state-of-the-art commercial LLMs and open-source models across multiple retrieval conditions. Our experimental results reveals current models' limited ability to handle noise and misinformation in the retrieved documents. We further analyze the LLMs' reasoning processes to provides valuable insights and future directions for developing RAG systems in this critical medical domain.

[Arxiv](https://arxiv.org/abs/2411.09213)