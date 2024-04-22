# SOS-1K：专为中文社交媒体分析设计的细致自杀风险分类数据集

发布时间：2024年04月19日

`LLM应用` `社交媒体分析` `心理健康`

> SOS-1K: A Fine-grained Suicide Risk Classification Dataset for Chinese Social Media Analysis

# 摘要

> 社交媒体用户常表露个人情感，其中某些表达可能暗示着自杀风险。网络语言的隐晦多样使得迅速准确识别社交媒体上的自杀意图变得困难，这对及时干预构成了挑战。深度学习模型在自杀风险检测上展现出潜力，但中文相关数据集的缺乏尤为突出。本研究填补了这一空白，推出了一个中文社交媒体数据集，专注于自杀意图、方法和紧迫性等细粒度分类指标。在评估的七个预训练模型中，深度学习模型在高风险与低风险自杀风险区分上表现优异，最高F1得分达88.39%，但在细粒度分类上仍有提升空间，加权F1得分为50.89%。为应对数据不平衡和数据集规模限制，我们探索了传统与基于大型语言模型的先进数据增强技术，发现数据增强可提升模型性能，最高可增加4.65%的F1得分。特别值得一提的是，基于心理学领域数据预训练的Chinese MentalBERT模型，在两项任务中均表现卓越。本研究为社交媒体平台上自杀个体的自动识别提供了重要见解，有助于实现及时的心理干预。研究的源代码和数据已对公众开放。

> In the social media, users frequently express personal emotions, a subset of which may indicate potential suicidal tendencies. The implicit and varied forms of expression in internet language complicate accurate and rapid identification of suicidal intent on social media, thus creating challenges for timely intervention efforts. The development of deep learning models for suicide risk detection is a promising solution, but there is a notable lack of relevant datasets, especially in the Chinese context. To address this gap, this study presents a Chinese social media dataset designed for fine-grained suicide risk classification, focusing on indicators such as expressions of suicide intent, methods of suicide, and urgency of timing. Seven pre-trained models were evaluated in two tasks: high and low suicide risk, and fine-grained suicide risk classification on a level of 0 to 10. In our experiments, deep learning models show good performance in distinguishing between high and low suicide risk, with the best model achieving an F1 score of 88.39%. However, the results for fine-grained suicide risk classification were still unsatisfactory, with an weighted F1 score of 50.89%. To address the issues of data imbalance and limited dataset size, we investigated both traditional and advanced, large language model based data augmentation techniques, demonstrating that data augmentation can enhance model performance by up to 4.65% points in F1-score. Notably, the Chinese MentalBERT model, which was pre-trained on psychological domain data, shows superior performance in both tasks. This study provides valuable insights for automatic identification of suicidal individuals, facilitating timely psychological intervention on social media platforms. The source code and data are publicly available.

[Arxiv](https://arxiv.org/abs/2404.12659)