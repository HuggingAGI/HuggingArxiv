# MBBQ：探索生成型大型语言模型中刻板印象的跨语言比较数据集

发布时间：2024年06月11日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLMs）在多语言环境下的偏见和刻板印象问题，并提出了一个多语言偏见基准问答（MBBQ）数据集来评估和比较不同语言中的偏见情况。这属于对LLMs在实际应用中的问题进行研究和改进的范畴，因此归类为LLM应用。` `人工智能` `语言处理`

> MBBQ: A Dataset for Cross-Lingual Comparison of Stereotypes in Generative LLMs

# 摘要

> 生成型大型语言模型（LLMs）存在有害偏见和刻板印象，尽管安全微调主要针对英语，但这些模型正被多语言用户广泛使用。研究表明，LLMs在不同语言中的表现不一，且会根据用户的人口统计特征产生歧视。为此，我们探讨了LLMs所展现的社会刻板印象是否因语言而异，同时考虑了文化差异和任务准确性。我们精心策划了MBBQ（多语言偏见基准问答），将英语BBQ数据集扩展至荷兰语、西班牙语和土耳其语，用以评估这些语言中普遍的刻板印象。此外，我们通过平行控制数据集独立评估问答任务的性能，不受偏见影响。研究结果显示，一些非英语语言在偏见方面比英语更严重，即使在考虑文化差异的情况下。我们还发现，除了最准确的模型外，其他模型在偏见行为上存在显著的跨语言差异。我们希望通过发布MBBQ，推动多语言环境中偏见研究的深入。数据集和代码已公开于https://github.com/Veranep/MBBQ。

> Generative large language models (LLMs) have been shown to exhibit harmful biases and stereotypes. While safety fine-tuning typically takes place in English, if at all, these models are being used by speakers of many different languages. There is existing evidence that the performance of these models is inconsistent across languages and that they discriminate based on demographic factors of the user. Motivated by this, we investigate whether the social stereotypes exhibited by LLMs differ as a function of the language used to prompt them, while controlling for cultural differences and task accuracy. To this end, we present MBBQ (Multilingual Bias Benchmark for Question-answering), a carefully curated version of the English BBQ dataset extended to Dutch, Spanish, and Turkish, which measures stereotypes commonly held across these languages. We further complement MBBQ with a parallel control dataset to measure task performance on the question-answering task independently of bias. Our results based on several open-source and proprietary LLMs confirm that some non-English languages suffer from bias more than English, even when controlling for cultural shifts. Moreover, we observe significant cross-lingual differences in bias behaviour for all except the most accurate models. With the release of MBBQ, we hope to encourage further research on bias in multilingual settings. The dataset and code are available at https://github.com/Veranep/MBBQ.

![MBBQ：探索生成型大型语言模型中刻板印象的跨语言比较数据集](../../../paper_images/2406.07243/x1.png)

![MBBQ：探索生成型大型语言模型中刻板印象的跨语言比较数据集](../../../paper_images/2406.07243/x2.png)

![MBBQ：探索生成型大型语言模型中刻板印象的跨语言比较数据集](../../../paper_images/2406.07243/x3.png)

![MBBQ：探索生成型大型语言模型中刻板印象的跨语言比较数据集](../../../paper_images/2406.07243/x4.png)

[Arxiv](https://arxiv.org/abs/2406.07243)