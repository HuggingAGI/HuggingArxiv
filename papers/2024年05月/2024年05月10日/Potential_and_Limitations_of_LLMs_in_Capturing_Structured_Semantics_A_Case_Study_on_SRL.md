# 大型语言模型在揭示结构化语义的奥秘上既有潜力也有限制，本研究以语义角色标注为切入点，深入探讨了这一议题。

发布时间：2024年05月10日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）在捕捉语言结构化语义方面的能力，特别是通过语义角色标注（SRL）任务来评估。它提出了一个名为PromptSRL的少样本SRL解析器，并分析了LLMs在处理语义结构任务时的性能和局限性。此外，论文还比较了LLMs与人类在错误上的重叠，这表明了LLMs在认知任务上的某些共性。这些内容更偏向于对LLMs理论能力的研究，因此归类为LLM理论。` `语义分析`

> Potential and Limitations of LLMs in Capturing Structured Semantics: A Case Study on SRL

# 摘要

> 大型语言模型（LLMs）在捕捉语言的结构化语义方面至关重要，有助于提升语言理解、增强解释性并减少偏见。然而，关于LLMs掌握结构化语义的能力，学术界仍争论不休。为此，我们提出以语义角色标注（SRL）为基石任务，探究LLMs在提取语义结构方面的潜能。我们采用提示方法，开发了少样本SRL解析器PromptSRL，它使LLMs能将自然语言转化为清晰的语义框架，为我们揭示LLMs的内在特性提供了一扇窗。我们的研究揭示了LLMs在捕捉语义结构方面的潜力，并指出规模扩大并非总能提升性能。同时，我们也注意到LLMs在处理C-论元等任务时的局限。令人惊讶的是，我们发现LLMs与未经训练的人类在错误上有高达30%的重叠，这表明两者在某些认知任务上存在共通之处。

> Large Language Models (LLMs) play a crucial role in capturing structured semantics to enhance language understanding, improve interpretability, and reduce bias. Nevertheless, an ongoing controversy exists over the extent to which LLMs can grasp structured semantics. To assess this, we propose using Semantic Role Labeling (SRL) as a fundamental task to explore LLMs' ability to extract structured semantics. In our assessment, we employ the prompting approach, which leads to the creation of our few-shot SRL parser, called PromptSRL. PromptSRL enables LLMs to map natural languages to explicit semantic structures, which provides an interpretable window into the properties of LLMs. We find interesting potential: LLMs can indeed capture semantic structures, and scaling-up doesn't always mirror potential. Additionally, limitations of LLMs are observed in C-arguments, etc. Lastly, we are surprised to discover that significant overlap in the errors is made by both LLMs and untrained humans, accounting for almost 30% of all errors.

[Arxiv](https://arxiv.org/abs/2405.06410)