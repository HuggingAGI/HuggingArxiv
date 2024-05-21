# MapCoder：多代理协作，共创竞争问题解决的代码新篇章

发布时间：2024年05月18日

`Agent

理由：这篇论文介绍了一种新颖的多代理提示方法，用于代码合成，其中涉及多个LLM代理模拟人类开发者的程序合成全周期。这种方法强调了代理（Agent）的概念，即多个智能体协同工作以完成复杂的任务。因此，这篇论文更适合归类在Agent分类中。` `软件开发` `人工智能`

> MapCoder: Multi-Agent Code Generation for Competitive Problem Solving

# 摘要

> 代码合成是一项艰巨的任务，它要求深入理解复杂的自然语言描述，生成复杂算法和数据结构的代码指令，并通过全面的单元测试。尽管大型语言模型（LLMs）在自然语言处理上表现出色，但在代码生成方面仍有局限。本文提出了一种新颖的多代理提示方法，模拟人类开发者的程序合成全周期，包括回忆示例、规划、代码生成和调试。我们的MapCoder框架由四个LLM代理组成，经过在八个高难度基准上的广泛测试，MapCoder在多个编程语言和问题难度上均展现出顶尖的代码生成能力，刷新了HumanEval、MBPP、APPS、CodeContests和xCodeEval的记录。我们已将MapCoder框架开源，地址为https://github.com/Md-Ashraful-Pramanik/MapCoder。

> Code synthesis, which requires a deep understanding of complex natural language problem descriptions, generation of code instructions for complex algorithms and data structures, and the successful execution of comprehensive unit tests, presents a significant challenge. While large language models (LLMs) demonstrate impressive proficiency in natural language processing, their performance in code generation tasks remains limited. In this paper, we introduce a new approach to code generation tasks leveraging multi-agent prompting that uniquely replicates the full cycle of program synthesis as observed in human developers. Our framework, MapCoder, consists of four LLM agents specifically designed to emulate the stages of this cycle: recalling relevant examples, planning, code generation, and debugging. After conducting thorough experiments, with multiple LLM ablations and analyses across eight challenging competitive problem-solving and program synthesis benchmarks, MapCoder showcases remarkable code generation capabilities, achieving new state-of-the-art results (pass@1) on HumanEval (93.9%), MBPP (83.1%), APPS (22.0%), CodeContests (28.5%), and xCodeEval (45.3%). Moreover, our method consistently delivers superior performance across various programming languages and varying problem difficulties. We open-source our framework at https://github.com/Md-Ashraful-Pramanik/MapCoder.

![MapCoder：多代理协作，共创竞争问题解决的代码新篇章](../../../paper_images/2405.11403/x1.png)

![MapCoder：多代理协作，共创竞争问题解决的代码新篇章](../../../paper_images/2405.11403/x3.png)

![MapCoder：多代理协作，共创竞争问题解决的代码新篇章](../../../paper_images/2405.11403/x4.png)

![MapCoder：多代理协作，共创竞争问题解决的代码新篇章](../../../paper_images/2405.11403/x5.png)

![MapCoder：多代理协作，共创竞争问题解决的代码新篇章](../../../paper_images/2405.11403/xcode-algo-diff.png)

![MapCoder：多代理协作，共创竞争问题解决的代码新篇章](../../../paper_images/2405.11403/apps-dataset-difficulty-levels.png)

![MapCoder：多代理协作，共创竞争问题解决的代码新篇章](../../../paper_images/2405.11403/multi-lingual.png)

![MapCoder：多代理协作，共创竞争问题解决的代码新篇章](../../../paper_images/2405.11403/x13.png)

![MapCoder：多代理协作，共创竞争问题解决的代码新篇章](../../../paper_images/2405.11403/x14.png)

![MapCoder：多代理协作，共创竞争问题解决的代码新篇章](../../../paper_images/2405.11403/x15.png)

[Arxiv](https://arxiv.org/abs/2405.11403)