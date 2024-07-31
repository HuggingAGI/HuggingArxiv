# 警惕超参数优化导致的过拟合问题！

发布时间：2024年07月30日

`LLM理论` `机器学习`

> Be aware of overfitting by hyperparameter optimization!

# 摘要

> 超参数优化在机器学习领域应用广泛，但过度优化大量参数可能导致模型过拟合。最新研究中，研究者从多个来源收集了七个溶解度数据集，采用尖端的图方法，并对比了不同数据清洗和超参数优化下的模型性能。我们的研究发现，超参数优化并非总能提升模型质量，可能因统计方法一致性导致的过拟合。预设超参数能大幅减少计算负担，约降低10,000倍。此外，我们引入基于SMILES的Transformer CNN方法，该方法在28次对比中26次超越传统图方法，且耗时极少。最后，我们强调了使用统一统计标准进行结果对比的重要性。

> Hyperparameter optimization is very frequently employed in machine learning. However, an optimization of a large space of parameters could result in overfitting of models. In recent studies on solubility prediction the authors collected seven thermodynamic and kinetic solubility datasets from different data sources. They used state-of-the-art graph-based methods and compared models developed for each dataset using different data cleaning protocols and hyperparameter optimization. In our study we showed that hyperparameter optimization did not always result in better models, possibly due to overfitting when using the same statistical measures. Similar results could be calculated using pre-set hyperparameters, reducing the computational effort by around 10,000 times. We also extended the previous analysis by adding a representation learning method based on Natural Language Processing of smiles called Transformer CNN. We show that across all analyzed sets using exactly the same protocol, Transformer CNN provided better results than graph-based methods for 26 out of 28 pairwise comparisons by using only a tiny fraction of time as compared to other methods. Last but not least we stressed the importance of comparing calculation results using exactly the same statistical measures.

[Arxiv](https://arxiv.org/abs/2407.20786)