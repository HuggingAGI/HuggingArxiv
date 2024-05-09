# GP-MoLFormer：分子生成的奠基之作在这篇文章中，我们将介绍GP-MoLFormer，这是一种开创性的基础模型，专为分子生成而设计。它通过深度学习和先进的算法，为药物发现和材料科学领域带来了革命性的变革。GP-MoLFormer不仅能够高效地生成新颖的分子结构，还能确保这些结构在化学上可行且具有潜在的应用价值。随着我们对这一模型的深入探讨，我们将揭示它是如何成为分子设计领域的一块重要基石，以及它如何推动科学探索的边界。

发布时间：2024年04月04日

`LLM应用

这篇论文介绍了一个基于Transformer的大型语言模型GP-MoLFormer，专门用于生成化学分子字符串（SMILES）。它展示了模型在生成新颖、有效且唯一的分子结构方面的能力，并探讨了训练数据质量对模型性能的影响。此外，论文还评估了模型在不同化学任务中的应用，包括从头设计分子、骨架约束装饰和属性引导优化。这些应用展示了LLM在特定领域（如化学）的实际应用价值，因此属于LLM应用分类。` `分子设计`

> GP-MoLFormer: A Foundation Model For Molecular Generation

# 摘要

> 基于Transformer的模型在分子字符串的大型数据集上训练，已成为揭示结构与性质关系的利器。我们在此基础上，推出了GP-MoLFormer，一个能生成超过11亿化学SMILES的自回归分子生成器。它采用4680万参数的Transformer解码器，结合线性注意力和旋转位置编码。GP-MoLFormer在生成新颖、有效且唯一的SMILES方面表现出色，即使在分子生成量达百亿级时亦然。然而，我们也发现它对训练数据的记忆效应，这在化学语言模型中尚属首次。我们分析了训练数据质量对记忆和创新的影响，并指出复制偏差虽增强记忆，却牺牲了创新。我们通过三个任务评估GP-MoLFormer：从头设计、骨架约束装饰和属性引导优化，其中最后一个任务采用了我们提出的pair-tuning微调方法。结果表明，GP-MoLFormer在各项任务中均表现出色，展现了其广泛的适用性。

> Transformer-based models trained on large and general purpose datasets consisting of molecular strings have recently emerged as a powerful tool for successfully modeling various structure-property relations. Inspired by this success, we extend the paradigm of training chemical language transformers on large-scale chemical datasets to generative tasks in this work. Specifically, we propose GP-MoLFormer, an autoregressive molecular string generator that is trained on more than 1.1B chemical SMILES. GP-MoLFormer uses a 46.8M parameter transformer decoder model with linear attention and rotary positional encodings as the base architecture. We explore the utility of GP-MoLFormer in generating novel, valid, and unique SMILES. Impressively, we find GP-MoLFormer is able to generate a significant fraction of novel, valid, and unique SMILES even when the number of generated molecules is in the 10 billion range and the reference set is over a billion. We also find strong memorization of training data in GP-MoLFormer generations, which has so far remained unexplored for chemical language models. Our analyses reveal that training data memorization and novelty in generations are impacted by the quality of the training data; duplication bias in training data can enhance memorization at the cost of lowering novelty. We evaluate GP-MoLFormer's utility and compare it with that of existing baselines on three different tasks: de novo generation, scaffold-constrained molecular decoration, and unconstrained property-guided optimization. While the first two are handled with no additional training, we propose a parameter-efficient fine-tuning method for the last task, which uses property-ordered molecular pairs as input. We call this new approach pair-tuning. Our results show GP-MoLFormer performs better or comparable with baselines across all three tasks, demonstrating its general utility.

[Arxiv](https://arxiv.org/abs/2405.04912)