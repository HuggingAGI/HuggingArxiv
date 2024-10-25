# 元流匹配：在瓦瑟斯坦流形上集成向量场

发布时间：2024年08月26日

`其他`

> Meta Flow Matching: Integrating Vector Fields on the Wasserstein Manifold

# 摘要

> 摘要：许多生物和物理过程可以被建模为随时间不断演变的相互作用实体的系统，例如通信细胞或物理粒子的动态。学习此类系统的动态对于预测新样本和未见过的环境中群体的时间演变至关重要。基于流的模型允许在群体水平上学习这些动态 - 它们对样本的整个分布的演变进行建模。然而，当前的基于流的模型仅限于单个初始群体和一组描述不同动态的预定义条件。我们认为，自然科学中的多个过程必须表示为概率密度的 Wasserstein 流形上的向量场。也就是说，由于样本之间的相互作用，群体在任何时刻的变化都取决于群体本身。特别是，这对于个性化医疗至关重要，其中疾病的发展及其各自的治疗反应取决于每个患者特定的细胞微环境。我们提出了元流匹配（MFM），这是一种通过在初始群体上摊销流模型来沿着 Wasserstein 流形上的这些向量场进行积分的实用方法。即，我们使用图神经网络（GNN）嵌入样本群体，并使用这些嵌入来训练流匹配模型。这使 MFM 具有与先前提出的方法不同的在初始分布上泛化的能力。我们在大规模多患者单细胞药物筛选数据集上展示了 MFM 改善个体治疗反应预测的能力。

> 
Abstract:Numerous biological and physical processes can be modeled as systems of interacting entities evolving continuously over time, e.g. the dynamics of communicating cells or physical particles. Learning the dynamics of such systems is essential for predicting the temporal evolution of populations across novel samples and unseen environments. Flow-based models allow for learning these dynamics at the population level - they model the evolution of the entire distribution of samples. However, current flow-based models are limited to a single initial population and a set of predefined conditions which describe different dynamics. We argue that multiple processes in natural sciences have to be represented as vector fields on the Wasserstein manifold of probability densities. That is, the change of the population at any moment in time depends on the population itself due to the interactions between samples. In particular, this is crucial for personalized medicine where the development of diseases and their respective treatment response depends on the microenvironment of cells specific to each patient. We propose Meta Flow Matching (MFM), a practical approach to integrating along these vector fields on the Wasserstein manifold by amortizing the flow model over the initial populations. Namely, we embed the population of samples using a Graph Neural Network (GNN) and use these embeddings to train a Flow Matching model. This gives MFM the ability to generalize over the initial distributions unlike previously proposed methods. We demonstrate the ability of MFM to improve prediction of individual treatment responses on a large scale multi-patient single-cell drug screen dataset.
    

[Arxiv](https://arxiv.org/pdf/2408.14608)