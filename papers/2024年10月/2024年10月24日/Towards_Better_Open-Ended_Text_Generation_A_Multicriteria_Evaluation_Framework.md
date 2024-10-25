# 迈向更好的开放式文本生成：一个多标准评估框架

发布时间：2024年10月24日

`LLM应用` `文本生成`

> Towards Better Open-Ended Text Generation: A Multicriteria Evaluation Framework

# 摘要

> 由于强大（大型）语言模型的兴起，开放式文本生成已成为自然语言处理中的一项突出任务。然而，评估这些模型的质量和所采用的解码策略仍然具有挑战性，因为在诸如连贯性、多样性和困惑度等广泛使用的指标之间存在权衡。解码方法往往在某些指标上表现出色，而在其他指标上表现不佳，这使得建立明确的排名变得复杂。在本文中，我们在这个多标准框架内提出了新的排名策略。具体来说，我们采用基于偏序的基准测试方法，并提出了一种新的综合指标，旨在平衡现有的自动指标，对文本生成质量提供更全面的评估。此外，我们讨论了这些方法与人类判断的一致性。我们的实验表明，所提出的方法为比较解码策略提供了一种可靠的方式，与人类偏好表现出相似性，并作为指导开放式文本生成任务模型选择的有价值工具。最后，我们为改进文本生成中的评估方法提出了未来的方向。我们的代码库、数据集和模型是公开可用的。

> Open-ended text generation has become a prominent task in natural language processing due to the rise of powerful (large) language models. However, evaluating the quality of these models and the employed decoding strategies remains challenging because of trade-offs among widely used metrics such as coherence, diversity, and perplexity. Decoding methods often excel in some metrics while underperforming in others, complicating the establishment of a clear ranking. In this paper, we present novel ranking strategies within this multicriteria framework. Specifically, we employ benchmarking approaches based on partial orderings and present a new summary metric designed to balance existing automatic indicators, providing a more holistic evaluation of text generation quality. Furthermore, we discuss the alignment of these approaches with human judgments. Our experiments demonstrate that the proposed methods offer a robust way to compare decoding strategies, exhibit similarities with human preferences, and serve as valuable tools in guiding model selection for open-ended text generation tasks. Finally, we suggest future directions for improving evaluation methodologies in text generation. Our codebase, datasets, and models are publicly available.

[Arxiv](https://arxiv.org/abs/2410.18653)