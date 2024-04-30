# 为了快速生成代码，我们对大型语言模型进行了性能优化，确保它们在编码任务中的表现与预期目标精准对齐。

发布时间：2024年04月29日

`分类：LLM应用

这篇论文讨论了如何利用大型语言模型（LLMs）来优化科学软件的性能。虽然这些模型主要针对代码文本分布进行训练，但本研究提出了一种基于强化学习的策略，以提升代码LLMs输出的性能。这表明了LLMs在软件开发领域的应用，特别是在性能优化方面。因此，这篇论文应该被归类为LLM应用。` `软件工程` `性能优化`

> Performance-Aligned LLMs for Generating Fast Code

# 摘要

> 科学软件的优化工作颇为棘手，原因在于代码库往往庞大复杂，且性能受算法、实现方式、硬件等多种因素影响。性能问题可能源自不同因素，诊断起来颇具挑战。近年来，大量研究利用大型语言模型（LLMs）助力软件开发。但这些模型主要针对代码文本分布进行训练，并未专门针对代码性能进行优化。本研究提出了一种基于强化学习的策略，旨在提升代码LLMs输出的性能。通过此方法，我们不仅能够利用LLMs现有的代码建模能力，还能进一步优化，生成性能更优的代码。实验结果表明，我们微调后的模型在一系列基准测试中，将串行代码的预期加速比从0.9提升至1.6，OpenMP代码的加速比更是从1.9跃升至4.5。

> Optimizing scientific software is a difficult task because codebases are often large and complex, and performance can depend upon several factors including the algorithm, its implementation, and hardware among others. Causes of poor performance can originate from disparate sources and be difficult to diagnose. Recent years have seen a multitude of work that use large language models (LLMs) to assist in software development tasks. However, these tools are trained to model the distribution of code as text, and are not specifically designed to understand performance aspects of code. In this work, we introduce a reinforcement learning based methodology to align the outputs of code LLMs with performance. This allows us to build upon the current code modeling capabilities of LLMs and extend them to generate better performing code. We demonstrate that our fine-tuned model improves the expected speedup of generated code over base models for a set of benchmark tasks from 0.9 to 1.6 for serial code and 1.9 to 4.5 for OpenMP code.

[Arxiv](https://arxiv.org/abs/2404.18864)