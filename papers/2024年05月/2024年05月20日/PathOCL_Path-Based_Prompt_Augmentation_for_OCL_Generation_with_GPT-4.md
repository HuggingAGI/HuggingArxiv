# PathOCL：利用 GPT-4，通过路径增强提示，精准生成 OCL

发布时间：2024年05月20日

`LLM应用

理由：这篇论文主要探讨了如何通过PathOCL技术优化大型语言模型（LLMs）在处理大型UML类模型时的性能，特别是在生成对象约束语言（OCL）方面的应用。论文关注的是LLMs在实际应用中的一个具体问题——令牌处理限制，并提出了一种解决方案。这与LLM的理论研究不同，因为它不涉及模型的基本理论或算法，而是关注于如何改进模型在特定任务上的应用。因此，这篇论文更适合归类为LLM应用。` `软件开发` `人工智能`

> PathOCL: Path-Based Prompt Augmentation for OCL Generation with GPT-4

# 摘要

> AI编程助手如GitHub Copilot的迅猛发展极大地推动了软件开发的进程。这些助手背后的力量是大型语言模型（LLMs），它们作为基础模型（FMs），支持着从语言理解到生成的多样化任务。LLMs已能运用如对象约束语言（OCL）等正式语言精准表达UML模型规范。但LLMs处理令牌的限制，使得提示的上下文大小受限，尤其当UML类模型规模增大时，这一限制愈发显著。为此，本研究推出了PathOCL，一种基于路径的提示增强技术，专门设计来优化OCL生成。PathOCL通过分块策略，精选与规范相关的UML类子集来增强提示，有效克服了LLMs的令牌处理限制及大型UML类模型带来的挑战。实验结果显示，相较于全面增强UML类模型（UML-Augmentation），PathOCL在使用GPT-4模型时，能生成更多有效且准确的OCL约束。更令人振奋的是，随着UML类模型规模的扩大，采用PathOCL的提示平均大小显著缩减。

> The rapid progress of AI-powered programming assistants, such as GitHub Copilot, has facilitated the development of software applications. These assistants rely on large language models (LLMs), which are foundation models (FMs) that support a wide range of tasks related to understanding and generating language. LLMs have demonstrated their ability to express UML model specifications using formal languages like the Object Constraint Language (OCL). However, the context size of the prompt is limited by the number of tokens an LLM can process. This limitation becomes significant as the size of UML class models increases. In this study, we introduce PathOCL, a novel path-based prompt augmentation technique designed to facilitate OCL generation. PathOCL addresses the limitations of LLMs, specifically their token processing limit and the challenges posed by large UML class models. PathOCL is based on the concept of chunking, which selectively augments the prompts with a subset of UML classes relevant to the English specification. Our findings demonstrate that PathOCL, compared to augmenting the complete UML class model (UML-Augmentation), generates a higher number of valid and correct OCL constraints using the GPT-4 model. Moreover, the average prompt size crafted using PathOCL significantly decreases when scaling the size of the UML class models.

[Arxiv](https://arxiv.org/abs/2405.12450)