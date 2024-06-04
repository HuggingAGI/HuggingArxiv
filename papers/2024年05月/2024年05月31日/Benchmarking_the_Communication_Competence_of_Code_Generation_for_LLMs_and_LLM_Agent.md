# 评估大型语言模型及其代理在代码生成中的沟通能力

发布时间：2024年05月31日

`Agent

理由：这篇论文主要探讨了大型语言模型（LLMs）在代码生成任务中的沟通技巧，特别是如何通过提出澄清性问题来优化代码生成。论文中提到的“新型LLM代理方法Okanagan”表明这是一个关于Agent的研究，因为它涉及到了一个能够识别问题并提出解决方案的智能代理。此外，论文通过创建新的基准测试集和评估指标来评估这些代理的能力，进一步强调了其Agent的特性。因此，这篇论文更适合归类到Agent分类中。` `软件开发` `人工智能`

> Benchmarking the Communication Competence of Code Generation for LLMs and LLM Agent

# 摘要

> 大型语言模型（LLMs）在代码生成任务上的能力显著增强，但与顶尖软件工程师相比，仍有提升空间。顶尖软件工程师常通过提问来澄清需求和解决方案中的模糊性，我们认为LLMs也应采取类似策略。为此，我们开展了一项实证研究，专门评估和分析LLMs在代码生成中的沟通技巧。我们定义LLMs的沟通技巧为“在代码生成问题描述存在问题时，能够提出澄清性问题”。通过修改问题描述，我们创建了新的基准测试集HumanEvalComm，涵盖了不一致性、模糊性和不完整性三个方面。我们引入了沟通率和好问题率等新评估指标，并在HumanEvalComm上测试了多种代码LLMs及新型LLM代理方法Okanagan，后者能识别并针对模糊部分提出问题，以优化代码生成。最后，我们通过比较不同模型的评估结果，深入讨论了我们的发现。

> Large language models (LLMs) have significantly improved their ability to perform tasks in the field of code generation. However, there is still a gap between LLMs being capable coders and being top-tier software engineers. Based on the observation that top-level software engineers often ask clarifying questions to reduce ambiguity in both requirements and coding solutions, we argue that the same should be applied to LLMs for code generation tasks.
  In this work, we conducted an empirical study on the benchmark and analysis of the communication skills of LLMs for code generation. We define communication skills of LLMs as ``being able to ask clarifying questions when the description of the code generation problem has issues''. We created a new benchmark, HumanEvalComm, by modifying problem descriptions according to three issues: inconsistency, ambiguity, incompleteness. We defined new evaluation metrics such as Communication Rate and Good Question Rate, and then experimented on HumanEvalComm with different Code LLMs, and a new LLM agent approach, Okanagan, to identify and ask questions in ambiguous parts from code and descriptions for further refining the generated code. Finally, we discussed evaluation results by comparing Code LLMs and Okanagan with our findings.

![评估大型语言模型及其代理在代码生成中的沟通能力](../../../paper_images/2406.00215/HumanEvalComm_methdology.png)

![评估大型语言模型及其代理在代码生成中的沟通能力](../../../paper_images/2406.00215/CodeLLMs.png)

![评估大型语言模型及其代理在代码生成中的沟通能力](../../../paper_images/2406.00215/Okanagan.png)

![评估大型语言模型及其代理在代码生成中的沟通能力](../../../paper_images/2406.00215/x1.png)

![评估大型语言模型及其代理在代码生成中的沟通能力](../../../paper_images/2406.00215/x2.png)

[Arxiv](https://arxiv.org/abs/2406.00215)