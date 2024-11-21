# 在线广告检索的缩放定律

发布时间：2024年11月20日

`LLM应用` `在线检索`

> Scaling Laws for Online Advertisement Retrieval

# 摘要

> 缩放定律乃神经网络模型的显著特性，有力推动了大型语言模型的发展。其在指导模型设计与资源分配方面颇具潜力。近来研究愈发表明，缩放定律不仅适用于自然语言处理任务或 Transformer 架构，在推荐等领域亦有应用。然而，有关在线广告检索系统中缩放定律的研究文献尚缺。这或许是因为：其一，对于大规模工业应用而言，确定资源成本与在线收入的缩放定律，在时间和训练资源上往往耗费甚巨；其二，不同系统的各异设置阻碍了缩放定律在各类场景中的应用。为应对这些问题，我们提出一种轻量范式，以较低实验成本确定某一在线广告检索场景中在线收入与机器成本的缩放定律。具体而言，我们着眼于单个因素（FLOPs），并提出名为 R/R*的离线指标，其与检索模型的在线收入高度线性相关。我们通过模拟算法离线估算机器成本。如此，多数在线实验可转为低成本的离线实验。我们开展了全面实验，以验证所提指标 R/R*的有效性，并明确快手在线广告检索系统中的缩放定律。凭借缩放定律，我们在快手广告系统中展示了受 ROI 约束的模型设计以及多场景资源分配的实际应用。据我们所知，这是首项针对现实世界系统在线广告检索缩放定律的研究工作，展现出缩放定律在广告系统优化方面的巨大潜能。

> The scaling law is a notable property of neural network models and has significantly propelled the development of large language models. Scaling laws hold great promise in guiding model design and resource allocation. Recent research increasingly shows that scaling laws are not limited to NLP tasks or Transformer architectures; they also apply to domains such as recommendation. However, there is still a lack of literature on scaling law research in online advertisement retrieval systems. This may be because 1) identifying the scaling law for resource cost and online revenue is often expensive in both time and training resources for large-scale industrial applications, and 2) varying settings for different systems prevent the scaling law from being applied across various scenarios. To address these issues, we propose a lightweight paradigm to identify the scaling law of online revenue and machine cost for a certain online advertisement retrieval scenario with a low experimental cost. Specifically, we focus on a sole factor (FLOPs) and propose an offline metric named R/R* that exhibits a high linear correlation with online revenue for retrieval models. We estimate the machine cost offline via a simulation algorithm. Thus, we can transform most online experiments into low-cost offline experiments. We conduct comprehensive experiments to verify the effectiveness of our proposed metric R/R* and to identify the scaling law in the online advertisement retrieval system of Kuaishou. With the scaling law, we demonstrate practical applications for ROI-constrained model designing and multi-scenario resource allocation in Kuaishou advertising system. To the best of our knowledge, this is the first work to study the scaling laws for online advertisement retrieval of real-world systems, showing great potential for scaling law in advertising system optimization.

[Arxiv](https://arxiv.org/abs/2411.13322)