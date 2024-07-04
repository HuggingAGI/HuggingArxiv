# 评估大型语言模型的社会偏见，需借助多样化的提示手段。

发布时间：2024年07月03日

`LLM理论` `社会科学` `人工智能`

> Social Bias Evaluation for Large Language Models Requires Prompt Variations

# 摘要

> 警告：本文涉及刻板印象和偏见的内容。大型语言模型 (LLM) 存在显著的社会偏见，相关研究正努力准确评估并缓解这些偏见。以往研究通过下游任务提示来检测社会偏见的程度，但这些研究往往依赖于有限的提示类型。本文探讨了 LLM 在改变不同提示（包括任务指令、少样本示例及去偏提示）时的敏感性，并发现 LLM 对提示极为敏感，甚至影响模型在任务性能和社会偏见方面的排名。同时，提示设置中的偏见减少可能导致性能下降，而实例的模糊性也是 LLM 对提示敏感的原因之一。因此，我们建议采用多样化的提示来评估其对 LLM 社会偏见的影响。

> Warning: This paper contains examples of stereotypes and biases. Large Language Models (LLMs) exhibit considerable social biases, and various studies have tried to evaluate and mitigate these biases accurately. Previous studies use downstream tasks as prompts to examine the degree of social biases for evaluation and mitigation. While LLMs' output highly depends on prompts, previous studies evaluating and mitigating bias have often relied on a limited variety of prompts. In this paper, we investigate the sensitivity of LLMs when changing prompt variations (task instruction and prompt, few-shot examples, debias-prompt) by analyzing task performance and social bias of LLMs. Our experimental results reveal that LLMs are highly sensitive to prompts to the extent that the ranking of LLMs fluctuates when comparing models for task performance and social bias. Additionally, we show that LLMs have tradeoffs between performance and social bias caused by the prompts. Less bias from prompt setting may result in reduced performance. Moreover, the ambiguity of instances is one of the reasons for this sensitivity to prompts in advanced LLMs, leading to various outputs. We recommend using diverse prompts, as in this study, to compare the effects of prompts on social bias in LLMs.

[Arxiv](https://arxiv.org/abs/2407.03129)