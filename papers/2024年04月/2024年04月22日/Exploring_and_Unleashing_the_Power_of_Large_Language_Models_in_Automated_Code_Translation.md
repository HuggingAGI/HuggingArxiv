# 深入挖掘并充分发挥大型语言模型在自动化代码翻译领域的潜力。

发布时间：2024年04月22日

`LLM应用` `软件开发`

> Exploring and Unleashing the Power of Large Language Models in Automated Code Translation

# 摘要

> 为实现自动源代码到源代码的转换，开发了代码翻译工具。基于学习的转换编译器相较于基于规则的编译器，因其在大量单语种语料库上的任务特定预训练，展现出了显著的进步。但它们的表现对于实际应用而言仍显不足，且训练成本高昂。而大型语言模型（LLM）在广泛的代码/文本数据预训练后，在众多代码智能任务上展现了卓越的性能，这得益于它们的强大通用性，即便没有特定任务的训练。LLM 有望克服现有限制，但尚未被充分挖掘。本研究对比了多种 LLM 和基于学习的转换编译器在自动化代码翻译任务中的表现，发现尽管某些 LLM 超越了现有的编译器，但在准确性上仍有挑战，主要问题包括对源程序理解不足（38.51%）、翻译中 I/O 类型指示不明确（14.94%）以及忽视源目标程序间差异（41.38%）。基于这些发现，我们提出了 UniTrans，一个适用于多种 LLM 的统一代码翻译框架，旨在释放其在自动代码翻译领域的潜力。UniTrans 首先利用源程序辅助生成目标程序的一系列测试用例，然后通过这些自动生成的测试用例来增强代码翻译，并执行测试以验证其正确性。接着，UniTrans 会根据测试结果迭代修复翻译不准确的程序。我们在 Python、Java 和 C++ 的六个翻译数据集上进行了广泛测试，三种不同规模的最新 LLM 在使用 UniTrans 后均取得了显著的性能提升。

> Code translation tools are developed for automatic source-to-source translation. Although learning-based transpilers have shown impressive enhancement against rule-based counterparts, owing to their task-specific pre-training on extensive monolingual corpora. Their current performance still remains unsatisfactory for practical deployment, and the associated training resources are also prohibitively expensive. LLMs pre-trained on huge amounts of human-written code/text have shown remarkable performance in many code intelligence tasks due to their powerful generality, even without task-specific training. Thus, LLMs can potentially circumvent the above limitations, but they have not been exhaustively explored yet. This paper investigates diverse LLMs and learning-based transpilers for automated code translation tasks, finding that: although certain LLMs have outperformed current transpilers, they still have some accuracy issues, where most of the failures are induced by a lack of comprehension of source programs (38.51%), missing clear instructions on I/O types in translation (14.94%), and ignoring discrepancies between source and target programs (41.38%). Enlightened by the above findings, we propose UniTrans, an Unified code Translation framework, applicable to various LLMs, for unleashing their power in this field. Specifically, UniTrans first craft a series of test cases for target programs with the assistance of source programs. Next, it harnesses the above auto-generated test cases to augment the code translation and then evaluate their correctness via execution. Afterward, UniTrans further (iteratively) repairs incorrectly translated programs prompted by test case execution results. Extensive experiments are conducted on six translation datasets between Python, Java, and C++. Three recent LLMs of diverse sizes are tested with UniTrans, and all achieve substantial improvements.

[Arxiv](https://arxiv.org/abs/2404.14646)