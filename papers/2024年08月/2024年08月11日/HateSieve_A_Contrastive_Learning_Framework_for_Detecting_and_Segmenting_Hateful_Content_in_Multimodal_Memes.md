# HateSieve：一款对比学习框架，专为识别与分割多模态模因中的仇恨内容而设计。

发布时间：2024年08月11日

`LLM应用` `社交媒体` `网络安全`

> HateSieve: A Contrastive Learning Framework for Detecting and Segmenting Hateful Content in Multimodal Memes

# 摘要

> 随着大型多模态模型 (LMMs) 的兴起及其在生成和解释复杂内容中的广泛应用，传播偏见和有害模因的风险依然显著。现有的安全措施往往难以察觉“混淆者模因”中隐含的仇恨内容。为此，我们推出了 \textsc{HateSieve} 框架，旨在提升模因中仇恨元素的检测与分割。该框架包含创新的对比模因生成器、定制的三元组数据集及图像-文本对齐模块，以实现上下文感知的精确分割。实验显示，\textsc{HateSieve} 在性能上超越现有 LMMs，且参数更少，同时提供了一种强大的机制，精准识别并隔离仇恨内容。\textcolor{red}{注意：内容涉及仇恨言论的学术探讨，观众请谨慎阅读。}

> Amidst the rise of Large Multimodal Models (LMMs) and their widespread application in generating and interpreting complex content, the risk of propagating biased and harmful memes remains significant. Current safety measures often fail to detect subtly integrated hateful content within ``Confounder Memes''. To address this, we introduce \textsc{HateSieve}, a new framework designed to enhance the detection and segmentation of hateful elements in memes. \textsc{HateSieve} features a novel Contrastive Meme Generator that creates semantically paired memes, a customized triplet dataset for contrastive learning, and an Image-Text Alignment module that produces context-aware embeddings for accurate meme segmentation. Empirical experiments on the Hateful Meme Dataset show that \textsc{HateSieve} not only surpasses existing LMMs in performance with fewer trainable parameters but also offers a robust mechanism for precisely identifying and isolating hateful content. \textcolor{red}{Caution: Contains academic discussions of hate speech; viewer discretion advised.}

[Arxiv](https://arxiv.org/abs/2408.05794)