# 自然语言助力，静态调度器智能升级为动态调度器，自动化转换一触即发。

发布时间：2024年05月08日

`RAG

这篇论文探讨了大型语言模型（LLMs）在自动为动态调度问题建模和编码方面的应用，特别是提出了一种基于检索增强生成（RAG）的模型——RAGDyS。该模型旨在自动实施动态调度的约束，减少对专家优化的依赖，并简化建模过程。因此，它属于RAG分类，因为它专注于使用RAG技术来增强LLM在特定应用场景（动态调度问题）中的能力。` `调度优化` `自动化建模`

> Automated Conversion of Static to Dynamic Scheduler via Natural Language

# 摘要

> 本文探讨了大型语言模型（LLMs）在自动为动态调度问题建模和编码方面的潜力，这些问题基于现有的静态模型。静态调度问题由专家精心设计，但随着调度规则的演变，这些模型可能迅速失效。为了适应环境变化，有时需要将静态模型转变为动态模型。为此，我们提出了一种基于检索增强生成（RAG）的LLM模型——RAGDyS，它能够自动实施动态调度的约束，无需优化专家介入。我们的框架简化了数学建模和计算工作，使终端用户能够迅速生成接近原始调度的新方案，并通过自然语言描述反映约束变化。

> In this paper, we explore the potential application of Large Language Models (LLMs) that will automatically model constraints and generate code for dynamic scheduling problems given an existing static model. Static scheduling problems are modelled and coded by optimization experts. These models may be easily obsoleted as the underlying constraints may need to be fine-tuned in order to reflect changes in the scheduling rules. Furthermore, it may be necessary to turn a static model into a dynamic one in order to cope with disturbances in the environment. In this paper, we propose a Retrieval-Augmented Generation (RAG) based LLM model to automate the process of implementing constraints for Dynamic Scheduling (RAGDyS), without seeking help from an optimization modeling expert. Our framework aims to minimize technical complexities related to mathematical modelling and computational workload for end-users, thereby allowing end-users to quickly obtain a new schedule close to the original schedule with changes reflected by natural language constraint descriptions.

[Arxiv](https://arxiv.org/abs/2405.06697)