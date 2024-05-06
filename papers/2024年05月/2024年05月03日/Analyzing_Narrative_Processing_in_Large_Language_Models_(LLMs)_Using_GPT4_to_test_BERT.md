# 探索大型语言模型中的叙事处理能力：以 GPT-4 作为工具，对 BERT 进行测试分析

发布时间：2024年05月03日

`分类：LLM理论` `人工智能` `认知科学`

> Analyzing Narrative Processing in Large Language Models (LLMs): Using GPT4 to test BERT

# 摘要

> 人类凭借语言独有的能力来传递和接收复杂信息，这构成了传统、文化和多样化社交互动的基石。随着基于变换器的大型语言模型（LLMs）的问世，人类不再是唯一能够理解并创造语言的主体。本研究首次尝试将LLMs作为理解神经网络中语言处理机制的模型，以预测和提出关于人脑如何处理语言的假设。我们利用ChatGPT创作了十篇不同风格的伊索寓言变体，并将这些故事输入至开源的LLM BERT模型中。通过多维缩放和聚类分析，我们研究了BERT隐藏单元的激活模式。研究发现，BERT隐藏单元的激活向量更倾向于根据风格变化（在模型的前几层）而非叙事内容（在模型的后几层）进行聚类。BERT由12个相同的构建块堆叠而成，尽管这些构建块在大型文本语料库上进行了训练，但不同层却承担着不同的任务。这一发现为模拟人脑提供了有益的模型，其中大脑皮层的不同区域，即自相似结构，可以执行不同的功能，从而高效地处理语言。本研究的方法不仅有望揭开LLMs的神秘面纱，还可能为解析人类语言处理和认知的神经机制提供新的线索。

> The ability to transmit and receive complex information via language is unique to humans and is the basis of traditions, culture and versatile social interactions. Through the disruptive introduction of transformer based large language models (LLMs) humans are not the only entity to "understand" and produce language any more. In the present study, we have performed the first steps to use LLMs as a model to understand fundamental mechanisms of language processing in neural networks, in order to make predictions and generate hypotheses on how the human brain does language processing. Thus, we have used ChatGPT to generate seven different stylistic variations of ten different narratives (Aesop's fables). We used these stories as input for the open source LLM BERT and have analyzed the activation patterns of the hidden units of BERT using multi-dimensional scaling and cluster analysis. We found that the activation vectors of the hidden units cluster according to stylistic variations in earlier layers of BERT (1) than narrative content (4-5). Despite the fact that BERT consists of 12 identical building blocks that are stacked and trained on large text corpora, the different layers perform different tasks. This is a very useful model of the human brain, where self-similar structures, i.e. different areas of the cerebral cortex, can have different functions and are therefore well suited to processing language in a very efficient way. The proposed approach has the potential to open the black box of LLMs on the one hand, and might be a further step to unravel the neural processes underlying human language processing and cognition in general.

[Arxiv](https://arxiv.org/abs/2405.02024)