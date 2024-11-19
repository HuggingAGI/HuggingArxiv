# LLM 标注用于数据集标注的机遇与挑战：以媒体偏见检测为例

发布时间：2024年11月17日

`LLM应用` `文本分类`

> The Promises and Pitfalls of LLM Annotations in Dataset Labeling: a Case Study on Media Bias Detection

# 摘要

> 高额的雇佣或众包标注费用，让创建训练可靠文本分类器所需的大型、优质数据集变得困难重重。近期研究提出利用大型语言模型（LLMs）来实现标注过程的自动化，既能降低成本，又能保证数据质量。LLMs 在诸如仇恨言论检测和政治框架等下游任务的标注中成果斐然。基于这些领域的成功经验，本研究探索了 LLMs 能否胜任媒体偏见检测这一复杂任务的标注工作，以及能否基于此类数据训练下游的媒体偏见分类器。我们创建了 annolexical，这是首个用于媒体偏见分类的大规模数据集，包含超过 48000 个合成标注示例。在这个数据集上微调的分类器，在马修斯相关系数（MCC）方面比所有标注器 LLMs 高出 5 - 9%，在两个媒体偏见基准数据集（BABE 和 BASIL）上进行评估时，表现接近或优于基于人工标注数据训练的模型。本研究表明，我们的方法大幅降低了媒体偏见领域中创建数据集的成本，进而降低了分类器的开发成本，而后续的行为压力测试也揭示了其当前存在的一些局限性和权衡之处。

> High annotation costs from hiring or crowdsourcing complicate the creation of large, high-quality datasets needed for training reliable text classifiers. Recent research suggests using Large Language Models (LLMs) to automate the annotation process, reducing these costs while maintaining data quality. LLMs have shown promising results in annotating downstream tasks like hate speech detection and political framing. Building on the success in these areas, this study investigates whether LLMs are viable for annotating the complex task of media bias detection and whether a downstream media bias classifier can be trained on such data. We create annolexical, the first large-scale dataset for media bias classification with over 48000 synthetically annotated examples. Our classifier, fine-tuned on this dataset, surpasses all of the annotator LLMs by 5-9 percent in Matthews Correlation Coefficient (MCC) and performs close to or outperforms the model trained on human-labeled data when evaluated on two media bias benchmark datasets (BABE and BASIL). This study demonstrates how our approach significantly reduces the cost of dataset creation in the media bias domain and, by extension, the development of classifiers, while our subsequent behavioral stress-testing reveals some of its current limitations and trade-offs.

[Arxiv](https://arxiv.org/abs/2411.11081)