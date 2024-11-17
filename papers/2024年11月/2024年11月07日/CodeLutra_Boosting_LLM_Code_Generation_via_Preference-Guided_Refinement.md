# CodeLutra：借助偏好引导的优化来增强 LLM 代码生成能力

发布时间：2024年11月07日

`LLM应用` `代码生成` `软件开发`

> CodeLutra: Boosting LLM Code Generation via Preference-Guided Refinement

# 摘要

> 大型语言模型（LLMs）在代码生成领域进步显著，可常需大量资源，还易过度泛化，这就限制了其处理特定任务的效率。对较小的开源 LLMs 进行微调是个不错的选择；但因监督微调仅依赖正确的代码示例，所以通常会落后于前沿模型，限制了模型从自身错误中学习和应对各类编程挑战的能力。为填补这一空缺，我们推出了 CodeLutra 这一创新框架，它借助成功和失败的代码生成尝试来提升表现不佳的 LLMs。和传统微调不同，CodeLutra 运用迭代偏好学习机制来对比正确和错误的解决方案，还能最大程度提升正确代码出现的概率。经过持续的迭代优化，CodeLutra 让较小的 LLMs 在各类代码生成任务中能与 GPT-4 比肩甚至超越，且无需依赖海量外部数据集或更大的辅助模型。在一项颇具挑战的数据分析任务里，仅用 500 个样本就把 Llama-3-8B 的准确率从 28.2%提升至 48.6%，接近 GPT-4 的水平。这些成果彰显了 CodeLutra 在缩小开源和闭源模型差距方面的潜力，使其成为代码生成领域极具前景的方法。

> Large Language Models (LLMs) have significantly advanced code generation but often require substantial resources and tend to over-generalize, limiting their efficiency for specific tasks. Fine-tuning smaller, open-source LLMs presents a viable alternative; however, it typically lags behind cutting-edge models due to supervised fine-tuning's reliance solely on correct code examples, which restricts the model's ability to learn from its own mistakes and adapt to diverse programming challenges. To bridge this gap, we introduce CodeLutra, a novel framework that enhances low-performing LLMs by leveraging both successful and failed code generation attempts. Unlike conventional fine-tuning, CodeLutra employs an iterative preference learning mechanism to compare correct and incorrect solutions as well as maximize the likelihood of correct codes. Through continuous iterative refinement, CodeLutra enables smaller LLMs to match or surpass GPT-4's performance in various code generation tasks without relying on vast external datasets or larger auxiliary models. On a challenging data analysis task, using just 500 samples improved Llama-3-8B's accuracy from 28.2% to 48.6%, approaching GPT-4's performance. These results highlight CodeLutra's potential to close the gap between open-source and closed-source models, making it a promising approach in the field of code generation.

[Arxiv](https://arxiv.org/abs/2411.05199)