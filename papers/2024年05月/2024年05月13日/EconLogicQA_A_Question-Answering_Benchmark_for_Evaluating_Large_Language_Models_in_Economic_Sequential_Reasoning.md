# 经济逻辑问答：大型语言模型经济序列推理能力评估的问答基准

发布时间：2024年05月13日

`LLM应用

这篇论文介绍了一个名为 EconLogicQA 的新基准，专门设计来测试大型语言模型（LLMs）在经济学、商业和供应链管理领域内的顺序推理能力。这个基准的目的是评估模型在处理复杂经济逻辑时的表现，特别是它们如何识别和排序多个相互关联的事件。这与传统的基准测试不同，后者通常只关注单一事件的预测。EconLogicQA 数据集的创建和公开，以及对多个尖端 LLM 的评估结果，都表明了这项工作是针对 LLM 在特定应用场景下的性能评估，因此属于 LLM 应用分类。` `经济学` `商业智能`

> EconLogicQA: A Question-Answering Benchmark for Evaluating Large Language Models in Economic Sequential Reasoning

# 摘要

> 本文推出了EconLogicQA，一个专为检验大型语言模型（LLMs）在经济学、商业及供应链管理领域内顺序推理能力的严格基准。不同于传统基准仅预测单一事件，EconLogicQA挑战模型需识别并排序多个相互交织的事件，以揭示经济逻辑的复杂性。该基准包含自经济文章提炼的多事件场景，要求深入理解时间与逻辑事件的关联。我们通过详尽评估，证明EconLogicQA能准确评估LLM在经济环境中应对顺序复杂性的能力。本文详述了EconLogicQA数据集，并展示了在多个尖端LLM上的评估结果，为我们提供了关于它们在经济领域顺序推理能力的全面洞察。EconLogicQA数据集已公开于https://huggingface.co/datasets/yinzhu-quan/econ_logic_qa。

> In this paper, we introduce EconLogicQA, a rigorous benchmark designed to assess the sequential reasoning capabilities of large language models (LLMs) within the intricate realms of economics, business, and supply chain management. Diverging from traditional benchmarks that predict subsequent events individually, EconLogicQA poses a more challenging task: it requires models to discern and sequence multiple interconnected events, capturing the complexity of economic logics. EconLogicQA comprises an array of multi-event scenarios derived from economic articles, which necessitate an insightful understanding of both temporal and logical event relationships. Through comprehensive evaluations, we exhibit that EconLogicQA effectively gauges a LLM's proficiency in navigating the sequential complexities inherent in economic contexts. We provide a detailed description of EconLogicQA dataset and shows the outcomes from evaluating the benchmark across various leading-edge LLMs, thereby offering a thorough perspective on their sequential reasoning potential in economic contexts. Our benchmark dataset is available at https://huggingface.co/datasets/yinzhu-quan/econ_logic_qa.

[Arxiv](https://arxiv.org/abs/2405.07938)