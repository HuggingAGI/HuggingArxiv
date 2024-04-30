# RedCoast：一款轻量级工具，旨在简化在各种 GPU 或 TPU 上进行大型语言模型的分布式训练过程。

发布时间：2024年02月08日

`LLM应用` `机器学习` `系统开发`

> RedCoast: A Lightweight Tool to Automate Distributed Training of LLMs on Any GPU/TPUs

# 摘要

> 人工智能的最新突破在很大程度上得益于大型语言模型（LLMs）的发展。但这些模型日益增长的内存需求对机器学习（ML）的研究者和工程师构成了挑战。为了应对这一挑战，开发者必须将大型模型拆分，以便跨多个GPU或TPU进行分配。这一过程需要开发者使用Megatron-LM、DeepSpeed和Apla等现有的模型并行工具进行大量的编程和复杂的配置。这些工具的使用需要用户具备深厚的机器学习系统（MLSys）知识，这在LLM的开发过程中，对于没有MLSys背景的开发者来说，无疑是一个难题。为了解决这一问题，我们开发了RedCoast（简称Redco），这是一个轻量级且易于使用的工具，它能够自动化LLM的分布式训练和推理，并简化了ML流程的开发。Redco的设计突出了两个核心要素：首先，通过自动化模型并行化，我们的研究提出了两条简单的规则，为任何特定的LLM生成张量并行策略。将这些规则整合到Redco中，极大地简化了分布式LLM的训练和推理过程，无需额外编程或复杂配置。我们通过在GPT-J、LLaMA、T5和OPT等一系列LLM架构上应用Redco，证明了其有效性，这些模型的规模高达66B参数。其次，我们设计了一种机制，用户只需定义三个函数，即可定制多样化的ML流程，避免了编写冗长和刻板的多主机相关代码。这一机制在各种ML算法中都显示出了良好的适应性，从基础的语言模型到复杂的元学习和强化学习算法。因此，Redco的实现在代码行数上大大少于官方版本。

> The recent progress of AI can be largely attributed to large language models (LLMs). However, their escalating memory requirements introduce challenges for machine learning (ML) researchers and engineers. Addressing this requires developers to partition a large model to distribute it across multiple GPUs or TPUs. This necessitates considerable coding and intricate configuration efforts with existing model parallel tools, such as Megatron-LM, DeepSpeed, and Alpa. These tools require users' expertise in machine learning systems (MLSys), creating a bottleneck in LLM development, particularly for developers without MLSys background. In this work, we present RedCoast(Redco), a lightweight and user-friendly tool crafted to automate distributed training and inference for LLMs, as well as to simplify ML pipeline development. The design of Redco emphasizes two key aspects. Firstly, to automate model parallism, our study identifies two straightforward rules to generate tensor parallel strategies for any given LLM. Integrating these rules into Redco facilitates effortless distributed LLM training and inference, eliminating the need of additional coding or complex configurations. We demonstrate the effectiveness by applying Redco on a set of LLM architectures, such as GPT-J, LLaMA, T5, and OPT, up to the size of 66B. Secondly, we propose a mechanism that allows for the customization of diverse ML pipelines through the definition of merely three functions, avoiding redundant and formulaic code like multi-host related processing. This mechanism proves adaptable across a spectrum of ML algorithms, from foundational language modeling to complex algorithms like meta-learning and reinforcement learning. Consequently, Redco implementations exhibit much fewer code lines compared to their official counterparts.

[Arxiv](https://arxiv.org/abs/2310.16355)