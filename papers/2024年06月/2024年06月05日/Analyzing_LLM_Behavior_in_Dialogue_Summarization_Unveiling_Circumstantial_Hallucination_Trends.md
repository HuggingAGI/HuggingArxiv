# 探究大型语言模型在对话摘要中的行为，揭秘情境性幻觉的演变趋势

发布时间：2024年06月05日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在对话摘要中的应用，特别是在忠实度和错误检测方面的挑战。研究通过人工标注和错误分类，评估了LLMs在对话摘要中的性能，并提出了新的错误分类和检测方法。这与LLM的实际应用场景紧密相关，因此归类为LLM应用。` `对话摘要`

> Analyzing LLM Behavior in Dialogue Summarization: Unveiling Circumstantial Hallucination Trends

# 摘要

> 大型语言模型（LLMs）的进步已经显著提升了摘要系统的性能，但仍面临幻觉问题的挑战。尽管已有研究广泛评估了LLMs在新闻领域的性能，对话摘要的评估却多集中在基于BART的模型上，这导致我们对LLMs忠实度的理解存在空白。本研究通过人工标注，专注于识别和分类对话中的不一致性，来评估LLMs在对话摘要中的忠实度，特别关注了GPT-4和Alpaca-13B两个模型。我们发现，LLMs常产生看似合理但缺乏直接证据的推断，这在旧模型中较少见。为此，我们提出了新的错误分类，并创造了“间接推断”类别，同时发布了相关数据集。通过这一分类，我们比较了LLMs与旧模型的行为差异，并发现自动错误检测方法在处理这些细微错误时效果不佳。为此，我们开发了两种基于提示的细粒度错误检测方法，它们在识别“间接推断”方面表现出色。

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