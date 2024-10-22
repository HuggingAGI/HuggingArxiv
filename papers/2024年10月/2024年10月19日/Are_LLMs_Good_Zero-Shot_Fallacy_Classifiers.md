# LLM 能否成为优秀的零-shot 谬误分类器？

发布时间：2024年10月19日

`LLM应用` `人工智能` `信息安全`

> Are LLMs Good Zero-Shot Fallacy Classifiers?

# 摘要

> 谬误是推理错误的论证，检测和分类谬误是防止误导信息和偏见决策的关键任务。现有分类器因依赖大量标注数据而限制了其泛化能力。本文探讨如何利用大型语言模型（LLM）进行零样本谬误分类。我们设计了多种单轮和多轮提示方案，通过提取、总结和思维链推理等指令，激发LLM的谬误识别能力。实验表明，LLM在零样本情况下表现出色，尤其在分布外场景和开放任务中超越了全样本基线。多轮提示方案尤其提升了小型LLM的性能。研究强调了零样本谬误分类的未来方向。代码和数据详见：https://github.com/panFJCharlotte98/Fallacy_Detection。

> Fallacies are defective arguments with faulty reasoning. Detecting and classifying them is a crucial NLP task to prevent misinformation, manipulative claims, and biased decisions. However, existing fallacy classifiers are limited by the requirement for sufficient labeled data for training, which hinders their out-of-distribution (OOD) generalization abilities. In this paper, we focus on leveraging Large Language Models (LLMs) for zero-shot fallacy classification. To elicit fallacy-related knowledge and reasoning abilities of LLMs, we propose diverse single-round and multi-round prompting schemes, applying different task-specific instructions such as extraction, summarization, and Chain-of-Thought reasoning. With comprehensive experiments on benchmark datasets, we suggest that LLMs could be potential zero-shot fallacy classifiers. In general, LLMs under single-round prompting schemes have achieved acceptable zero-shot performances compared to the best full-shot baselines and can outperform them in all OOD inference scenarios and some open-domain tasks. Our novel multi-round prompting schemes can effectively bring about more improvements, especially for small LLMs. Our analysis further underlines the future research on zero-shot fallacy classification. Codes and data are available at: https://github.com/panFJCharlotte98/Fallacy_Detection.

[Arxiv](https://arxiv.org/abs/2410.15050)