# ANAH：大型语言模型幻觉的深度解析

发布时间：2024年05月30日

`LLM应用

这篇论文主要关注大型语言模型（LLMs）中的“幻觉”问题，并通过创建一个名为 **ANAH** 的双语数据集来解决这一问题。该数据集专注于生成式问答中的幻觉分析标注，包括参考片段检索、幻觉类型判断及内容修正。论文通过实验展示了使用该数据集训练的生成式标注器在性能上超越了现有的开源模型和 GPT-3.5，并与 GPT-4 相媲美，同时在新问题上表现出更强的泛化能力。因此，这篇论文属于 LLM 应用类别，因为它提供了一个具体的应用场景和解决方案，即通过数据集和标注器来改善 LLMs 在生成式问答中的表现。` `数据集构建`

> ANAH: Analytical Annotation of Hallucinations in Large Language Models

# 摘要

> 为了解决大型语言模型（LLMs）中的“幻觉”问题，我们推出了 **ANAH** 双语数据集，专注于 LLMs 在生成式问答中的幻觉分析标注。每个答案都经过精细标注，包括参考片段检索、幻觉类型判断及内容修正。ANAH 包含约 12,000 个句子级标注，覆盖 700 多个主题，通过人机协同流程精心构建。这一精细的标注使我们能定量分析 LLMs 幻觉的累积情况，并利用 ANAH 训练和评估幻觉标注器。实验表明，尽管开源 LLMs 在精细幻觉标注上存在挑战，但 ANAH 训练的生成式标注器不仅超越了所有开源模型和 GPT-3.5，还展现出与 GPT-4 相媲美的性能，并在新问题上表现出更强的泛化能力。

> Reducing the `$\textit{hallucination}$' problem of Large Language Models (LLMs) is crucial for their wide applications. A comprehensive and fine-grained measurement of the hallucination is the first key step for the governance of this issue but is under-explored in the community. Thus, we present $\textbf{ANAH}$, a bilingual dataset that offers $\textbf{AN}$alytical $\textbf{A}$nnotation of $\textbf{H}$allucinations in LLMs within Generative Question Answering. Each answer sentence in our dataset undergoes rigorous annotation, involving the retrieval of a reference fragment, the judgment of the hallucination type, and the correction of hallucinated content. ANAH consists of ~12k sentence-level annotations for ~4.3k LLM responses covering over 700 topics, constructed by a human-in-the-loop pipeline. Thanks to the fine granularity of the hallucination annotations, we can quantitatively confirm that the hallucinations of LLMs progressively accumulate in the answer and use ANAH to train and evaluate hallucination annotators. We conduct extensive experiments on studying generative and discriminative annotators and show that, although current open-source LLMs have difficulties in fine-grained hallucination annotation, the generative annotator trained with ANAH can surpass all open-source LLMs and GPT-3.5, obtain performance competitive with GPT-4, and exhibits better generalization ability on unseen questions.

![ANAH：大型语言模型幻觉的深度解析](../../../paper_images/2405.20315/x1.png)

![ANAH：大型语言模型幻觉的深度解析](../../../paper_images/2405.20315/x2.png)

![ANAH：大型语言模型幻觉的深度解析](../../../paper_images/2405.20315/x3.png)

![ANAH：大型语言模型幻觉的深度解析](../../../paper_images/2405.20315/x4.png)

![ANAH：大型语言模型幻觉的深度解析](../../../paper_images/2405.20315/x5.png)

![ANAH：大型语言模型幻觉的深度解析](../../../paper_images/2405.20315/x6.png)

![ANAH：大型语言模型幻觉的深度解析](../../../paper_images/2405.20315/x7.png)

[Arxiv](https://arxiv.org/abs/2405.20315)