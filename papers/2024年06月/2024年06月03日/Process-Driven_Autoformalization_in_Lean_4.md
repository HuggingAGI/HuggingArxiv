# Lean 4中的过程驱动自动形式化

发布时间：2024年06月03日

`LLM应用

这篇论文主要探讨了如何利用大型语言模型（LLMs）来提高自动形式化技术，特别是在将自然语言数学转化为形式语言如Lean 4的过程中的应用。论文介绍了一个新的基准测试和过程监督验证器（PSV）模型，这些都是为了提升LLMs在自动形式化任务中的性能。因此，这篇论文的内容更偏向于LLM的具体应用，而不是理论研究或Agent的设计与实现，也不是关于检索增强生成（RAG）的研究。` `数学推理` `形式化语言`

> Process-Driven Autoformalization in Lean 4

# 摘要

> 自动形式化技术，将自然语言数学转化为形式语言，极大地推动了数学推理的发展。但目前的工作仅限于那些拥有丰富在线资源的形式语言，对于如Lean 4这类快速演进的语言则显得力不从心。为此，我们推出了一项新基准——Lean 4的正式化（\textbf{\name}），专门用于测试大型语言模型（LLMs）的自动形式化能力，涵盖了问题、答案、正式陈述及证明的全面评估。同时，我们还开发了一个过程监督验证器（PSV）模型，它通过Lean 4编译器的精准反馈来提升自动形式化效率。实验结果显示，PSV不仅提高了自动形式化的准确性，还减少了训练数据的筛选需求。当PSV通过包含详细过程信息的数据进行微调时，其对数据的利用更为高效，显著提升了Lean 4的自动形式化效果。我们的数据集和代码已公开于\url{https://github.com/rookie-joe/PDA}。

> Autoformalization, the conversion of natural language mathematics into formal languages, offers significant potential for advancing mathematical reasoning. However, existing efforts are limited to formal languages with substantial online corpora and struggle to keep pace with rapidly evolving languages like Lean 4. To bridge this gap, we propose a new benchmark \textbf{Form}alization for \textbf{L}ean~\textbf{4} (\textbf{\name}) designed to evaluate the autoformalization capabilities of large language models (LLMs). This benchmark encompasses a comprehensive assessment of questions, answers, formal statements, and proofs. Additionally, we introduce a \textbf{P}rocess-\textbf{S}upervised \textbf{V}erifier (\textbf{PSV}) model that leverages the precise feedback from Lean 4 compilers to enhance autoformalization. Our experiments demonstrate that the PSV method improves autoformalization, enabling higher accuracy using less filtered training data. Furthermore, when fine-tuned with data containing detailed process information, PSV can leverage the data more effectively, leading to more significant improvements in autoformalization for Lean 4. Our dataset and code are available at \url{https://github.com/rookie-joe/PDA}.

![Lean 4中的过程驱动自动形式化](../../../paper_images/2406.01940/x1.png)

[Arxiv](https://arxiv.org/abs/2406.01940)