# MICL：借助演示中的多标签词优化情境学习

发布时间：2024年06月16日

`LLM应用

这篇论文主要关注于如何通过优化样本-标签对中的标签词选择来提升大型语言模型（LLM）在样本引导学习（ICL）中的性能。论文提出了一种新的方法，即在样本-标签对中使用多个标签词，并根据LLM的输出分布精心挑选和排序这些对，以优化演示效果。这种方法的目的是通过策略性地组织标签词的选择、顺序和数量，利用多样化的标签信息来提高ICL的性能。因此，这篇论文属于LLM应用类别，因为它探讨了如何应用LLM来改进特定的机器学习任务（即样本引导学习）。` `机器学习`

> MICL: Improving In-Context Learning through Multiple-Label Words in Demonstration

# 摘要

> ICL 通过样本-标签对演示，让 LLMs 掌握新任务。但演示的差异会导致性能大相径庭。现有研究多聚焦于样本选择，默认类别名作为标签词。然而，标签词的选择对 ICL 至关重要。我们发现，单一类别名可能并非最佳选择。因此，本文提出在样本-标签对中采用多个标签词，以提升 ICL 性能。同时，我们依据 LLM 输出分布，精心挑选和排序样本-标签对，力求从样本和标签两方面优化演示。对七个分类数据集的评估显示，通过策略性地组织标签词的选择、顺序和数量，利用多样化的标签信息，有效提升了 ICL 性能。

> In-context learning (ICL) enables large language models (LLMs) to perform new tasks by using sample-label pairs as demonstrations. However, variations in demonstrations can lead to significantly different performances. Current research mainly focuses on selecting demonstration samples, preassuming the class name to be the label word when creating sample-label pairs. However, the choice of label words is crucial for ICL performance. In addition, we observe that using a single class name in demonstration may not yield optimal results. In this paper, we propose to use multiple label words in one sample-label pair to enhance ICL performance. Further, we select and order sample-label pairs based on LLM's output distribution, aiming to optimize the demonstration examples from both the samples' and labels' perspectives. Evaluation results on seven classification datasets show that the use of multiple label words, strategically organized by their selection, order and quantity, improves ICL performance through diverse label information.

![MICL：借助演示中的多标签词优化情境学习](../../../paper_images/2406.10908/x1.png)

![MICL：借助演示中的多标签词优化情境学习](../../../paper_images/2406.10908/x2.png)

![MICL：借助演示中的多标签词优化情境学习](../../../paper_images/2406.10908/x3.png)

![MICL：借助演示中的多标签词优化情境学习](../../../paper_images/2406.10908/x4.png)

![MICL：借助演示中的多标签词优化情境学习](../../../paper_images/2406.10908/x5.png)

![MICL：借助演示中的多标签词优化情境学习](../../../paper_images/2406.10908/x6.png)

![MICL：借助演示中的多标签词优化情境学习](../../../paper_images/2406.10908/x7.png)

![MICL：借助演示中的多标签词优化情境学习](../../../paper_images/2406.10908/x8.png)

![MICL：借助演示中的多标签词优化情境学习](../../../paper_images/2406.10908/x9.png)

![MICL：借助演示中的多标签词优化情境学习](../../../paper_images/2406.10908/x10.png)

![MICL：借助演示中的多标签词优化情境学习](../../../paper_images/2406.10908/x11.png)

![MICL：借助演示中的多标签词优化情境学习](../../../paper_images/2406.10908/x12.png)

![MICL：借助演示中的多标签词优化情境学习](../../../paper_images/2406.10908/x13.png)

![MICL：借助演示中的多标签词优化情境学习](../../../paper_images/2406.10908/x14.png)

![MICL：借助演示中的多标签词优化情境学习](../../../paper_images/2406.10908/x15.png)

![MICL：借助演示中的多标签词优化情境学习](../../../paper_images/2406.10908/x16.png)

[Arxiv](https://arxiv.org/abs/2406.10908)