# Nob-MIAs：针对大型语言模型，通过事后数据集构建，进行无偏见的成员推理攻击评估。

发布时间：2024年08月12日

`LLM理论`

> Nob-MIAs: Non-biased Membership Inference Attacks Assessment on Large Language Models with Ex-Post Dataset Construction

# 摘要

> 随着大型语言模型（LLM）的兴起，法律和伦理问题也随之而来，尤其是训练数据集中未经授权使用版权材料的问题。这引发了针对未经许可使用受保护内容的科技公司的诉讼。成员推理攻击（MIA）试图检测特定文档是否被用于LLM的预训练，但其有效性受到时间偏移和n-gram重叠等偏见的影响。本文在承认成员与非成员数据集间固有偏差的事后假设下，评估了具有部分可推断训练集的LLM上的MIA。我们提出并验证了创建“无偏见”和“不可分类”数据集的算法，以实现更公平的MIA评估。实验显示，仅消除已知偏见是不够的。我们的方法生成了无偏见的事后数据集，其AUC-ROC分数与之前在真正随机数据集上获得的分数相当，验证了我们的方法。总体而言，MIA的结果接近随机，仅有一种在随机和我们的数据集上都有效，但其性能在消除偏见时下降。

> The rise of Large Language Models (LLMs) has triggered legal and ethical concerns, especially regarding the unauthorized use of copyrighted materials in their training datasets. This has led to lawsuits against tech companies accused of using protected content without permission. Membership Inference Attacks (MIAs) aim to detect whether specific documents were used in a given LLM pretraining, but their effectiveness is undermined by biases such as time-shifts and n-gram overlaps.
  This paper addresses the evaluation of MIAs on LLMs with partially inferable training sets, under the ex-post hypothesis, which acknowledges inherent distributional biases between members and non-members datasets. We propose and validate algorithms to create ``non-biased'' and ``non-classifiable'' datasets for fairer MIA assessment. Experiments using the Gutenberg dataset on OpenLamma and Pythia show that neutralizing known biases alone is insufficient. Our methods produce non-biased ex-post datasets with AUC-ROC scores comparable to those previously obtained on genuinely random datasets, validating our approach. Globally, MIAs yield results close to random, with only one being effective on both random and our datasets, but its performance decreases when bias is removed.

[Arxiv](https://arxiv.org/abs/2408.05968)