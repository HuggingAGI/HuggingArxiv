# 异质性中蕴含着对不变性和因果性的内在倾向，本文探讨这一隐含偏置的实质及其影响。

发布时间：2024年03月03日

`LLM理论`

> The Implicit Bias of Heterogeneity towards Invariance and Causality

# 摘要

> 实践经验揭示，利用互联网海量数据集并通过改进的回归损失训练的 LLM 能够在某种程度上揭示出因果联系，颠覆了“相关性不等于因果性”的传统观念，并打破了传统因果推理中强调先验因果知识精心融入方法设计的框架。令人惊奇的是，深层次的因果性竟然能从追求关联性的回归任务中显现出来。本文主张，源自关联性训练的因果性突现，主要源于数据源的异质性、训练算法的随机性和模型的过参数化三者间的耦合作用。为了形象阐述这一观点，我们借助一个简洁却深刻的模型，利用回归损失学习近似因果性质的不变性。具体场景是处理多环境下的低秩矩阵感知问题，其中各环境下的未知 r-秩 d*d 真实矩阵虽有所差异，但都包含一个较低秩且保持不变的因果部分。常规的汇集梯度下降法往往只能得到反映一般关联性的有偏解。然而，我们证明，在一定条件下，运用大规模随机梯度下降法，每批次采样自特定环境的线性测量样本，可以有效促使解决方案趋近于不变的因果解。这一过程与环境的较强异质性、优化算法中较大的步长和噪声以及模型的过参数化紧密相关。综上所述，我们揭示了一种新的隐含偏差，它源自数据异质性和现代算法之间的共生关系，据目前所知，这是文献上的首例发现。

> It is observed empirically that the large language models (LLM), trained with a variant of regression loss using numerous corpus from the Internet, can unveil causal associations to some extent. This is contrary to the traditional wisdom that ``association is not causation'' and the paradigm of traditional causal inference in which prior causal knowledge should be carefully incorporated into the design of methods. It is a mystery why causality, in a higher layer of understanding, can emerge from the regression task that pursues associations. In this paper, we claim the emergence of causality from association-oriented training can be attributed to the coupling effects from the heterogeneity of the source data, stochasticity of training algorithms, and over-parameterization of the learning models. We illustrate such an intuition using a simple but insightful model that learns invariance, a quasi-causality, using regression loss. To be specific, we consider multi-environment low-rank matrix sensing problems where the unknown r-rank ground-truth d*d matrices diverge across the environments but contain a lower-rank invariant, causal part. In this case, running pooled gradient descent will result in biased solutions that only learn associations in general. We show that running large-batch Stochastic Gradient Descent, whose each batch being linear measurement samples randomly selected from a certain environment, can successfully drive the solution towards the invariant, causal solution under certain conditions. This step is related to the relatively strong heterogeneity of the environments, the large step size and noises in the optimization algorithm, and the over-parameterization of the model. In summary, we unveil another implicit bias that is a result of the symbiosis between the heterogeneity of data and modern algorithms, which is, to the best of our knowledge, first in the literature.

[Arxiv](https://arxiv.org/abs/2403.01420)