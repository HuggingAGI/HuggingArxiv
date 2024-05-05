# Tryage：实时智能地将用户指令分发至大型语言模型

发布时间：2023年08月23日

`LLM应用` `机器学习` `软件开发`

> Tryage: Real-time, intelligent Routing of User Prompts to Large Language Models

# 摘要

> 自注意力机制的变革性引入催生了大量针对特定任务和数据领域的语言模型。Hugging Face 生态系统内超过二十万个模型让用户在挑选合适模型以适应多样化工作流程和数据领域时，面临计算、安全和时效性的挑战。目前急需机器学习框架，以减轻用户在选择和定制模型时的负担，充分释放庞大新兴模型库的潜力。我们提出了一个名为 Tryage 的上下文感知路由系统，它通过分析个别输入提示，利用语言模型路由器从模型库中优选专家模型。该系统灵感来源于大脑中的丘脑路由器，采用感知路由器预测下游模型在提示上的表现，并结合用户目标和通过标志（如模型大小、时效性）指定的约束，通过目标函数做出最优路由决策。Tryage 使用户能够在任务准确性和次要目标（如最小化模型大小、时效性、安全性、冗长性和可读性）之间进行权衡，探索最优解决方案。在涵盖代码、文本、临床数据和专利的多样化数据集上，Tryage 在动态模型选择上超越了 Gorilla 和 GPT3.5 turbo，准确率高达 50.9%，而 GPT 3.5 Turbo 为 23.6%，Gorilla 为 10.8%。Tryage 从概念上证明了路由模型如何应用于编程和控制多模型大型语言模型系统的行为，以最大化利用不断增长和演变的语言模型生态。

> The introduction of the transformer architecture and the self-attention mechanism has led to an explosive production of language models trained on specific downstream tasks and data domains. With over 200, 000 models in the Hugging Face ecosystem, users grapple with selecting and optimizing models to suit multifaceted workflows and data domains while addressing computational, security, and recency concerns. There is an urgent need for machine learning frameworks that can eliminate the burden of model selection and customization and unleash the incredible power of the vast emerging model library for end users. Here, we propose a context-aware routing system, Tryage, that leverages a language model router for optimal selection of expert models from a model library based on analysis of individual input prompts. Inspired by the thalamic router in the brain, Tryage employs a perceptive router to predict down-stream model performance on prompts and, then, makes a routing decision using an objective function that integrates performance predictions with user goals and constraints that are incorporated through flags (e.g., model size, model recency). Tryage allows users to explore a Pareto front and automatically trade-off between task accuracy and secondary goals including minimization of model size, recency, security, verbosity, and readability. Across heterogeneous data sets that include code, text, clinical data, and patents, the Tryage framework surpasses Gorilla and GPT3.5 turbo in dynamic model selection identifying the optimal model with an accuracy of 50.9% , compared to 23.6% by GPT 3.5 Turbo and 10.8% by Gorilla. Conceptually, Tryage demonstrates how routing models can be applied to program and control the behavior of multi-model LLM systems to maximize efficient use of the expanding and evolving language model ecosystem.

[Arxiv](https://arxiv.org/abs/2308.11601)