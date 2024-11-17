# CoCoP：借助代码完成提示用 LLM 强化文本分类

发布时间：2024年11月13日

`LLM应用` `代码相关任务`

> CoCoP: Enhancing Text Classification with LLM through Code Completion Prompt

# 摘要

> 文本分类乃自然语言处理（NLP）的基础任务，大型语言模型（LLMs）已展现出能在各领域执行此任务的能力。然而，LLMs 的性能极大程度取决于输入提示的质量。近期研究还显示，LLMs 在代码相关任务中表现出众。为借助 LLMs 在文本分类中的能力，我们提出了代码完成提示（CoCoP）方法，将文本分类问题转化为代码完成任务。CoCoP 借助 LLMs 的代码完成能力，在不同数据集上大幅提升了文本分类性能。比如，CoCoP 让 SST2 数据集的准确率提高了 20%以上。另外，当 CoCoP 与专为代码相关任务设计的 LLMs（如 CodeLLaMA）集成时，该方法仅用十分之一的模型大小，就展现出优于或与少样本学习技术相当的性能。我们所提方法的源代码在论文被接收后会向公众开放。

> Text classification is a fundamental task in natural language processing (NLP), and large language models (LLMs) have demonstrated their capability to perform this task across various domains. However, the performance of LLMs heavily depends on the quality of their input prompts. Recent studies have also shown that LLMs exhibit remarkable results in code-related tasks. To leverage the capabilities of LLMs in text classification, we propose the Code Completion Prompt (CoCoP) method, which transforms the text classification problem into a code completion task. CoCoP significantly improves text classification performance across diverse datasets by utilizing LLMs' code-completion capability. For instance, CoCoP enhances the accuracy of the SST2 dataset by more than 20%. Moreover, when CoCoP integrated with LLMs specifically designed for code-related tasks (code models), such as CodeLLaMA, this method demonstrates better or comparable performance to few-shot learning techniques while using only one-tenth of the model size. The source code of our proposed method will be available to the public upon the acceptance of the paper.

[Arxiv](https://arxiv.org/abs/2411.08979)