# 在资源匮乏的语言中识别讽刺

发布时间：2024年10月16日

`LLM应用` `情感分析`

> Sarcasm Detection in a Less-Resourced Language

# 摘要

> 讽刺检测任务在自然语言处理中旨在判断话语是否带有讽刺意味，这与情感分析紧密相关，因为讽刺往往反转表面情感。讽刺句高度依赖上下文，且常伴有非语言线索，因此颇具挑战。现有研究多聚焦于英语等高资源语言。为斯洛文尼亚语等低资源语言构建讽刺检测数据集，我们采用了两种前沿技术：专用于机器翻译的中型变压器模型和庞大的生成语言模型。我们探究了翻译数据集的可行性，并分析了预训练变压器模型大小对讽刺检测能力的影响。通过训练多个检测模型并评估其性能，我们发现大模型普遍优于小模型，而模型集成能小幅提升检测效果。最佳集成方法的F1分数达到0.765，接近源语言标注者的一致性水平。

> The sarcasm detection task in natural language processing tries to classify whether an utterance is sarcastic or not. It is related to sentiment analysis since it often inverts surface sentiment. Because sarcastic sentences are highly dependent on context, and they are often accompanied by various non-verbal cues, the task is challenging. Most of related work focuses on high-resourced languages like English. To build a sarcasm detection dataset for a less-resourced language, such as Slovenian, we leverage two modern techniques: a machine translation specific medium-size transformer model, and a very large generative language model. We explore the viability of translated datasets and how the size of a pretrained transformer affects its ability to detect sarcasm. We train ensembles of detection models and evaluate models' performance. The results show that larger models generally outperform smaller ones and that ensembling can slightly improve sarcasm detection performance. Our best ensemble approach achieves an $\text{F}_1$-score of 0.765 which is close to annotators' agreement in the source language.

[Arxiv](https://arxiv.org/abs/2410.12704)