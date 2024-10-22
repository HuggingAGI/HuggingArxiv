# AMPLE：情感感知的多模态融合提示学习，专为假新闻检测而生

发布时间：2024年10月20日

`LLM应用` `人工智能`

> AMPLE: Emotion-Aware Multimodal Fusion Prompt Learning for Fake News Detection

# 摘要

> 假新闻检测因其多样性和复杂性而充满挑战，传统方法多聚焦于文本特征，忽视了语义和情感元素。当前方法依赖大型标注数据集，限制了其在细致分析中的表现。为此，本文提出 Emotion-**A**ware **M**ultimodal Fusion **P**rompt **L**earning (**AMPLE**) 框架，结合文本情感分析、多模态数据和混合提示模板，提取情感元素并整合多模态数据。AMPLE 框架在少样本和数据丰富场景下均表现出色，揭示了情感在假新闻检测中的潜力。研究还探讨了大型语言模型在文本情感提取中的应用，发现仍有巨大改进空间。代码详见 :\url{https://github.com/xxm1215/MMM2025_few-shot/}。

> Detecting fake news in large datasets is challenging due to its diversity and complexity, with traditional approaches often focusing on textual features while underutilizing semantic and emotional elements. Current methods also rely heavily on large annotated datasets, limiting their effectiveness in more nuanced analysis. To address these challenges, this paper introduces Emotion-\textbf{A}ware \textbf{M}ultimodal Fusion \textbf{P}rompt \textbf{L}\textbf{E}arning (\textbf{AMPLE}) framework to address the above issue by combining text sentiment analysis with multimodal data and hybrid prompt templates. This framework extracts emotional elements from texts by leveraging sentiment analysis tools. It then employs Multi-Head Cross-Attention (MCA) mechanisms and similarity-aware fusion methods to integrate multimodal data. The proposed AMPLE framework demonstrates strong performance on two public datasets in both few-shot and data-rich settings, with results indicating the potential of emotional aspects in fake news detection. Furthermore, the study explores the impact of integrating large language models with this method for text sentiment extraction, revealing substantial room for further improvement. The code can be found at :\url{https://github.com/xxm1215/MMM2025_few-shot/

[Arxiv](https://arxiv.org/abs/2410.15591)