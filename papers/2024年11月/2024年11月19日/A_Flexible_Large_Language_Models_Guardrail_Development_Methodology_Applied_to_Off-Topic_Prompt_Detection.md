# 一种适用于离题提示检测的灵活的大型语言模型防护栏开发方法

发布时间：2024年11月19日

`LLM应用` `语言模型` `安全防护`

> A Flexible Large Language Models Guardrail Development Methodology Applied to Off-Topic Prompt Detection

# 摘要

> 大型语言模型常有离题滥用的问题，用户可能让其执行超预期范围的任务。当下的防护栏常依赖精心挑选的示例或自定义分类器，存在误报率高、适应性差以及需要预生产中没有的真实数据等难题。本文引入了一种灵活且无需数据的防护栏开发方法来应对这些挑战。通过定性地全面定义问题空间并传递给大型语言模型生成多样提示，构建了合成数据集来测试和训练离题防护栏，效果优于启发式方法。另外，把任务设定为判别用户提示相对于系统提示是否相关，我们的防护栏能有效推广到其他滥用类别，如越狱和有害提示。最后，我们开源了合成数据集和离题防护栏模型，为预生产环境中防护栏的开发提供了宝贵资源，也为大型语言模型安全性的未来研究和开发助力。

> Large Language Models are prone to off-topic misuse, where users may prompt these models to perform tasks beyond their intended scope. Current guardrails, which often rely on curated examples or custom classifiers, suffer from high false-positive rates, limited adaptability, and the impracticality of requiring real-world data that is not available in pre-production. In this paper, we introduce a flexible, data-free guardrail development methodology that addresses these challenges. By thoroughly defining the problem space qualitatively and passing this to an LLM to generate diverse prompts, we construct a synthetic dataset to benchmark and train off-topic guardrails that outperform heuristic approaches. Additionally, by framing the task as classifying whether the user prompt is relevant with respect to the system prompt, our guardrails effectively generalize to other misuse categories, including jailbreak and harmful prompts. Lastly, we further contribute to the field by open-sourcing both the synthetic dataset and the off-topic guardrail models, providing valuable resources for developing guardrails in pre-production environments and supporting future research and development in LLM safety.

[Arxiv](https://arxiv.org/abs/2411.12946)