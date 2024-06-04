# InterpreTabNet：借助显著特征解释，精炼表格数据中的预测信号

发布时间：2024年06月01日

`Agent

理由：这篇论文介绍了一种改进的神经网络模型（InterpreTabNet），该模型通过引入Gumbel-Softmax分布和KL散度正则化来增强注意力掩码的稀疏性，从而提高模型的可解释性和效能。此外，论文还提到了使用GPT-4大型语言模型通过提示工程将特征掩码转化为自然语言描述，以揭示特征间的相互作用。这些内容主要关注于开发和应用特定的技术来改进模型性能和可解释性，而不是深入探讨LLM的理论或应用，也不是关于Agent的一般性研究。因此，将其归类为Agent是因为它涉及到了特定模型的改进和应用，这些改进和应用可以被视为一种智能代理（Agent）的行为，即通过技术手段优化和解释数据处理过程。` `数据分析` `机器学习`

> InterpreTabNet: Distilling Predictive Signals from Tabular Data by Salient Feature Interpretation

# 摘要

> 表格数据遍布各行各业，TabNet等神经网络利用注意力机制提升预测的可解释性。但注意力掩码往往过于密集，难以洞察预测信号的本质。为此，我们开发了InterpreTabNet，这一TabNet的变种将注意力机制视为Gumbel-Softmax分布中的潜在变量，通过KL散度正则化促进注意力掩码的稀疏性，避免特征重叠，增强模型效能与可解释性，精准识别关键特征。我们还借助GPT-4大型语言模型，通过提示工程将特征掩码转化为自然语言描述，揭示特征间的相互作用。实验证明，InterpreTabNet在解释表格数据方面超越了以往方法，同时保持了高准确度。

> Tabular data are omnipresent in various sectors of industries. Neural networks for tabular data such as TabNet have been proposed to make predictions while leveraging the attention mechanism for interpretability. However, the inferred attention masks are often dense, making it challenging to come up with rationales about the predictive signal. To remedy this, we propose InterpreTabNet, a variant of the TabNet model that models the attention mechanism as a latent variable sampled from a Gumbel-Softmax distribution. This enables us to regularize the model to learn distinct concepts in the attention masks via a KL Divergence regularizer. It prevents overlapping feature selection by promoting sparsity which maximizes the model's efficacy and improves interpretability to determine the important features when predicting the outcome. To assist in the interpretation of feature interdependencies from our model, we employ a large language model (GPT-4) and use prompt engineering to map from the learned feature mask onto natural language text describing the learned signal. Through comprehensive experiments on real-world datasets, we demonstrate that InterpreTabNet outperforms previous methods for interpreting tabular data while attaining competitive accuracy.

[Arxiv](https://arxiv.org/abs/2406.00426)