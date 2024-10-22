# AMPLE：情感感知的多模态融合提示学习，专为假新闻检测而生。

发布时间：2024年10月20日

`LLM应用` `社交媒体`

> AMPLE: Emotion-Aware Multimodal Fusion Prompt Learning for Fake News Detection

# 摘要

> 假新闻检测因其多样性和复杂性而充满挑战，传统方法多聚焦于文本特征，却忽视了语义和情感元素。当前方法依赖大量标注数据，限制了其在细致分析中的表现。为此，本文提出 Emotion-**A**ware **M**ultimodal Fusion **P**rompt **L**earning (**AMPLE**) 框架，结合文本情感分析、多模态数据和混合提示模板，从文本中提取情感元素，并通过多头交叉注意力机制和相似性感知融合方法整合多模态数据。AMPLE 框架在两个公共数据集上表现出色，显示出情感元素在假新闻检测中的潜力。研究还探讨了结合大型语言模型进行文本情感提取的可能性，发现仍有巨大改进空间。代码链接 :\url{https://github.com/xxm1215/MMM2025_few-shot/}。

> Detecting fake news in large datasets is challenging due to its diversity and complexity, with traditional approaches often focusing on textual features while underutilizing semantic and emotional elements. Current methods also rely heavily on large annotated datasets, limiting their effectiveness in more nuanced analysis. To address these challenges, this paper introduces Emotion-\textbf{A}ware \textbf{M}ultimodal Fusion \textbf{P}rompt \textbf{L}\textbf{E}arning (\textbf{AMPLE}) framework to address the above issue by combining text sentiment analysis with multimodal data and hybrid prompt templates. This framework extracts emotional elements from texts by leveraging sentiment analysis tools. It then employs Multi-Head Cross-Attention (MCA) mechanisms and similarity-aware fusion methods to integrate multimodal data. The proposed AMPLE framework demonstrates strong performance on two public datasets in both few-shot and data-rich settings, with results indicating the potential of emotional aspects in fake news detection. Furthermore, the study explores the impact of integrating large language models with this method for text sentiment extraction, revealing substantial room for further improvement. The code can be found at :\url{https://github.com/xxm1215/MMM2025_few-shot/

[Arxiv](https://arxiv.org/abs/2410.15591)