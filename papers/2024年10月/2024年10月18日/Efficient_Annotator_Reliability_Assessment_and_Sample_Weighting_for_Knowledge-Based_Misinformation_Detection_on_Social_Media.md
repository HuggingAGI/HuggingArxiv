# 高效评估标注者可靠性，并加权样本，助力社交媒体上的基于知识的错误信息检测

发布时间：2024年10月18日

`RAG` `社交媒体` `错误信息检测`

> Efficient Annotator Reliability Assessment and Sample Weighting for Knowledge-Based Misinformation Detection on Social Media

# 摘要

> 社交媒体上的错误信息传播迅速，混淆视听并针对脆弱人群。为有效应对，需先准确检测错误信息，再采取缓解措施，如X的社区笔记（目前为手动操作）。本研究采用知识驱动方法，将错误信息检测视为自然语言推理问题。我们引入EffiARA注释框架，通过分析注释者间的共识与内部一致性，评估注释可靠性，进而优化大型语言模型的分类训练。为评估EffiARA，我们创建并公开了Russo-Ukrainian冲突知识基础错误信息分类数据集（RUC-MCD）。研究发现，基于注释者可靠性的样本加权法效果最佳，结合了注释者间的共识与内部一致性及软标签训练。使用Llama-3.2-1B和TwHIN-BERT-large分别达到宏观F1的0.757和0.740。

> Misinformation spreads rapidly on social media, confusing the truth and targetting potentially vulnerable people. To effectively mitigate the negative impact of misinformation, it must first be accurately detected before applying a mitigation strategy, such as X's community notes, which is currently a manual process. This study takes a knowledge-based approach to misinformation detection, modelling the problem similarly to one of natural language inference. The EffiARA annotation framework is introduced, aiming to utilise inter- and intra-annotator agreement to understand the reliability of each annotator and influence the training of large language models for classification based on annotator reliability. In assessing the EffiARA annotation framework, the Russo-Ukrainian Conflict Knowledge-Based Misinformation Classification Dataset (RUC-MCD) was developed and made publicly available. This study finds that sample weighting using annotator reliability performs the best, utilising both inter- and intra-annotator agreement and soft-label training. The highest classification performance achieved using Llama-3.2-1B was a macro-F1 of 0.757 and 0.740 using TwHIN-BERT-large.

[Arxiv](https://arxiv.org/abs/2410.14515)