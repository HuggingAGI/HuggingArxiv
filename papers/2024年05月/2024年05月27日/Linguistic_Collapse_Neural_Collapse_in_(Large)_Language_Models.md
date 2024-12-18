# 语言模型危机：探究大型语言模型中的神经崩溃现象

发布时间：2024年05月27日

`LLM理论

理由：这篇论文主要探讨了神经崩溃现象（$\mathcal{NC}$）在大型语言模型（LLMs）中的表现及其与模型泛化能力的关系。论文通过实证分析因果语言模型（CLMs）的架构和训练扩展对$\mathcal{NC}$演进的影响，研究了$\mathcal{NC}$特性与泛化能力之间的关联，并探讨了$\mathcal{NC}$与泛化之间可能存在的独立于规模的联系。这些内容属于对LLMs理论层面的研究，特别是关于模型内部机制和性能的理论分析，因此归类为LLM理论。` `语言建模` `神经网络`

> Linguistic Collapse: Neural Collapse in (Large) Language Models

# 摘要

> 神经崩溃现象（$\mathcal{NC}$）揭示了分类任务中顶层表示趋向于其类别均值，这些均值等范数、等角度且与分类器对齐，这与模型的泛化和鲁棒性紧密相关。然而，这种现象仅在特定条件下显现：模型训练至零损失，采用平衡类别的无噪声标签，且类别数量不超过模型隐藏维度。近期研究尝试在缺少这些条件的情况下探索$\mathcal{NC}$，以期利用理想几何形状的优势。语言建模领域尤为引人注目，因为其“通过令牌预测训练”虽属分类任务，却无一符合上述条件：词汇不平衡且超出嵌入维度；不同令牌可能映射至相似的上下文嵌入；大型语言模型（LLMs）通常仅经历少数训练周期。本研究实证分析了因果语言模型（CLMs）架构与训练的扩展如何影响其向$\mathcal{NC}$的演进。我们发现，随着模型规模的增大，$\mathcal{NC}$特性与泛化能力之间存在关联。此外，有迹象表明$\mathcal{NC}$与泛化之间存在某种独立于规模的联系。我们的研究强调了$\mathcal{NC}$在语言建模这一新挑战领域的普遍性，并旨在激发对这一现象的深入研究，以增进对LLMs及神经网络的理解，并基于$\mathcal{NC}$相关特性优化现有架构。

> Neural collapse ($\mathcal{NC}$) is a phenomenon observed in classification tasks where top-layer representations collapse into their class means, which become equinorm, equiangular and aligned with the classifiers. These behaviors -- associated with generalization and robustness -- would manifest under specific conditions: models are trained towards zero loss, with noise-free labels belonging to balanced classes, which do not outnumber the model's hidden dimension. Recent studies have explored $\mathcal{NC}$ in the absence of one or more of these conditions to extend and capitalize on the associated benefits of ideal geometries. Language modeling presents a curious frontier, as \textit{training by token prediction} constitutes a classification task where none of the conditions exist: the vocabulary is imbalanced and exceeds the embedding dimension; different tokens might correspond to similar contextual embeddings; and large language models (LLMs) in particular are typically only trained for a few epochs. This paper empirically investigates the impact of scaling the architectures and training of causal language models (CLMs) on their progression towards $\mathcal{NC}$. We find that $\mathcal{NC}$ properties that develop with scaling are linked to generalization. Moreover, there is evidence of some relationship between $\mathcal{NC}$ and generalization independent of scale. Our work therefore underscores the generality of $\mathcal{NC}$ as it extends to the novel and more challenging setting of language modeling. Downstream, we seek to inspire further research on the phenomenon to deepen our understanding of LLMs -- and neural networks at large -- and improve existing architectures based on $\mathcal{NC}$-related properties.

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x1.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x2.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x3.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x4.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x5.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x6.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x7.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x8.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x9.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x10.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x11.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x12.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x13.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x14.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x15.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x16.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x17.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x18.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x19.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x20.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x21.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x22.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x23.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x24.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x25.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x26.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x27.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x28.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x29.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x30.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x31.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x32.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x33.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x34.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x35.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x36.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x37.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x38.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x39.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x40.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x41.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x42.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x43.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x44.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x45.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x46.png)

![语言模型危机：探究大型语言模型中的神经崩溃现象](../../../paper_images/2405.17767/x47.png)

[Arxiv](https://arxiv.org/abs/2405.17767)