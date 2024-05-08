# 代码智能之石：花岗岩系列开源基础模型在

发布时间：2024年05月07日

`LLM应用

这篇论文讨论了专门为代码生成任务设计的Granite系列大型语言模型（LLMs），这些模型在多项任务评估中表现出色，并且针对企业软件开发进行了优化。它们在代码生成、修复和解释等任务中表现卓越，因此被归类为LLM应用，因为它们展示了LLMs在特定应用领域（即软件开发）的实际应用和效果。这与Agent或RAG分类不符，因为论文没有特别关注代理行为或检索增强生成技术。同时，它也不属于LLM理论分类，因为它更多地关注模型的实际应用而非理论基础。` `软件开发` `编程语言

解释：根据论文摘要` `该研究涉及大型语言模型在代码生成、修复和解释等软件开发任务中的应用` `并且模型训练了多种编程语言` `因此标签为“软件开发”和“编程语言”。`

> Granite Code Models: A Family of Open Foundation Models for Code Intelligence

# 摘要

> 代码训练的大型语言模型（LLMs）正革新软件开发，它们被越来越多地融入开发环境，提升程序员效率，并开始自主处理复杂任务。Granite系列仅解码器的代码模型，专为代码生成任务设计，训练了116种编程语言，参数从3亿到340亿不等，适应各种场景。在多项任务评估中，Granite Code模型始终领先于其他开源代码LLMs。针对企业软件开发优化，Granite Code模型在代码生成、修复和解释等任务中表现卓越，成为一款全能代码模型。我们以Apache 2.0许可证发布，供研究和商业使用。

> Large Language Models (LLMs) trained on code are revolutionizing the software development process. Increasingly, code LLMs are being integrated into software development environments to improve the productivity of human programmers, and LLM-based agents are beginning to show promise for handling complex tasks autonomously. Realizing the full potential of code LLMs requires a wide range of capabilities, including code generation, fixing bugs, explaining and documenting code, maintaining repositories, and more. In this work, we introduce the Granite series of decoder-only code models for code generative tasks, trained with code written in 116 programming languages. The Granite Code models family consists of models ranging in size from 3 to 34 billion parameters, suitable for applications ranging from complex application modernization tasks to on-device memory-constrained use cases. Evaluation on a comprehensive set of tasks demonstrates that Granite Code models consistently reaches state-of-the-art performance among available open-source code LLMs. The Granite Code model family was optimized for enterprise software development workflows and performs well across a range of coding tasks (e.g. code generation, fixing and explanation), making it a versatile all around code model. We release all our Granite Code models under an Apache 2.0 license for both research and commercial use.

[Arxiv](https://arxiv.org/abs/2405.04324)