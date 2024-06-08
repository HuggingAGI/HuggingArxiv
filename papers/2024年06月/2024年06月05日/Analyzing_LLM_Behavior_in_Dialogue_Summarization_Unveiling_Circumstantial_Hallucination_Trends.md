# 探究大型语言模型在对话摘要中的行为，揭秘情境性幻觉的演变趋势

发布时间：2024年06月05日

`LLM应用

这篇论文主要关注大型语言模型（LLMs）在对话摘要中的应用，特别是在评估其忠实度方面的问题。论文通过人工标注和分析，探讨了LLMs在对话摘要中产生的不一致性，特别是GPT-4和Alpaca-13B模型。此外，论文还提出了新的错误分类，并开发了基于提示的细粒度错误检测方法，以改善自动错误检测的效果。这些内容主要涉及LLMs的实际应用和评估，因此归类为LLM应用。` `对话摘要`

> Analyzing LLM Behavior in Dialogue Summarization: Unveiling Circumstantial Hallucination Trends

# 摘要

> 大型语言模型（LLMs）的进步将摘要系统推向新高度，但幻觉问题依旧困扰着它们。尽管新闻领域的LLMs评估已相当广泛，对话摘要的忠实度评估却多聚焦于BART模型，留下了认知的空白。本研究通过人工标注，专注于对话摘要中跨度级别的不一致性，来评估LLMs的忠实度，特别关注了GPT-4和Alpaca-13B。我们发现，LLMs常产生看似合理却缺乏直接证据的推断，这在旧模型中较为罕见。为此，我们提出了新的错误分类，并创造了“间接推断”类别，同时发布了相关数据集。通过这一分类，我们揭示了LLMs与旧模型在行为上的差异，并发现自动错误检测方法在处理这些细微错误时显得力不从心。为此，我们开发了两种基于提示的细粒度错误检测方法，它们在识别“间接推断”方面表现出色，超越了现有指标。

> Recent advancements in large language models (LLMs) have considerably advanced the capabilities of summarization systems. However, they continue to face concerns about hallucinations. While prior work has evaluated LLMs extensively in news domains, most evaluation of dialogue summarization has focused on BART-based models, leaving a gap in our understanding of their faithfulness. Our work benchmarks the faithfulness of LLMs for dialogue summarization, using human annotations and focusing on identifying and categorizing span-level inconsistencies. Specifically, we focus on two prominent LLMs: GPT-4 and Alpaca-13B. Our evaluation reveals subtleties as to what constitutes a hallucination: LLMs often generate plausible inferences, supported by circumstantial evidence in the conversation, that lack direct evidence, a pattern that is less prevalent in older models. We propose a refined taxonomy of errors, coining the category of "Circumstantial Inference" to bucket these LLM behaviors and release the dataset. Using our taxonomy, we compare the behavioral differences between LLMs and older fine-tuned models. Additionally, we systematically assess the efficacy of automatic error detection methods on LLM summaries and find that they struggle to detect these nuanced errors. To address this, we introduce two prompt-based approaches for fine-grained error detection that outperform existing metrics, particularly for identifying "Circumstantial Inference."

![探究大型语言模型在对话摘要中的行为，揭秘情境性幻觉的演变趋势](../../../paper_images/2406.03487/x1.png)

![探究大型语言模型在对话摘要中的行为，揭秘情境性幻觉的演变趋势](../../../paper_images/2406.03487/x2.png)

![探究大型语言模型在对话摘要中的行为，揭秘情境性幻觉的演变趋势](../../../paper_images/2406.03487/x3.png)

![探究大型语言模型在对话摘要中的行为，揭秘情境性幻觉的演变趋势](../../../paper_images/2406.03487/x4.png)

![探究大型语言模型在对话摘要中的行为，揭秘情境性幻觉的演变趋势](../../../paper_images/2406.03487/x5.png)

![探究大型语言模型在对话摘要中的行为，揭秘情境性幻觉的演变趋势](../../../paper_images/2406.03487/x6.png)

![探究大型语言模型在对话摘要中的行为，揭秘情境性幻觉的演变趋势](../../../paper_images/2406.03487/x7.png)

![探究大型语言模型在对话摘要中的行为，揭秘情境性幻觉的演变趋势](../../../paper_images/2406.03487/x8.png)

[Arxiv](https://arxiv.org/abs/2406.03487)