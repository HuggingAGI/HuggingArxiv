# Lean 4 中的过程驱动自动形式化

发布时间：2024年06月03日

`LLM应用

这篇论文主要探讨了如何利用大型语言模型（LLM）来提高自动形式化技术的能力，特别是在处理如Lean 4这样的形式语言时。论文中提出的“Lean 4形式化”基准和过程监督验证器（PSV）都是为了评估和提升LLM在自动形式化任务中的表现。这些内容直接关联到LLM的应用层面，即如何将LLM技术应用于特定的技术挑战（如形式化数学语言的转换），并展示了LLM在实际应用中的改进和优化。因此，这篇论文应归类于LLM应用。` `数学推理` `形式化语言`

> Process-Driven Autoformalization in Lean 4

# 摘要

> 自动形式化技术，将自然语言数学转化为形式语言，极大地推动了数学推理的发展。但目前的工作仅限于那些拥有丰富在线资源的形式语言，对于如Lean 4这类快速演进的语言则显得力不从心。为此，我们推出了一项名为“Lean 4形式化”的新基准，专门用于测试大型语言模型在自动形式化方面的能力，涵盖了问题、答案、形式陈述及证明的全面评估。同时，我们还开发了一个过程监督验证器（PSV），它通过Lean 4编译器的精准反馈来提升自动形式化效果。实验结果显示，PSV不仅提高了自动形式化的准确性，还减少了训练数据的筛选需求。当PSV利用包含详细过程信息的数据进行微调时，其在Lean 4自动形式化上的表现更是有了显著提升。我们的数据集和代码已公开在GitHub上，地址为：https://github.com/rookie-joe/PDA。

> Autoformalization, the conversion of natural language mathematics into formal languages, offers significant potential for advancing mathematical reasoning. However, existing efforts are limited to formal languages with substantial online corpora and struggle to keep pace with rapidly evolving languages like Lean 4. To bridge this gap, we propose a new benchmark \textbf{Form}alization for \textbf{L}ean~\textbf{4} (\textbf{\name}) designed to evaluate the autoformalization capabilities of large language models (LLMs). This benchmark encompasses a comprehensive assessment of questions, answers, formal statements, and proofs. Additionally, we introduce a \textbf{P}rocess-\textbf{S}upervised \textbf{V}erifier (\textbf{PSV}) model that leverages the precise feedback from Lean 4 compilers to enhance autoformalization. Our experiments demonstrate that the PSV method improves autoformalization, enabling higher accuracy using less filtered training data. Furthermore, when fine-tuned with data containing detailed process information, PSV can leverage the data more effectively, leading to more significant improvements in autoformalization for Lean 4. Our dataset and code are available at \url{https://github.com/rookie-joe/PDA}.

![Lean 4 中的过程驱动自动形式化](../../../paper_images/2406.01940/x1.png)

[Arxiv](https://arxiv.org/abs/2406.01940)