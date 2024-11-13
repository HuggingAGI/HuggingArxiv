# ExpressivityArena：大型语言模型能否隐性地表达信息？

发布时间：2024年11月12日

`LLM应用` `语言模型` `软件开发`

> ExpressivityArena: Can LLMs Express Information Implicitly?

# 摘要

> 虽然大型语言模型（LLMs）在某些方面表现出了显著的性能，但它们表达人类用于有效交流的隐性语言线索的能力仍不清楚。本文介绍了 ExpressivityArena，这是一个用于测量 LLMs 隐性交流能力的 Python 库。我们提供了一个全面的框架来评估任意 LLMs 的表达能力，并探讨其实际影响。为此，我们完善了“表达能力”的定义和测量方法，并在一组小型实验中使用了我们的框架。这些实验在诗歌、编码和基于情感的响应等创造性和逻辑性任务中对 LLMs 进行测试。然后通过 ExpressivityArena 由自动评分器进行评估，我们证实这是测试表达能力最实用的方法。基于这些实验，我们通过评估 LLMs 在对话中保持表达能力的能力，加深了对 LLMs 表达能力的理解。我们的研究结果表明，LLMs 能够生成和理解有表现力的内容，但存在一些局限性。这些见解将为未来有表现力的 LLMs 的开发和部署提供信息。我们在论文中提供了 ExpressivityArena 的代码。

> While Large Language Models (LLMs) have demonstrated remarkable performance in certain dimensions, their ability to express implicit language cues that human use for effective communication remains unclear. This paper presents ExpressivityArena, a Python library for measuring the implicit communication abilities of LLMs. We provide a comprehensive framework to evaluate expressivity of arbitrary LLMs and explore its practical implications. To this end, we refine the definition and measurements of ``expressivity,'' and use our framework in a set of small experiments. These experiments test LLMs in creative and logical tasks such as poetry, coding, and emotion-based responses. They are then evaluated by an automated grader, through ExpressivityArena, which we verify to be the most pragmatic for testing expressivity. Building on these experiments, we deepen our understanding of the expressivity of LLMs by assessing their ability to remain expressive in conversations. Our findings indicate that LLMs are capable of generating and understanding expressive content, however, with some limitations. These insights will inform the future development and deployment of expressive LLMs. We provide the code for ExpressivityArena alongside our paper.

[Arxiv](https://arxiv.org/abs/2411.08010)