# WISE：重塑大型语言模型终身编辑的知识记忆

发布时间：2024年05月23日

`LLM应用

这篇论文主要讨论了大型语言模型（LLMs）在知识更新方面的挑战，并提出了一种名为WISE的解决方案，用于有效地编辑和更新模型知识。论文中提到的WISE方案通过设计双参数记忆系统来解决模型编辑中的可靠性、泛化性和局部性问题，这对于LLMs的应用至关重要。因此，这篇论文更适合归类于LLM应用，因为它关注的是如何改进和应用LLMs以适应不断变化的知识需求，而不是专注于理论研究或Agent的设计与应用。` `人工智能` `模型编辑`

> WISE: Rethinking the Knowledge Memory for Lifelong Model Editing of Large Language Models

# 摘要

> 大型语言模型（LLMs）需不断更新知识，以适应日益增长的数据事实并修正错误响应，这促进了终身模型编辑技术的发展。模型编辑中的关键问题是如何存储更新后的知识。本文揭示，无论是修改长期记忆（即直接调整模型参数）还是工作记忆（通过检索增强的神经网络激活/表示），都会陷入一个无法同时满足可靠性、泛化性和局部性的困境。直接修改长期记忆可能导致与预训练知识或先前编辑的冲突，而工作记忆的检索机制则难以确保模型理解和泛化这些修改。为此，我们提出了WISE方案，通过设计双参数记忆系统来解决这一难题。WISE包含主记忆存储预训练知识，辅助记忆存储编辑后的知识，并通过训练路由器智能选择记忆路径。对于持续的知识更新，WISE采用知识分片技术，确保不同编辑集在参数子空间中独立存在，最终无冲突地整合到共享记忆中。实验证明，WISE在问答、幻觉检测和分布外场景下的终身模型编辑中表现卓越，适用于GPT、LLaMA和Mistral等主流LLM架构。相关代码将在https://github.com/zjunlp/EasyEdit公开。

> Large language models (LLMs) need knowledge updates to meet the ever-growing world facts and correct the hallucinated responses, facilitating the methods of lifelong model editing. Where the updated knowledge resides in memories is a fundamental question for model editing. In this paper, we find that editing either long-term memory (direct model parameters) or working memory (non-parametric knowledge of neural network activations/representations by retrieval) will result in an impossible triangle -- reliability, generalization, and locality can not be realized together in the lifelong editing settings. For long-term memory, directly editing the parameters will cause conflicts with irrelevant pretrained knowledge or previous edits (poor reliability and locality). For working memory, retrieval-based activations can hardly make the model understand the edits and generalize (poor generalization). Therefore, we propose WISE to bridge the gap between memories. In WISE, we design a dual parametric memory scheme, which consists of the main memory for the pretrained knowledge and a side memory for the edited knowledge. We only edit the knowledge in the side memory and train a router to decide which memory to go through when given a query. For continual editing, we devise a knowledge-sharding mechanism where different sets of edits reside in distinct subspaces of parameters, and are subsequently merged into a shared memory without conflicts. Extensive experiments show that WISE can outperform previous model editing methods and overcome the impossible triangle under lifelong model editing of question answering, hallucination, and out-of-distribution settings across trending LLM architectures, e.g., GPT, LLaMA, and Mistral. Code will be released at https://github.com/zjunlp/EasyEdit.

[Arxiv](https://arxiv.org/abs/2405.14768)