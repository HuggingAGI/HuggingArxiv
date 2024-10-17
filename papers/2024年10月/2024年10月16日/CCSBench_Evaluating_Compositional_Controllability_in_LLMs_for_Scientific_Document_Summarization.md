# CCSBench：科学文档摘要中 LLM 组合可控性的评估工具

发布时间：2024年10月16日

`LLM应用` `科学传播`

> CCSBench: Evaluating Compositional Controllability in LLMs for Scientific Document Summarization

# 摘要

> 为了更广泛地传播科学知识，科学文献摘要需同时兼顾长度和实证焦点等多重属性。然而，现有研究多聚焦于单一属性的控制，对多属性组合控制的研究尚显不足。为此，我们推出了CCSBench，一个专注于科学领域组合可控摘要的基准。该基准不仅能在显性属性（如长度）上实现精细调控，还能对隐性属性（如实证焦点）进行深入控制。我们在GPT-4、LLaMA2等主流LLM上进行了全面实验，结果显示，大型语言模型在平衡各控制属性，尤其是需深度理解和抽象推理的隐性属性方面，仍存在显著挑战。

> To broaden the dissemination of scientific knowledge to diverse audiences, scientific document summarization must simultaneously control multiple attributes such as length and empirical focus. However, existing research typically focuses on controlling single attributes, leaving the compositional control of multiple attributes underexplored. To address this gap, we introduce CCSBench, a benchmark for compositional controllable summarization in the scientific domain. Our benchmark enables fine-grained control over both explicit attributes (e.g., length), which are objective and straightforward, and implicit attributes (e.g., empirical focus), which are more subjective and conceptual. We conduct extensive experiments on GPT-4, LLaMA2, and other popular LLMs under various settings. Our findings reveal significant limitations in large language models' ability to balance trade-offs between control attributes, especially implicit ones that require deeper understanding and abstract reasoning.

[Arxiv](https://arxiv.org/abs/2410.12601)