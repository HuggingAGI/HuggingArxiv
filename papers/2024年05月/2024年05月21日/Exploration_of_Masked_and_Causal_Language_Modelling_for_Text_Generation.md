# 探究掩码与因果语言建模在文本生成领域的应用

发布时间：2024年05月21日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）中的两种不同的语言建模方法——因果语言建模（CLM）和掩码语言建模（MLM），并比较了它们在文本生成任务上的表现。这种比较和分析属于对LLM理论的深入研究，因为它关注的是模型内部的机制和方法论，而不是直接的应用或特定的安全问题。此外，论文通过实验评估了不同模型在特定任务上的性能，这进一步强化了其理论研究的性质。因此，这篇论文应归类为LLM理论。`

> Exploration of Masked and Causal Language Modelling for Text Generation

# 摘要

> 大型语言模型（LLMs）已彻底革新了自然语言处理（NLP）领域，几乎在所有任务中都达到了顶尖水平。然而，当前文本生成的主流方法——因果语言建模（CLM），其从左至右的顺序生成方式，限制了模型的灵活性。相反，掩码语言建模（MLM），主要用于语言理解任务，允许令牌在文本中任意位置和顺序生成。本文深入比较了MLM与CLM在文本生成任务上的表现。我们预先训练了多个大小相当的语言模型，涵盖三个数据集：医疗出院摘要、电影情节梗概和作者验证数据集。评估生成文本的质量时，我们首先采用定量指标，随后进行人类评估，分析文本的连贯性和语法正确性。此外，我们还通过三个下游任务——实体识别、文本分类和作者验证——来检验生成文本的实用性。结果显示，MLM在所有数据集上的文本生成中均优于CLM，不仅定量得分更高，生成的文本也更连贯。研究还发现，生成文本的质量与模型在下游任务中的表现并无明显关联。本研究揭示了MLM在文本生成领域的巨大潜力，并为未来的研究指明了方向。

> Large Language Models (LLMs) have revolutionised the field of Natural Language Processing (NLP) and have achieved state-of-the-art performance in practically every task in this field. However, the prevalent approach used in text generation, Causal Language Modelling (CLM), which generates text sequentially from left to right, inherently limits the freedom of the model, which does not decide when and where each token is generated. In contrast, Masked Language Modelling (MLM), primarily used for language understanding tasks, can generate tokens anywhere in the text and any order. This paper conducts an extensive comparison of MLM and CLM approaches for text generation tasks. To do so, we pre-train several language models of comparable sizes on three different datasets, namely 1) medical discharge summaries, 2) movie plot synopses, and 3) authorship verification datasets. To assess the quality of the generations, we first employ quantitative metrics and then perform a qualitative human evaluation to analyse coherence and grammatical correctness. In addition, we evaluate the usefulness of the generated texts by using them in three different downstream tasks: 1) Entity Recognition, 2) Text Classification, and 3) Authorship Verification. The results show that MLM consistently outperforms CLM in text generation across all datasets, with higher quantitative scores and better coherence in the generated text. The study also finds \textit{no strong correlation} between the quality of the generated text and the performance of the models in the downstream tasks. With this study, we show that MLM for text generation has great potential for future research and provides direction for future studies in this area.

[Arxiv](https://arxiv.org/abs/2405.12630)