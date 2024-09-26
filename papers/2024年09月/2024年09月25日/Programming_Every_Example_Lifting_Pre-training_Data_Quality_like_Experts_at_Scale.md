# 精雕细琢每个示例：大规模提升预训练数据质量，如同专家般精准

发布时间：2024年09月25日

`LLM理论` `人工智能`

> Programming Every Example: Lifting Pre-training Data Quality like Experts at Scale

# 摘要

> 传统上，大型语言模型的预训练依赖于人类专家设计的启发式方法来提升语料库质量，但这些规则缺乏灵活性，难以应对每个示例的独特性。本文展示，即使是仅0.3B参数的小型模型，也能具备与人类专家相当的数据提炼能力。我们提出了“编程每个示例”（ProX）框架，将数据提炼视为编程任务，使模型能大规模生成和执行细粒度操作，如字符串归一化，从而提炼语料库。实验表明，ProX提炼的数据预训练模型在下游任务中表现优于原始数据和其他方法，提升超过2%。ProX不仅适用于多种模型和语料库，还在特定领域预训练中表现出色，无需特定设计，即可显著提升模型准确率。此外，ProX大幅节省训练计算量，为高效LLM预训练开辟了新路径。我们已开源ProX，包含超过100B语料库、模型及详细实现细节，助力可重复研究和创新。代码：https://github.com/GAIR-NLP/ProX

> Large language model pre-training has traditionally relied on human experts to craft heuristics for improving the corpora quality, resulting in numerous rules developed to date. However, these rules lack the flexibility to address the unique characteristics of individual example effectively. Meanwhile, applying tailored rules to every example is impractical for human experts. In this paper, we demonstrate that even small language models, with as few as 0.3B parameters, can exhibit substantial data refining capabilities comparable to those of human experts. We introduce Programming Every Example (ProX), a novel framework that treats data refinement as a programming task, enabling models to refine corpora by generating and executing fine-grained operations, such as string normalization, for each individual example at scale. Experimental results show that models pre-trained on ProX-curated data outperform either original data or data filtered by other selection methods by more than 2% across various downstream benchmarks. Its effectiveness spans various model sizes and pre-training corpora, including C4, RedPajama-V2, and FineWeb. Furthermore, ProX exhibits significant potential in domain-specific continual pre-training: without domain specific design, models trained on OpenWebMath refined by ProX outperform human-crafted rule-based methods, improving average accuracy by 7.6% over Mistral-7B, with 14.6% for Llama-2-7B and 20.3% for CodeLlama-7B, all within 10B tokens to be comparable to models like Llemma-7B trained on 200B tokens. Further analysis highlights that ProX significantly saves training FLOPs, offering a promising path for efficient LLM pre-training.We are open-sourcing ProX with >100B corpus, models, and sharing all training and implementation details for reproducible research and future innovation. Code: https://github.com/GAIR-NLP/ProX

[Arxiv](https://arxiv.org/abs/2409.17115)