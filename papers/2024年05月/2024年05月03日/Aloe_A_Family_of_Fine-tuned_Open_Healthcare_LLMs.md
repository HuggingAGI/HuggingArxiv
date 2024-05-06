# Aloe：一套经过精细调整的开放医疗大型语言模型家族

发布时间：2024年05月03日

`LLM应用` `人工智能`

> Aloe: A Family of Fine-tuned Open Healthcare LLMs

# 摘要

> 随着大型语言模型（LLMs）在医疗领域的应用日益深入，对于能够维护公共福祉的开源模型的需求也日益迫切。面对日益增多的高竞争力开源基础模型，持续预训练的效果变得愈发不明确。本研究旨在探讨指导性微调、模型融合、模型对齐、对抗性测试和高级推理策略等手段，以提升现有开源模型的性能。我们特别推出了芦荟系列，这是一系列在规模上极具竞争力的开源医疗语言模型。这些模型基于当前顶尖的基础模型（Mistral和LLaMA 3）进行训练，并采用了结合了公共数据源和合成思维链（CoT）方法的全新定制数据集。芦荟模型经过对齐阶段，成为首批采用直接偏好优化进行政策对齐的开源医疗LLM，树立了医疗LLM伦理性能的新标杆。我们的模型评估不仅涵盖了多种偏见和毒性数据集，还包括了专门的对抗性测试和医疗LLM风险评估。此外，为了探究当前LLMs在推理方面的潜力，我们研究了多种先进的提示工程策略，以提升模型在各项基准测试中的表现，为开源医疗领域的7B规模LLMs取得了开创性的成绩。

> As the capabilities of Large Language Models (LLMs) in healthcare and medicine continue to advance, there is a growing need for competitive open-source models that can safeguard public interest. With the increasing availability of highly competitive open base models, the impact of continued pre-training is increasingly uncertain. In this work, we explore the role of instruct tuning, model merging, alignment, red teaming and advanced inference schemes, as means to improve current open models. To that end, we introduce the Aloe family, a set of open medical LLMs highly competitive within its scale range. Aloe models are trained on the current best base models (Mistral, LLaMA 3), using a new custom dataset which combines public data sources improved with synthetic Chain of Thought (CoT). Aloe models undergo an alignment phase, becoming one of the first few policy-aligned open healthcare LLM using Direct Preference Optimization, setting a new standard for ethical performance in healthcare LLMs. Model evaluation expands to include various bias and toxicity datasets, a dedicated red teaming effort, and a much-needed risk assessment for healthcare LLMs. Finally, to explore the limits of current LLMs in inference, we study several advanced prompt engineering strategies to boost performance across benchmarks, yielding state-of-the-art results for open healthcare 7B LLMs, unprecedented at this scale.

[Arxiv](https://arxiv.org/abs/2405.01886)