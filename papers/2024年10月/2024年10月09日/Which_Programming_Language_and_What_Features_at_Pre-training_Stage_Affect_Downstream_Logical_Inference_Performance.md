# 预训练阶段，哪种编程语言及其特征最能提升下游逻辑推理的表现？

发布时间：2024年10月09日

`LLM理论` `软件开发` `人工智能`

> Which Programming Language and What Features at Pre-training Stage Affect Downstream Logical Inference Performance?

# 摘要

> 最新的大型语言模型在数学和逻辑推理任务中表现出色。研究表明，编程语言数据预训练的 LLM 具备强大的数学和推理能力，但这种因果关系尚未得到充分验证。我们的研究旨在探索哪些编程语言及其特征在预训练中影响逻辑推理性能。我们使用十种编程语言和三种自然语言数据集，在相同条件下从头开始预训练语言模型，并在逻辑推理任务上进行评估。结果显示，编程语言训练的模型在逻辑推理和指令遵循方面均优于自然语言训练的模型。进一步分析发现，抽象语法树的深度也影响推理性能。这些发现为提升 LLM 基础能力提供了关键见解。

> Recent large language models (LLMs) have demonstrated remarkable generalization abilities in mathematics and logical reasoning tasks. Prior research indicates that LLMs pre-trained with programming language data exhibit high mathematical and reasoning abilities; however, this causal relationship has not been rigorously tested. Our research aims to verify which programming languages and features during pre-training affect logical inference performance. Specifically, we pre-trained decoder-based language models from scratch using datasets from ten programming languages (e.g., Python, C, Java) and three natural language datasets (Wikipedia, Fineweb, C4) under identical conditions. Thereafter, we evaluated the trained models in a few-shot in-context learning setting on logical reasoning tasks: FLD and bAbi, which do not require commonsense or world knowledge. The results demonstrate that nearly all models trained with programming languages consistently outperform those trained with natural languages, indicating that programming languages contain factors that elicit logic inference performance. In addition, we found that models trained with programming languages exhibit a better ability to follow instructions compared to those trained with natural languages. Further analysis reveals that the depth of Abstract Syntax Trees representing parsed results of programs also affects logical reasoning performance. These findings will offer insights into the essential elements of pre-training for acquiring the foundational abilities of LLMs.

[Arxiv](https://arxiv.org/abs/2410.06735)