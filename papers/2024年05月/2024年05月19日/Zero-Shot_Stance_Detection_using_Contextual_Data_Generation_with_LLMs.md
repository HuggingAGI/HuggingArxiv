# 借助LLMs生成上下文数据，实现零-shot立场检测

发布时间：2024年05月19日

`LLM应用

这篇论文摘要主要描述了一种结合小样本学习和大型语言模型（如GPT-3）的方法，用于立场检测任务。该方法通过动态模型适应和上下文数据生成来解决标记数据稀缺的问题，并引入了新的数据集来帮助模型理解上下文与多主题间的关系。这种方法的应用性质明显，因此归类为LLM应用。` `假新闻检测` `意见挖掘`

> Zero-Shot Stance Detection using Contextual Data Generation with LLMs

# 摘要

> 立场检测是识别文本对特定主题的态度，对假新闻检测和意见挖掘等应用至关重要。但标记数据的稀缺性是一大难题。为此，我们开发了动态模型适应与上下文数据生成（DyMoAdapt），结合了小样本学习和大型语言模型。该方法在测试时对现有模型进行微调，利用GPT-3生成主题特定数据，使模型能适应新主题，从而提升性能。尽管结果未达预期，我们仍引入了多生成主题VAST（MGT-VAST）数据集，通过GPT-3扩展VAST，使每个上下文关联多个主题，帮助模型理解上下文与多主题间的关系。

> Stance detection, the classification of attitudes expressed in a text towards a specific topic, is vital for applications like fake news detection and opinion mining. However, the scarcity of labeled data remains a challenge for this task. To address this problem, we propose Dynamic Model Adaptation with Contextual Data Generation (DyMoAdapt) that combines Few-Shot Learning and Large Language Models. In this approach, we aim to fine-tune an existing model at test time. We achieve this by generating new topic-specific data using GPT-3. This method could enhance performance by allowing the adaptation of the model to new topics. However, the results did not increase as we expected. Furthermore, we introduce the Multi Generated Topic VAST (MGT-VAST) dataset, which extends VAST using GPT-3. In this dataset, each context is associated with multiple topics, allowing the model to understand the relationship between contexts and various potential topics

[Arxiv](https://arxiv.org/abs/2405.11637)