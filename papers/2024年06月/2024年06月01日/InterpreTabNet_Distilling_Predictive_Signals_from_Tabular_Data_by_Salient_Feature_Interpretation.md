# InterpreTabNet：借助显著特征解释，精炼表格数据中的预测信号

发布时间：2024年06月01日

`Agent

理由：这篇论文介绍了一种名为InterpreTabNet的神经网络变种，它通过改进注意力机制来提高表格数据预测的可解释性。论文中提到使用GPT-4大型语言模型来将特征掩码转化为自然语言描述，这表明该工作涉及到了语言模型的应用，但主要关注点是通过改进神经网络模型来增强其解释性，而不是直接研究语言模型本身或其理论。因此，它更适合归类为Agent，即关注于开发和改进特定类型的智能代理（在此案例中为神经网络模型）以执行特定任务（解释表格数据预测）。` `数据分析` `机器学习`

> InterpreTabNet: Distilling Predictive Signals from Tabular Data by Salient Feature Interpretation

# 摘要

> 表格数据遍布各行各业，TabNet等神经网络利用注意力机制提升预测的可解释性。但注意力掩码往往过于密集，难以清晰解读预测信号。为此，我们开发了InterpreTabNet，这一TabNet的变种将注意力机制视为Gumbel-Softmax分布中的潜在变量，通过KL散度正则化促进注意力掩码的稀疏性，避免特征重叠，增强模型效能与可解释性，明确识别预测中的关键特征。我们还借助GPT-4大型语言模型，运用提示工程将特征掩码转化为自然语言描述，揭示特征间的相互作用。实验证明，InterpreTabNet在解释表格数据方面超越了以往方法，同时保持了高准确度。

> Tabular data are omnipresent in various sectors of industries. Neural networks for tabular data such as TabNet have been proposed to make predictions while leveraging the attention mechanism for interpretability. However, the inferred attention masks are often dense, making it challenging to come up with rationales about the predictive signal. To remedy this, we propose InterpreTabNet, a variant of the TabNet model that models the attention mechanism as a latent variable sampled from a Gumbel-Softmax distribution. This enables us to regularize the model to learn distinct concepts in the attention masks via a KL Divergence regularizer. It prevents overlapping feature selection by promoting sparsity which maximizes the model's efficacy and improves interpretability to determine the important features when predicting the outcome. To assist in the interpretation of feature interdependencies from our model, we employ a large language model (GPT-4) and use prompt engineering to map from the learned feature mask onto natural language text describing the learned signal. Through comprehensive experiments on real-world datasets, we demonstrate that InterpreTabNet outperforms previous methods for interpreting tabular data while attaining competitive accuracy.

[Arxiv](https://arxiv.org/abs/2406.00426)