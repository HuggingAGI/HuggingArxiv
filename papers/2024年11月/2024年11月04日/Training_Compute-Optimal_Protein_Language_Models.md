# 训练计算最优的蛋白质语言模型

发布时间：2024年11月04日

`LLM理论` `蛋白质`

> Training Compute-Optimal Protein Language Models

# 摘要

> 我们探索最优地训练蛋白质语言模型，这是生物研究中一个备受关注的领域，在最佳实践方面的指导有限。大多数模型都是用大量的计算资源进行训练，直到性能提升达到平稳，主要侧重于增加模型规模，而不是优化平衡性能和计算预算的高效计算前沿。我们的研究基于一个由 9.39 亿个蛋白质序列组成的大规模数据集。我们在 50 亿到 2000 亿个独特的标记上训练了 300 多个模型，参数范围从 350 万到 1070 亿，以研究模型规模、训练标记数量和目标之间的关系。首先，我们观察到当重复使用常用的 Uniref 数据库时，因果语言模型（CLM）的收益递减效应和掩码语言模型（MLM）的过拟合效应。为了解决这个问题，我们在训练集中加入了宏基因组蛋白质序列，以增加多样性并避免平稳或过拟合效应。其次，我们获得了针对蛋白质序列数据特定特征的 Transformer 上 CLM 和 MLM 的缩放定律。第三，我们观察到从 CLM 到 MLM 的转移缩放现象，进一步通过基于估计的有效转移标记的缩放行为证明了转移的有效性。最后，为了验证我们的缩放定律，我们在下游任务上比较了 ESM-2 和 PROGEN2 的大规模版本，包括蛋白质生成以及与结构和功能相关任务的评估，所有这些都在较少或相等的预训练计算预算内。

> We explore optimally training protein language models, an area of significant interest in biological research where guidance on best practices is limited. Most models are trained with extensive compute resources until performance gains plateau, focusing primarily on increasing model sizes rather than optimizing the efficient compute frontier that balances performance and compute budgets. Our investigation is grounded in a massive dataset consisting of 939 million protein sequences. We trained over 300 models ranging from 3.5 million to 10.7 billion parameters on 5 to 200 billion unique tokens, to investigate the relations between model sizes, training token numbers, and objectives. First, we observed the effect of diminishing returns for the Causal Language Model (CLM) and that of overfitting for the Masked Language Model~(MLM) when repeating the commonly used Uniref database. To address this, we included metagenomic protein sequences in the training set to increase the diversity and avoid the plateau or overfitting effects. Second, we obtained the scaling laws of CLM and MLM on Transformer, tailored to the specific characteristics of protein sequence data. Third, we observe a transfer scaling phenomenon from CLM to MLM, further demonstrating the effectiveness of transfer through scaling behaviors based on estimated Effectively Transferred Tokens. Finally, to validate our scaling laws, we compare the large-scale versions of ESM-2 and PROGEN2 on downstream tasks, encompassing evaluations of protein generation as well as structure- and function-related tasks, all within less or equivalent pre-training compute budgets.

[Arxiv](https://arxiv.org/abs/2411.02142)