# 大型语言模型是否解决了捷径学习问题？本文评估了这些模型在应对捷径挑战方面的表现。

发布时间：2024年10月17日

`LLM理论` `人工智能`

> Do LLMs Overcome Shortcut Learning? An Evaluation of Shortcut Challenges in Large Language Models

# 摘要

> 大型语言模型 (LLM) 在 NLP 任务中表现出色，但可能依赖数据集偏差作为预测捷径，从而影响其鲁棒性和泛化能力。本文介绍的 Shortcut Suite 测试套件，通过六种捷径类型、五种评估指标和四种提示策略，全面评估了捷径对 LLM 性能的影响。实验发现：1) LLM 在不同下游任务中对捷径的依赖程度不一，显著影响性能。2) 较大的 LLM 在零-shot 和 few-shot 提示下更易利用捷径。3) 链式思维提示有效减少捷径依赖，优于其他提示策略，而 few-shot 提示通常不如 zero-shot 提示。4) LLM 在包含捷径的数据集上常表现出过度自信。5) LLM 在充满捷径的数据集中解释质量较低，错误类型包括分散注意力、伪装理解和逻辑谬误。这些发现为评估 LLM 的鲁棒性和泛化提供了新视角，并指出了减轻捷径依赖的潜在方向。代码已开源，详见 \url {https://github.com/yyhappier/ShortcutSuite.git}。

> Large Language Models (LLMs) have shown remarkable capabilities in various natural language processing tasks. However, LLMs may rely on dataset biases as shortcuts for prediction, which can significantly impair their robustness and generalization capabilities. This paper presents Shortcut Suite, a comprehensive test suite designed to evaluate the impact of shortcuts on LLMs' performance, incorporating six shortcut types, five evaluation metrics, and four prompting strategies. Our extensive experiments yield several key findings: 1) LLMs demonstrate varying reliance on shortcuts for downstream tasks, significantly impairing their performance. 2) Larger LLMs are more likely to utilize shortcuts under zero-shot and few-shot in-context learning prompts. 3) Chain-of-thought prompting notably reduces shortcut reliance and outperforms other prompting strategies, while few-shot prompts generally underperform compared to zero-shot prompts. 4) LLMs often exhibit overconfidence in their predictions, especially when dealing with datasets that contain shortcuts. 5) LLMs generally have a lower explanation quality in shortcut-laden datasets, with errors falling into three types: distraction, disguised comprehension, and logical fallacy. Our findings offer new insights for evaluating robustness and generalization in LLMs and suggest potential directions for mitigating the reliance on shortcuts. The code is available at \url {https://github.com/yyhappier/ShortcutSuite.git}.

[Arxiv](https://arxiv.org/abs/2410.13343)