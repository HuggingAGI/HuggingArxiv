# 评估 LLMs 与 LLM 代理在代码生成中的沟通能力

发布时间：2024年05月31日

`Agent

理由：这篇论文主要关注的是在代码生成任务中，如何通过代理方法（如Okanagan）来提高大型语言模型（LLMs）的沟通技巧，特别是在问题描述不明确时提出澄清问题的能力。论文中提到的代理方法Okanagan是用来优化LLMs在代码生成中的表现，这符合Agent分类的定义，即关注于如何通过智能代理来增强或改进系统的功能。因此，这篇论文应归类于Agent。` `软件开发` `人工智能`

> Benchmarking the Communication Competence of Code Generation for LLMs and LLM Agent

# 摘要

> 大型语言模型（LLMs）在代码生成任务上的能力显著增强，但与顶尖软件工程师相比，仍有提升空间。顶尖软件工程师常通过提问澄清需求和解决方案的歧义，我们认为LLMs也应采取类似策略。为此，我们进行了实证研究，评估LLMs在代码生成中的沟通技巧，定义为“在问题描述不明确时能提出澄清问题”。我们创建了新基准HumanEvalComm，针对描述中的不一致、歧义和不完整问题进行调整，并引入了沟通率和优质问题率等新评估指标。通过在HumanEvalComm上测试不同LLMs和新型代理方法Okanagan，我们发现Okanagan能有效识别并针对歧义部分提问，从而优化代码生成。最后，我们对比了不同LLMs和Okanagan的表现，深入讨论了研究结果。

> Large language models (LLMs) have significantly improved their ability to perform tasks in the field of code generation. However, there is still a gap between LLMs being capable coders and being top-tier software engineers. Based on the observation that top-level software engineers often ask clarifying questions to reduce ambiguity in both requirements and coding solutions, we argue that the same should be applied to LLMs for code generation tasks.
  In this work, we conducted an empirical study on the benchmark and analysis of the communication skills of LLMs for code generation. We define communication skills of LLMs as ``being able to ask clarifying questions when the description of the code generation problem has issues''. We created a new benchmark, HumanEvalComm, by modifying problem descriptions according to three issues: inconsistency, ambiguity, incompleteness. We defined new evaluation metrics such as Communication Rate and Good Question Rate, and then experimented on HumanEvalComm with different Code LLMs, and a new LLM agent approach, Okanagan, to identify and ask questions in ambiguous parts from code and descriptions for further refining the generated code. Finally, we discussed evaluation results by comparing Code LLMs and Okanagan with our findings.

![评估 LLMs 与 LLM 代理在代码生成中的沟通能力](../../../paper_images/2406.00215/HumanEvalComm_methdology.png)

![评估 LLMs 与 LLM 代理在代码生成中的沟通能力](../../../paper_images/2406.00215/CodeLLMs.png)

![评估 LLMs 与 LLM 代理在代码生成中的沟通能力](../../../paper_images/2406.00215/Okanagan.png)

![评估 LLMs 与 LLM 代理在代码生成中的沟通能力](../../../paper_images/2406.00215/x1.png)

![评估 LLMs 与 LLM 代理在代码生成中的沟通能力](../../../paper_images/2406.00215/x2.png)

[Arxiv](https://arxiv.org/abs/2406.00215)