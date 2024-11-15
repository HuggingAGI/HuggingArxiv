# DAHL：借助生物医学中的基准数据集实现对长文本特定领域的自动幻觉评估

发布时间：2024年11月14日

`LLM应用` `生物医学`

> DAHL: Domain-specific Automated Hallucination Evaluation of Long-Form Text through a Benchmark Dataset in Biomedicine

# 摘要

> 我们推出了 DAHL，这是一套专为评估长文本生成中的幻觉现象而设计的基准数据集和自动化评估系统，尤其是在生物医学范畴。我们精心从生物医学研究论文中整理出的基准数据集涵盖 29 个类别，包含 8573 个问题。DAHL 把大型语言模型（LLM）的响应拆解为原子单元，每个单元代表一条信息，借此评估其中与事实冲突的幻觉。这些响应的准确率取均值得出 DAHL 分数，相比依赖多项选择任务的过往方法，能更深入地评估幻觉。我们用 8 种不同模型做实验，发现规模较大的模型幻觉倾向较小；但当模型规模超过 70 到 80 亿参数时，继续扩大规模对事实准确性的提升并不显著。DAHL 分数有望成为人工标注偏好标签的高效替代品，还能拓展到其他专业领域。我们已将数据集和代码公开。

> We introduce DAHL, a benchmark dataset and automated evaluation system designed to assess hallucination in long-form text generation, specifically within the biomedical domain. Our benchmark dataset, meticulously curated from biomedical research papers, consists of 8,573 questions across 29 categories. DAHL evaluates fact-conflicting hallucinations in Large Language Models (LLMs) by deconstructing responses into atomic units, each representing a single piece of information. The accuracy of these responses is averaged to produce the DAHL Score, offering a more in-depth evaluation of hallucinations compared to previous methods that rely on multiple-choice tasks. We conduct experiments with 8 different models, finding that larger models tend to hallucinate less; however, beyond a model size of 7 to 8 billion parameters, further scaling does not significantly improve factual accuracy. The DAHL Score holds potential as an efficient alternative to human-annotated preference labels, being able to be expanded to other specialized domains. We release the dataset and code in public.

[Arxiv](https://arxiv.org/abs/2411.09255)