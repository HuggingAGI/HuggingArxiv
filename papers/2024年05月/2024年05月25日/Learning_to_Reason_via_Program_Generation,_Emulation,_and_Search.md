# 学习推理：程序生成、模拟与搜索的结合

发布时间：2024年05月25日

`LLM应用

这篇论文主要探讨了如何扩展语言模型（LMs）的程序合成能力，以解决更广泛的推理任务，包括那些不能简单转化为代码的任务。通过开发Code Generation and Emulated EXecution（CoGEX）系统，论文展示了如何训练LMs创造和模拟执行伪程序，以及如何利用这些程序在多个任务中寻找最优解。这种方法在算法和软推理任务上优于传统的上下文学习方法，显示了代码合成在更广泛问题类别中的应用潜力。因此，这篇论文属于LLM应用类别，因为它关注的是如何应用LLM技术来解决实际问题，而不是理论研究或Agent的设计与应用。` `人工智能`

> Learning to Reason via Program Generation, Emulation, and Search

# 摘要

> 语言模型（LMs）的程序合成能力已开启了一系列推理技能的大门；经过代码优化的LMs在生成解决多种算法符号操作任务（如单词拼接）的程序方面表现出色。然而，并非所有推理任务都能简单转化为代码，比如涉及常识推理、道德判断和讽刺理解的挑战。我们的目标是将LMs的程序合成技能扩展至这些领域，并通过伪程序（即Python程序，其中某些叶函数调用未定义）来评估成果。为此，我们开发了Code Generation and Emulated EXecution（CoGEX），它通过以下方式运作：(1) 训练LMs创造自己的伪程序，(2) 教导它们模拟这些程序的执行，包括未定义的叶函数，让LMs的知识填补执行的空白；(3) 利用它们在众多程序中寻找最优解。为了使CoGEX模型适应新任务，我们提出了一种程序搜索方法，以找到一个在应用于特定数据集的所有实例时能实现最优性能的程序。我们的方法在一系列算法和软推理任务上显著优于传统的上下文学习方法。这一成果展示了代码合成在更广泛问题类别中的应用潜力。我们发布的数据集、微调模型和实现细节可在\url{https://github.com/nweir127/CoGEX}获取。

> Program synthesis with language models (LMs) has unlocked a large set of reasoning abilities; code-tuned LMs have proven adept at generating programs that solve a wide variety of algorithmic symbolic manipulation tasks (e.g. word concatenation). However, not all reasoning tasks are easily expressible as code, e.g. tasks involving commonsense reasoning, moral decision-making, and sarcasm understanding. Our goal is to extend an LM's program synthesis skills to such tasks and evaluate the results via pseudo-programs, namely Python programs where some leaf function calls are left undefined. To that end, we propose, Code Generation and Emulated EXecution (CoGEX). CoGEX works by (1) training LMs to generate their own pseudo-programs, (2) teaching them to emulate their generated program's execution, including those leaf functions, allowing the LM's knowledge to fill in the execution gaps; and (3) using them to search over many programs to find an optimal one. To adapt the CoGEX model to a new task, we introduce a method for performing program search to find a single program whose pseudo-execution yields optimal performance when applied to all the instances of a given dataset. We show that our approach yields large improvements compared to standard in-context learning approaches on a battery of tasks, both algorithmic and soft reasoning. This result thus demonstrates that code synthesis can be applied to a much broader class of problems than previously considered. Our released dataset, fine-tuned models, and implementation can be found at \url{https://github.com/nweir127/CoGEX}.

![学习推理：程序生成、模拟与搜索的结合](../../../paper_images/2405.16337/x1.png)

![学习推理：程序生成、模拟与搜索的结合](../../../paper_images/2405.16337/x2.png)

![学习推理：程序生成、模拟与搜索的结合](../../../paper_images/2405.16337/x3.png)

![学习推理：程序生成、模拟与搜索的结合](../../../paper_images/2405.16337/x4.png)

![学习推理：程序生成、模拟与搜索的结合](../../../paper_images/2405.16337/x5.png)

[Arxiv](https://arxiv.org/abs/2405.16337)