# 从人工针到真实干草堆：通过微调合成数据，提升大型语言模型的检索能力

发布时间：2024年06月27日

`LLM应用

这篇论文探讨了通过合成数据集微调大型语言模型（LLMs）以提高其在长上下文环境中的信息检索和推理能力。研究结果显示，特定的微调策略能够显著提升模型在实际任务中的表现，同时保持模型在通用基准测试中的稳定性。这种方法特别关注了数值键值检索任务，并展示了从合成任务到实际应用的良好技能转移。因此，这项工作属于LLM应用类别，因为它专注于实际应用中的模型性能改进。` `信息检索`

> From Artificial Needles to Real Haystacks: Improving Retrieval Capabilities in LLMs by Finetuning on Synthetic Data

# 摘要

> 最新研究表明，大型语言模型（LLMs）在处理长篇输入时，信息检索和推理能力面临挑战。为此，我们提出了一种基于合成数据集的微调策略，该数据集专为数值键值检索任务设计。实验结果显示，如GPT-3.5 Turbo和Mistral 7B等模型通过此数据集微调后，在长上下文环境中的信息检索和推理能力显著提升。我们进一步分析了这些微调模型的表现，发现它们在实际任务评估中展现出了从合成任务到实际应用的良好技能转移（例如，GPT-3.5 Turbo在处理20份文档的MDQA任务中，位置10的性能提升了10.5%）。同时，微调后的LLMs在通用基准测试中的表现保持稳定，而使用其他长上下文增强数据集的模型可能会出现性能下降，甚至产生幻觉（例如，在TriviaQA测试中，Mistral 7B微调我们的合成数据未见性能下降，而其他数据集可能导致性能下降2.33%至6.19%）。本研究凸显了通过合成数据微调提升LLMs在长上下文任务中性能的巨大潜力。

> Recent studies have shown that Large Language Models (LLMs) struggle to accurately retrieve information and maintain reasoning capabilities when processing long-context inputs. To address these limitations, we propose a finetuning approach utilizing a carefully designed synthetic dataset comprising numerical key-value retrieval tasks. Our experiments on models like GPT-3.5 Turbo and Mistral 7B demonstrate that finetuning LLMs on this dataset significantly improves LLMs' information retrieval and reasoning capabilities in longer-context settings. We present an analysis of the finetuned models, illustrating the transfer of skills from synthetic to real task evaluations (e.g., $10.5\%$ improvement on $20$ documents MDQA at position $10$ for GPT-3.5 Turbo). We also find that finetuned LLMs' performance on general benchmarks remains almost constant while LLMs finetuned on other baseline long-context augmentation data can encourage hallucination (e.g., on TriviaQA, Mistral 7B finetuned on our synthetic data cause no performance drop while other baseline data can cause a drop that ranges from $2.33\%$ to $6.19\%$). Our study highlights the potential of finetuning on synthetic data for improving the performance of LLMs on longer-context tasks.

[Arxiv](https://arxiv.org/abs/2406.19292)