# TabM：通过参数高效集成推进表格深度学习

发布时间：2024年11月11日

`其他` `表格数据`

> TabM: Advancing Tabular Deep Learning with Parameter-Efficient Ensembling

# 摘要

> 用于表格数据监督学习的深度学习架构范围从简单的多层感知机（MLP）到复杂的 Transformer 和检索增强方法。本研究强调了一个重大但迄今被忽视的机会，可大幅改进表格 MLP：即参数高效集成——一种将模型集成实现为一个产生多个预测的模型的范例。我们首先开发了 TabM——一个基于 MLP 和我们对 BatchEnsemble（现有技术）的变体的简单模型。然后，我们在公共基准上对表格深度学习架构进行了大规模评估，包括任务性能和效率，这为表格深度学习的格局带来了新的视角。通常，我们表明，包括 TabM 在内的 MLP 与基于注意力和检索的架构相比，形成了一系列更强大和更实用的模型。特别是，我们发现 TabM 在表格深度学习模型中表现最佳。最后，我们对 TabM 的集成性质进行了实证分析。例如，我们观察到 TabM 的多个预测单独来看较弱，但整体上很强。总的来说，我们的工作为表格深度学习带来了一种有影响力的技术，分析了其行为，并通过 TabM 推进了性能效率的权衡——这是研究人员和从业者的一个简单而强大的基线。

> Deep learning architectures for supervised learning on tabular data range from simple multilayer perceptrons (MLP) to sophisticated Transformers and retrieval-augmented methods. This study highlights a major, yet so far overlooked opportunity for substantially improving tabular MLPs: namely, parameter-efficient ensembling -- a paradigm for implementing an ensemble of models as one model producing multiple predictions. We start by developing TabM -- a simple model based on MLP and our variations of BatchEnsemble (an existing technique). Then, we perform a large-scale evaluation of tabular DL architectures on public benchmarks in terms of both task performance and efficiency, which renders the landscape of tabular DL in a new light. Generally, we show that MLPs, including TabM, form a line of stronger and more practical models compared to attention- and retrieval-based architectures. In particular, we find that TabM demonstrates the best performance among tabular DL models. Lastly, we conduct an empirical analysis on the ensemble-like nature of TabM. For example, we observe that the multiple predictions of TabM are weak individually, but powerful collectively. Overall, our work brings an impactful technique to tabular DL, analyses its behaviour, and advances the performance-efficiency trade-off with TabM -- a simple and powerful baseline for researchers and practitioners.

[Arxiv](https://arxiv.org/abs/2410.24210)