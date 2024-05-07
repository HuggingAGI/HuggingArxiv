# 释放已知类别：通过生成锚点和重新构建分类框架，增强少样本与零样本文本分类的性能。

发布时间：2024年05月06日

`分类：LLM应用` `文本分类` `机器学习`

> Liberating Seen Classes: Boosting Few-Shot and Zero-Shot Text Classification via Anchor Generation and Classification Reframing

# 摘要

> 少样本与零样本文本分类致力于在有限或无标记样本的情况下，识别新类别的样本。尽管现有技术通过知识迁移展现出潜力，但仍面临两大挑战：一是类别间的本质差异导致特征转换困难且效率低下；二是稀缺的标记新样本难以为模型提供足够的监督信号以适应复杂场景中的分布变化。为应对这些挑战，我们提出了一种简洁高效的策略。该策略旨在打破模型对已知类别的依赖，使其无需先前训练即可对未见类别进行预测。具体而言，我们使用大型预训练语言模型生成伪新样本，挑选出具有代表性的样本作为类别锚点。随后，我们将多类分类问题转化为二元分类问题，并利用查询与锚点对的相似度进行预测，以最大化利用有限的监督信号。在六个广泛使用的公共数据集上的实验结果表明，我们的方法在少样本和零样本任务中显著超越了其他强有力基准，即便在不依赖任何已知类别样本的情况下。

> Few-shot and zero-shot text classification aim to recognize samples from novel classes with limited labeled samples or no labeled samples at all. While prevailing methods have shown promising performance via transferring knowledge from seen classes to unseen classes, they are still limited by (1) Inherent dissimilarities among classes make the transformation of features learned from seen classes to unseen classes both difficult and inefficient. (2) Rare labeled novel samples usually cannot provide enough supervision signals to enable the model to adjust from the source distribution to the target distribution, especially for complicated scenarios. To alleviate the above issues, we propose a simple and effective strategy for few-shot and zero-shot text classification. We aim to liberate the model from the confines of seen classes, thereby enabling it to predict unseen categories without the necessity of training on seen classes. Specifically, for mining more related unseen category knowledge, we utilize a large pre-trained language model to generate pseudo novel samples, and select the most representative ones as category anchors. After that, we convert the multi-class classification task into a binary classification task and use the similarities of query-anchor pairs for prediction to fully leverage the limited supervision signals. Extensive experiments on six widely used public datasets show that our proposed method can outperform other strong baselines significantly in few-shot and zero-shot tasks, even without using any seen class samples.

[Arxiv](https://arxiv.org/abs/2405.03565)