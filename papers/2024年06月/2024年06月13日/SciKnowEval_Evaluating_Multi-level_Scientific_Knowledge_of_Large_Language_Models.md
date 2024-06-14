# SciKnowEval：探究大型语言模型在多层次科学知识上的表现

发布时间：2024年06月13日

`LLM应用

这篇论文主要讨论了大型语言模型（LLMs）在科学研究中的应用，并提出了一个名为SciKnowEval的新基准来评估这些模型在科学知识理解和应用方面的能力。论文通过构建一个包含多级科学题目的数据集，并对比了多种LLMs的表现，强调了在科学领域中LLMs的评估和改进需求。因此，这篇论文更偏向于LLM的应用层面，而不是理论研究或Agent、RAG的特定领域。` `科学研究` `教育评估`

> SciKnowEval: Evaluating Multi-level Scientific Knowledge of Large Language Models

# 摘要

> 随着大型语言模型（LLMs）在科学研究中的广泛应用，我们需要更高级的基准来全面评估它们对科学知识的理解和应用能力。为此，我们推出了SciKnowEval基准，这是一个创新的评估框架，它通过五个递进的科学知识水平——广泛学习、深入探究、深刻思考、清晰辨别和勤奋实践——来系统地检验LLMs的能力。这些水平不仅考察了LLMs的知识广度和深度，还涉及了探究能力、推理能力、伦理安全意识及实践技能。我们以生物学和化学为例，构建了一个包含5万道多级科学题目的数据集。利用此数据集，我们对比了20款顶尖的开放源代码和专有LLMs，采用零-shot和少-shot提示策略。结果表明，尽管专有LLMs表现卓越，但在科学计算和应用方面仍有提升空间。我们相信SciKnowEval将成为科学领域LLMs评估的全面标准，并推动结合科学知识与高安全意识的LLMs的发展。相关数据集和代码已公开于https://github.com/hicai-zju/sciknoweval。

> The burgeoning utilization of Large Language Models (LLMs) in scientific research necessitates advanced benchmarks capable of evaluating their understanding and application of scientific knowledge comprehensively. To address this need, we introduce the SciKnowEval benchmark, a novel framework that systematically evaluates LLMs across five progressive levels of scientific knowledge: studying extensively, inquiring earnestly, thinking profoundly, discerning clearly, and practicing assiduously. These levels aim to assess the breadth and depth of scientific knowledge in LLMs, including knowledge coverage, inquiry and exploration capabilities, reflection and reasoning abilities, ethic and safety considerations, as well as practice proficiency. Specifically, we take biology and chemistry as the two instances of SciKnowEval and construct a dataset encompassing 50K multi-level scientific problems and solutions. By leveraging this dataset, we benchmark 20 leading open-source and proprietary LLMs using zero-shot and few-shot prompting strategies. The results reveal that despite achieving state-of-the-art performance, the proprietary LLMs still have considerable room for improvement, particularly in addressing scientific computations and applications. We anticipate that SciKnowEval will establish a comprehensive standard for benchmarking LLMs in science research and discovery, and promote the development of LLMs that integrate scientific knowledge with strong safety awareness. The dataset and code are publicly available at https://github.com/hicai-zju/sciknoweval .

![SciKnowEval：探究大型语言模型在多层次科学知识上的表现](../../../paper_images/2406.09098/x1.png)

![SciKnowEval：探究大型语言模型在多层次科学知识上的表现](../../../paper_images/2406.09098/x2.png)

[Arxiv](https://arxiv.org/abs/2406.09098)