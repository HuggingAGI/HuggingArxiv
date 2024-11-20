# FLAME：冻结大型语言模型助力实现数据高效的语言-图像预训练

发布时间：2024年11月18日

`LLM应用` `计算机视觉`

> FLAME: Frozen Large Language Models Enable Data-Efficient Language-Image Pre-training

# 摘要

> 语言-图像预训练因特定格式数据有限以及文本编码器能力不足而遭遇重大挑战。尽管主流方法尝试通过数据扩充和架构修改来应对这些难题，但在处理长文本输入时仍力不从心，且传统 CLIP 文本编码器的固有局限致使下游泛化效果欠佳。本文提出了 FLAME（冻结大型语言模型实现数据高效的语言-图像预训练），借助冻结的大型语言模型充当文本编码器，可自然处理长文本输入，展现出出色的多语言泛化能力。FLAME 涵盖两个关键部分：其一，一种多面的提示蒸馏技术，能从长标题中提取多样的语义表征，与图像的多面性更适配；其二，一种方面解耦的注意力机制，搭配离线嵌入策略，保障高效计算。大量的实证评估彰显了 FLAME 的卓越性能。于 CC3M 上训练时，FLAME 在 ImageNet top-1 准确率方面比先前的最优水平高出 4.9％。在 YFCC15M 上，FLAME 在 36 种语言的平均图像到文本 recall@1 上比由 WIT-400M 训练的 CLIP 高出 44.4％，在 Urban-1k 上长上下文检索的文本到图像 recall@1 上高出 34.6％。代码可在 url{https://github.com/MIV-XJTU/FLAME}获取。

> Language-image pre-training faces significant challenges due to limited data in specific formats and the constrained capacities of text encoders. While prevailing methods attempt to address these issues through data augmentation and architecture modifications, they continue to struggle with processing long-form text inputs, and the inherent limitations of traditional CLIP text encoders lead to suboptimal downstream generalization. In this paper, we propose FLAME (Frozen Large lAnguage Models Enable data-efficient language-image pre-training) that leverages frozen large language models as text encoders, naturally processing long text inputs and demonstrating impressive multilingual generalization. FLAME comprises two key components: 1) a multifaceted prompt distillation technique for extracting diverse semantic representations from long captions, which better aligns with the multifaceted nature of images, and 2) a facet-decoupled attention mechanism, complemented by an offline embedding strategy, to ensure efficient computation. Extensive empirical evaluations demonstrate FLAME's superior performance. When trained on CC3M, FLAME surpasses the previous state-of-the-art by 4.9\% in ImageNet top-1 accuracy. On YFCC15M, FLAME surpasses the WIT-400M-trained CLIP by 44.4\% in average image-to-text recall@1 across 36 languages, and by 34.6\% in text-to-image recall@1 for long-context retrieval on Urban-1k. Code is available at url{https://github.com/MIV-XJTU/FLAME}.

[Arxiv](https://arxiv.org/abs/2411.11927)