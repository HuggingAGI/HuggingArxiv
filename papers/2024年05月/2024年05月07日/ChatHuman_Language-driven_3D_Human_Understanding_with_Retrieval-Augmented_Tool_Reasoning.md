# ChatHuman：借助检索增强的工具推理，实现语言驱动的3D人体理解在这项研究中，我们提出了ChatHuman，一个创新系统，它通过结合语言理解和检索增强的工具推理，实现了对3D人体的深入理解。该系统不仅能够处理复杂的语言指令，还能够利用检索机制来增强其推理能力，从而在3D人体建模和交互任务中展现出卓越的性能。

发布时间：2024年05月07日

`Agent

解释：这篇论文介绍了一个名为ChatHuman的系统，它是一个集成了多种方法技能的语言驱动人类理解系统。它通过微调大型语言模型（LLM）来智能选择并结合多种工具，以解决复杂问题并提升对人类的推理能力。这个系统可以被视为一个智能代理（Agent），因为它能够自主地选择和使用工具来完成任务。此外，它利用了检索增强生成技术（RAG）来生成学习示例，这表明它结合了RAG技术，但主要还是作为一个Agent来执行任务。因此，这篇论文更适合归类为Agent。` `人机交互` `智能辅助系统`

> ChatHuman: Language-driven 3D Human Understanding with Retrieval-Augmented Tool Reasoning

# 摘要

> 为了解决现有方法孤立工作的问题，我们开发了ChatHuman——一个集成了多种方法技能的语言驱动人类理解系统。通过微调LLM，ChatHuman能够智能选择并结合多种工具，以更精准地解决复杂问题，并提升对人类的推理能力。其创新之处在于，它利用学术文献指导3D人类工具的应用，采用检索增强生成技术为新工具生成学习示例，并通过整合工具结果深化对3D人类的理解。实验证明，ChatHuman在工具选择和多任务性能上均超越了现有模型，标志着我们向着构建一个统一、高效的人类分析系统迈出了重要一步。

> Numerous methods have been proposed to detect, estimate, and analyze properties of people in images, including the estimation of 3D pose, shape, contact, human-object interaction, emotion, and more. Each of these methods works in isolation instead of synergistically. Here we address this problem and build a language-driven human understanding system -- ChatHuman, which combines and integrates the skills of many different methods. To do so, we finetune a Large Language Model (LLM) to select and use a wide variety of existing tools in response to user inputs. In doing so, ChatHuman is able to combine information from multiple tools to solve problems more accurately than the individual tools themselves and to leverage tool output to improve its ability to reason about humans. The novel features of ChatHuman include leveraging academic publications to guide the application of 3D human-related tools, employing a retrieval-augmented generation model to generate in-context-learning examples for handling new tools, and discriminating and integrating tool results to enhance 3D human understanding. Our experiments show that ChatHuman outperforms existing models in both tool selection accuracy and performance across multiple 3D human-related tasks. ChatHuman is a step towards consolidating diverse methods for human analysis into a single, powerful, system for 3D human reasoning.

[Arxiv](https://arxiv.org/abs/2405.04533)