# 为了自我修正推理过程，小型语言模型亟需配备强有力的验证机制。

发布时间：2024年04月25日

`分类：LLM应用

这篇论文主要探讨了如何提升小型语言模型在推理任务上的自我纠错功能，通过设计一种创新的流程来培养模型的自我完善能力。这属于LLM应用的范畴，因为它涉及到如何更有效地利用现有的语言模型来提高其性能。` `人工智能`

> Small Language Models Need Strong Verifiers to Self-Correct Reasoning

# 摘要

> 自我纠错技术正成为提升大型语言模型推理能力的有效途径，它通过自我批评来精确识别并修正错误。本研究旨在探究小型语言模型（规模不超过13B）在几乎不依赖更大型语言模型输入的情况下，是否具备在推理任务上的自我纠错功能。我们设计了一种创新的流程，激励这些小型模型收集自我纠错数据，以培养其自我完善的能力。首先，我们使用正确答案引导模型自我批评错误回答；其次，经过筛选的批评意见被用于对自我纠错推理器进行有监督的微调，以细化解决方案。实验结果表明，在涵盖数学和常识推理的五个数据集中，两种模型的自我纠错能力均有所增强，尤其是在与基于GPT-4的强大验证器结合使用时，性能提升尤为明显。然而，当使用较弱的自我验证器来决定何时进行纠错时，也暴露出了一些限制。

> Self-correction has emerged as a promising solution to boost the reasoning performance of large language models (LLMs), where LLMs refine their solutions using self-generated critiques that pinpoint the errors. This work explores whether smaller-size (<= 13B) language models (LMs) have the ability of self-correction on reasoning tasks with minimal inputs from stronger LMs. We propose a novel pipeline that prompts smaller LMs to collect self-correction data that supports the training of self-refinement abilities. First, we leverage correct solutions to guide the model in critiquing their incorrect responses. Second, the generated critiques, after filtering, are used for supervised fine-tuning of the self-correcting reasoner through solution refinement. Our experimental results show improved self-correction abilities of two models on five datasets spanning math and commonsense reasoning, with notable performance gains when paired with a strong GPT-4-based verifier, though limitations are identified when using a weak self-verifier for determining when to correct.

[Arxiv](https://arxiv.org/abs/2404.17140)