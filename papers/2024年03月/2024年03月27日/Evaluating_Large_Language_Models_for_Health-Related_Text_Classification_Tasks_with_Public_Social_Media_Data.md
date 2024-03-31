# 本研究利用公共社交媒体数据，对大型语言模型在健康相关文本分类任务中的表现进行评估。

发布时间：2024年03月27日

`LLM应用` `社交媒体` `健康信息分析`

> Evaluating Large Language Models for Health-Related Text Classification Tasks with Public Social Media Data

# 摘要

> 大型语言模型（LLMs）在自然语言处理（NLP）任务上取得了卓越成就。但针对社交媒体健康相关文本的分析，这类任务通常难以获得高分，相关研究却寥寥无几。我们对六项文本分类任务进行了评估，包括一个基于支持向量机（SVMs）的监督式经典机器学习模型、三个基于RoBERTa、BERTweet和SocBERT的预训练语言模型（PLMs），以及GPT3.5和GPT4两个LLM分类器。我们提出了三种利用LLMs进行文本分类的方法：直接使用LLMs作为零-shot分类器，让LLMs充当注释工具来标注训练数据，以及用少量样本的LLMs增强手动注释的数据。综合实验显示，结合少量人工注释数据，运用LLMs（GPT-4）进行数据增强，能够训练出比单独使用人工数据更优秀的轻量级监督模型。在零-shot场景下，监督学习器同样超越了GPT-4和GPT-3.5。通过这种数据增强策略，我们可以充分利用LLMs的能力，打造更小巧、更高效的特定领域NLP模型。然而，未经人工指导的LLM注释数据在训练轻量级监督模型方面效果不佳。尽管如此，作为零-shot分类器的LLM在筛除假阴性结果和可能降低人工注释负担方面仍具有潜力。未来的研究亟需确定最优的训练数据量和最佳的数据增强比例。

> Large language models (LLMs) have demonstrated remarkable success in NLP tasks. However, there is a paucity of studies that attempt to evaluate their performances on social media-based health-related natural language processing tasks, which have traditionally been difficult to achieve high scores in. We benchmarked one supervised classic machine learning model based on Support Vector Machines (SVMs), three supervised pretrained language models (PLMs) based on RoBERTa, BERTweet, and SocBERT, and two LLM based classifiers (GPT3.5 and GPT4), across 6 text classification tasks. We developed three approaches for leveraging LLMs for text classification: employing LLMs as zero-shot classifiers, us-ing LLMs as annotators to annotate training data for supervised classifiers, and utilizing LLMs with few-shot examples for augmentation of manually annotated data. Our comprehensive experiments demonstrate that employ-ing data augmentation using LLMs (GPT-4) with relatively small human-annotated data to train lightweight supervised classification models achieves superior results compared to training with human-annotated data alone. Supervised learners also outperform GPT-4 and GPT-3.5 in zero-shot settings. By leveraging this data augmentation strategy, we can harness the power of LLMs to develop smaller, more effective domain-specific NLP models. LLM-annotated data without human guidance for training light-weight supervised classification models is an ineffective strategy. However, LLM, as a zero-shot classifier, shows promise in excluding false negatives and potentially reducing the human effort required for data annotation. Future investigations are imperative to explore optimal training data sizes and the optimal amounts of augmented data.

[Arxiv](https://arxiv.org/abs/2403.19031)