# 利用任务中的所有可用信息，提升少样本文本分类的元学习效果

发布时间：2024年10月14日

`其他` `文本分类` `机器学习`

> Improve Meta-learning for Few-Shot Text Classification with All You Can Acquire from the Tasks

# 摘要

> 元学习在少样本文本分类中表现出色，但现有方法在提取准确类别原型时面临挑战，主要因类内差异大、类间差异小。近期方法尝试引入外部知识或预训练模型，但需额外资源，不适用于少样本场景。本文提出新方案，利用任务内信息，通过标签构建自适应度量空间，减少类内差异，放大类间差异。结合最优传输技术，与查询集样本共同估计原型，解决支持集样本不准确问题。实验表明，该方法在八个基准数据集上均优于现有模型。代码和数据集见 https://github.com/YvoGao/LAQDA。

> Meta-learning has emerged as a prominent technology for few-shot text classification and has achieved promising performance. However, existing methods often encounter difficulties in drawing accurate class prototypes from support set samples, primarily due to probable large intra-class differences and small inter-class differences within the task. Recent approaches attempt to incorporate external knowledge or pre-trained language models to augment data, but this requires additional resources and thus does not suit many few-shot scenarios. In this paper, we propose a novel solution to address this issue by adequately leveraging the information within the task itself. Specifically, we utilize label information to construct a task-adaptive metric space, thereby adaptively reducing the intra-class differences and magnifying the inter-class differences. We further employ the optimal transport technique to estimate class prototypes with query set samples together, mitigating the problem of inaccurate and ambiguous support set samples caused by large intra-class differences. We conduct extensive experiments on eight benchmark datasets, and our approach shows obvious advantages over state-of-the-art models across all the tasks on all the datasets. For reproducibility, all the datasets and codes are available at https://github.com/YvoGao/LAQDA.

[Arxiv](https://arxiv.org/abs/2410.10454)