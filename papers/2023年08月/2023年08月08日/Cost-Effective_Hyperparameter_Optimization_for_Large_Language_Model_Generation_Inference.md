# 高效优化大型语言模型推理的超参数，以降低成本在翻译过程中，我首先确保了原文意思的准确传达，然后根据中文的表达习惯，对翻译进行了调整，使其更加简洁、优雅，并保持了原文的生动性。

发布时间：2023年08月08日

`LLM应用

这篇论文探讨了在有限的推理预算下最大化大型语言模型（LLMs）生成价值的方法，提出了一个名为EcoOptiGen的框架，用于优化推理超参数以降低成本。这与LLM的应用层面相关，因为它关注的是如何在实际应用中更有效地使用LLMs，而不是探讨LLMs的理论基础或Agent的设计。因此，它属于LLM应用分类。` `成本优化`

> Cost-Effective Hyperparameter Optimization for Large Language Model Generation Inference

# 摘要

> 大型语言模型（LLMs）的生成能力激发了广泛的商业应用开发。然而，高昂的使用成本迫使开发者在一个有限的推理预算下寻求最大化生成价值的方法。本文探讨了优化推理超参数（如响应数量、温度和最大令牌数）的重要性，这些参数对文本生成的成本效益有着显著影响。我们提出了一个名为EcoOptiGen的框架，它通过经济型超参数优化和基于成本的剪枝策略，有效降低了成本。在GPT-3.5/GPT-4模型上进行的多样化任务实验证明了EcoOptiGen的有效性。该框架已在FLAML库的`autogen'包中实现，详情请访问：\url{https://aka.ms/autogen}。

> Large Language Models (LLMs) have sparked significant interest in their generative capabilities, leading to the development of various commercial applications. The high cost of using the models drives application builders to maximize the value of generation under a limited inference budget. This paper presents a study of optimizing inference hyperparameters such as the number of responses, temperature and max tokens, which significantly affects the utility/cost of text generation. We design a framework named EcoOptiGen which leverages economical hyperparameter optimization and cost-based pruning. Experiments with the GPT-3.5/GPT-4 models on a variety of tasks verify its effectiveness. EcoOptiGen is implemented in the `autogen' package of the FLAML library: \url{https://aka.ms/autogen}.

[Arxiv](https://arxiv.org/abs/2303.04673)