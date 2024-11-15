# P-MMEval：一个用于对大型语言模型进行一致性评估的并行多语言多任务基准

发布时间：2024年11月13日

`LLM应用` `多语言模型`

> P-MMEval: A Parallel Multilingual Multitask Benchmark for Consistent Evaluation of LLMs

# 摘要

> 大型语言模型（LLM）的最新进展在诸如翻译、代码生成和推理等任务中展现出多样的多语言能力。以往的评估往往将范围局限于基础的自然语言处理（NLP）或孤立的特定能力任务。为克服这一缺陷，我们致力于推出一个全面的多语言多任务基准。首先，我们给出一个从众多基准中筛选可用且合理基准的流程，解决了先前工作中有关这些基准效用（即区分被评估模型的能力）的疏漏。借助这一流程，我们引入了 P-MMEval，这是一个涵盖有效基础和能力专项数据集的大规模基准。而且，P-MMEval 在各类数据集中实现了一致的语言覆盖，并提供了并行样本。最后，我们针对具有代表性的多语言模型系列开展了广泛实验，对模型间的性能进行比较，分析数据集的有效性，考察提示对模型性能的影响，探究多语言性能与任务、模型规模和语言等因素的关系。这些见解为未来的研究提供了宝贵的指引。该数据集可在 https://huggingface.co/datasets/Qwen/P-MMEval 获取。

> Recent advancements in large language models (LLMs) showcase varied multilingual capabilities across tasks like translation, code generation, and reasoning. Previous assessments often limited their scope to fundamental natural language processing (NLP) or isolated capability-specific tasks. To alleviate this drawback, we aim to present a comprehensive multilingual multitask benchmark. First, we present a pipeline for selecting available and reasonable benchmarks from massive ones, addressing the oversight in previous work regarding the utility of these benchmarks, i.e., their ability to differentiate between models being evaluated. Leveraging this pipeline, we introduce P-MMEval, a large-scale benchmark covering effective fundamental and capability-specialized datasets. Furthermore, P-MMEval delivers consistent language coverage across various datasets and provides parallel samples. Finally, we conduct extensive experiments on representative multilingual model series to compare performances across models, analyze dataset effectiveness, examine prompt impacts on model performances, and explore the relationship between multilingual performances and factors such as tasks, model sizes, and languages. These insights offer valuable guidance for future research. The dataset is available at https://huggingface.co/datasets/Qwen/P-MMEval.

[Arxiv](https://arxiv.org/abs/2411.09116)