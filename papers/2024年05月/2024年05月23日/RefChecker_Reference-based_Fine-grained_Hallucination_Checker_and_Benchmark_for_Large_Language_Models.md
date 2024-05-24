# RefChecker：大型语言模型细粒度幻觉检测与基准评估工具

发布时间：2024年05月23日

`LLM应用

这篇论文介绍了一个名为RefChecker的框架，旨在检测大型语言模型（LLMs）产生的幻觉。该框架通过提取和评估LLM响应中的claim-triplets来实现这一目标。论文中还提到了在不同上下文环境中进行的实验，并展示了RefChecker在性能上的显著提升。由于这项工作专注于LLM的应用层面，即如何改进和检测LLM的输出质量，因此它属于LLM应用分类。` `模型评估`

> RefChecker: Reference-based Fine-grained Hallucination Checker and Benchmark for Large Language Models

# 摘要

> 大型语言模型（LLMs）虽能力惊人，却常陷入幻觉的陷阱。本文推出的RefChecker框架，通过claim-triplets精确捕捉LLM响应中的声明，旨在细查这些幻觉。RefChecker中，提取器从响应中抽取claim-triplets，再由检查器与参考资料对比评估。我们设定了零、噪声和准确三种上下文环境，模拟真实场景。精心构建的NLP任务基准，涵盖了从七个LLM的2.1k响应中提取的11k个claim-triplets。RefChecker兼容专有与开源模型，实验证明，其细粒度检测能力远超其他方法，性能提升6.8至26.1分，且与人类判断高度吻合。此项研究已在https://github.com/amazon-science/RefChecker开源。

> Large Language Models (LLMs) have shown impressive capabilities but also a concerning tendency to hallucinate. This paper presents RefChecker, a framework that introduces claim-triplets to represent claims in LLM responses, aiming to detect fine-grained hallucinations. In RefChecker, an extractor generates claim-triplets from a response, which are then evaluated by a checker against a reference. We delineate three task settings: Zero, Noisy and Accurate Context, to reflect various real-world use cases. We curated a benchmark spanning various NLP tasks and annotated 11k claim-triplets from 2.1k responses by seven LLMs. RefChecker supports both proprietary and open-source models as the extractor and checker. Experiments demonstrate that claim-triplets enable superior hallucination detection, compared to other granularities such as response, sentence and sub-sentence level claims. RefChecker outperforms prior methods by 6.8 to 26.1 points on our benchmark and the checking results of RefChecker are strongly aligned with human judgments. This work is open sourced at https://github.com/amazon-science/RefChecker

[Arxiv](https://arxiv.org/abs/2405.14486)