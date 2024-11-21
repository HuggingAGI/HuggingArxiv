# SelfCodeAlign：代码生成的自对齐技术

发布时间：2024年10月31日

`LLM应用` `软件开发` `代码生成`

> SelfCodeAlign: Self-Alignment for Code Generation

# 摘要

> 指令微调是一种监督式微调方法，能大幅提升大型语言模型（LLMs）遵循人类指令的能力。我们提出了 SelfCodeAlign，这是首个完全透明且无需许可的管道，能在无需大量人工注释或提炼的情况下实现代码 LLMs 的自对齐。SelfCodeAlign 在整个数据生成过程中均使用相同的基础模型进行推理。它先是从高质量的种子片段中提取各类编码概念以生成新任务，接着为每个任务采样多个响应，将每个响应与测试用例配对，并在沙盒环境中进行验证，最后选取通过的示例用于指令微调。在我们的主要实验中，我们使用 SelfCodeAlign 与 CodeQwen1.5-7B 生成了一个包含 7.4 万个指令 - 响应对的数据集。基于此数据集进行微调得到的模型在 HumanEval+ 上实现了 67.1 的 pass@1，尽管规模小了十倍，但仍超越了 CodeLlama-70B-Instruct。在所有基准测试中，这个微调后的模型始终优于使用 OctoPack 训练的原始版本，OctoPack 是此前在无人工注释或提炼情况下用于指令微调的最先进方法。此外，我们表明 SelfCodeAlign 在 3B 至 33B 等各种规模的 LLMs 中均有效，且基础模型与自身数据分布对齐时能获益更多。我们进一步验证了管道中每个组件的有效性，发现 SelfCodeAlign 优于从 GPT-4o 直接提炼以及领先的基于 GPT-3.5 的提炼方法，如 OSS-Instruct 和 Evol-Instruct。SelfCodeAlign 还催生了 StarCoder2-Instruct，这是首个完全透明、许可开放且自对齐的代码 LLM，实现了顶尖的编码性能。

> Instruction tuning is a supervised fine-tuning approach that significantly improves the ability of large language models (LLMs) to follow human instructions. We propose SelfCodeAlign, the first fully transparent and permissive pipeline for self-aligning code LLMs without extensive human annotations or distillation. SelfCodeAlign employs the same base model for inference throughout the data generation process. It first extracts diverse coding concepts from high-quality seed snippets to generate new tasks. It then samples multiple responses per task, pairs each with test cases, and validates them in a sandbox environment. Finally, passing examples are selected for instruction tuning. In our primary experiments, we use SelfCodeAlign with CodeQwen1.5-7B to generate a dataset of 74k instruction-response pairs. Finetuning on this dataset leads to a model that achieves a 67.1 pass@1 on HumanEval+, surpassing CodeLlama-70B-Instruct despite being ten times smaller. Across all benchmarks, this finetuned model consistently outperforms the original version trained with OctoPack, the previous state-of-the-art method for instruction tuning without human annotations or distillation. Additionally, we show that SelfCodeAlign is effective across LLMs of various sizes, from 3B to 33B, and that the base models can benefit more from alignment with their own data distribution. We further validate each component's effectiveness in our pipeline, showing that SelfCodeAlign outperforms both direct distillation from GPT-4o and leading GPT-3.5-based distillation methods, such as OSS-Instruct and Evol-Instruct. SelfCodeAlign has also led to the creation of StarCoder2-Instruct, the first fully transparent, permissively licensed, and self-aligned code LLM that achieves state-of-the-art coding performance.

[Arxiv](https://arxiv.org/abs/2410.24198)