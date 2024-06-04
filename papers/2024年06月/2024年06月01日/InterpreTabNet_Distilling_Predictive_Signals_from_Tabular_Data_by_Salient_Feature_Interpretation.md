# InterpreTabNet：借助显著特征解释，从表格数据中提炼预测信号

发布时间：2024年06月01日

`Agent

理由：这篇论文主要介绍了一种名为InterpreTabNet的新型神经网络，它通过改进注意力机制来增强表格数据预测的可解释性。虽然文中提到了使用大型语言模型GPT-4来辅助解释特征间的相互作用，但这并不是论文的核心内容。论文的主要贡献在于开发了一种新的神经网络架构，该架构通过特定的技术（如Gumbel-Softmax分布和KL散度正则化）来优化注意力机制，从而提高模型的解释性和性能。因此，这篇论文更符合Agent分类，因为它涉及的是一个具体的、用于处理特定任务（即表格数据预测）的智能代理或系统的设计和实现。` `数据分析`

> InterpreTabNet: Distilling Predictive Signals from Tabular Data by Salient Feature Interpretation

# 摘要

> 表格数据在各行各业中广泛存在。TabNet等针对表格数据的神经网络，通过注意力机制提升预测的可解释性。但这些网络产生的注意力掩码往往过于密集，难以清晰解读预测信号。为此，我们开发了InterpreTabNet，这一TabNet的变种将注意力机制视为Gumbel-Softmax分布中的潜在变量，通过KL散度正则化促进注意力掩码的稀疏性，从而增强模型的效能和可解释性，明确指出预测中的关键特征。为了进一步阐释特征间的相互作用，我们借助大型语言模型GPT-4，运用提示工程将特征掩码转化为自然语言描述。实验证明，InterpreTabNet不仅在解释性上超越了以往方法，其准确度也极具竞争力。

> Tabular data are omnipresent in various sectors of industries. Neural networks for tabular data such as TabNet have been proposed to make predictions while leveraging the attention mechanism for interpretability. However, the inferred attention masks are often dense, making it challenging to come up with rationales about the predictive signal. To remedy this, we propose InterpreTabNet, a variant of the TabNet model that models the attention mechanism as a latent variable sampled from a Gumbel-Softmax distribution. This enables us to regularize the model to learn distinct concepts in the attention masks via a KL Divergence regularizer. It prevents overlapping feature selection by promoting sparsity which maximizes the model's efficacy and improves interpretability to determine the important features when predicting the outcome. To assist in the interpretation of feature interdependencies from our model, we employ a large language model (GPT-4) and use prompt engineering to map from the learned feature mask onto natural language text describing the learned signal. Through comprehensive experiments on real-world datasets, we demonstrate that InterpreTabNet outperforms previous methods for interpreting tabular data while attaining competitive accuracy.

[Arxiv](https://arxiv.org/abs/2406.00426)