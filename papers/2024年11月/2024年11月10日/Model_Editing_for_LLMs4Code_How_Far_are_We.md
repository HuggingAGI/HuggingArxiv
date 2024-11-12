# 针对 LLMs4Code 的模型编辑：我们走了多远？

发布时间：2024年11月10日

`LLM应用` `软件工程` `模型编辑`

> Model Editing for LLMs4Code: How Far are We?

# 摘要

> 用于代码的大型语言模型（LLMs4Code）已被发现在软件工程领域表现出色，特别是在编码任务中的显著表现。然而，即使是最先进的 LLMs4Code 也不可避免地包含不正确或过时的代码知识。由于训练 LLMs4Code 的成本很高，重新训练模型以修复这些有问题的代码知识是不切实际的。模型编辑是一个新的技术领域，用于有效和高效地纠正 LLMs 中的错误知识，最近已经提出了各种模型编辑技术和基准。尽管如此，一个全面的研究，彻底比较和分析最先进的模型编辑技术在适应 LLMs4Code 内的知识在各种与代码相关的任务中的性能是明显缺失的。为了弥补这一差距，我们对应用最先进的模型编辑方法来修复 LLMs4Code 的不准确性进行了首次系统研究。为此，我们引入了一个名为 CLMEEval 的基准，它由两个数据集组成，即具有 21K + 代码生成样本的 CoNaLa-Edit（CNLE）和具有 16K + 代码摘要样本的 CodeSearchNet-Edit（CSNE）。在 CLMEEval 的帮助下，我们在三个 LLMs4Code 上评估了六种先进的模型编辑技术：CodeLlama（7B）、CodeQwen1.5（7B）和 Stable-Code（3B）。我们的发现包括基于外部记忆的 GRACE 方法实现了最佳的知识编辑有效性和特异性（编辑不影响未目标的知识），而泛化（编辑是否可以推广到其他语义相同的输入）是现有技术的普遍挑战。此外，基于深入的案例分析，我们引入了 GRACE 的增强版本称为 A-GRACE，它结合了对比学习以更好地捕获输入的语义。

> Large Language Models for Code (LLMs4Code) have been found to exhibit outstanding performance in the software engineering domain, especially the remarkable performance in coding tasks. However, even the most advanced LLMs4Code can inevitably contain incorrect or outdated code knowledge. Due to the high cost of training LLMs4Code, it is impractical to re-train the models for fixing these problematic code knowledge. Model editing is a new technical field for effectively and efficiently correcting erroneous knowledge in LLMs, where various model editing techniques and benchmarks have been proposed recently. Despite that, a comprehensive study that thoroughly compares and analyzes the performance of the state-of-the-art model editing techniques for adapting the knowledge within LLMs4Code across various code-related tasks is notably absent. To bridge this gap, we perform the first systematic study on applying state-of-the-art model editing approaches to repair the inaccuracy of LLMs4Code. To that end, we introduce a benchmark named CLMEEval, which consists of two datasets, i.e., CoNaLa-Edit (CNLE) with 21K+ code generation samples and CodeSearchNet-Edit (CSNE) with 16K+ code summarization samples. With the help of CLMEEval, we evaluate six advanced model editing techniques on three LLMs4Code: CodeLlama (7B), CodeQwen1.5 (7B), and Stable-Code (3B). Our findings include that the external memorization-based GRACE approach achieves the best knowledge editing effectiveness and specificity (the editing does not influence untargeted knowledge), while generalization (whether the editing can generalize to other semantically-identical inputs) is a universal challenge for existing techniques. Furthermore, building on in-depth case analysis, we introduce an enhanced version of GRACE called A-GRACE, which incorporates contrastive learning to better capture the semantics of the inputs.

[Arxiv](https://arxiv.org/abs/2411.06638)