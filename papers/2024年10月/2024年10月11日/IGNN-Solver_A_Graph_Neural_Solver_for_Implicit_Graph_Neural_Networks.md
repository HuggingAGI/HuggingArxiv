# IGNN-Solver：专为隐式图神经网络设计的图神经求解器

发布时间：2024年10月11日

`其他` `图神经网络` `大规模图计算`

> IGNN-Solver: A Graph Neural Solver for Implicit Graph Neural Networks

# 摘要

> 摘要：隐式图神经网络 (IGNNs) 凭借单层结构展现出强大的表达能力，近期在捕捉图中的长程依赖和缓解过平滑问题上表现卓越。然而，其依赖的定点迭代计算成本高昂，限制了在大规模图上的应用。为此，我们推出了 IGNN-Solver，一种利用广义 Anderson 加速方法的新型图神经求解器，通过小型 GNN 参数化，将迭代更新视为依赖于图的时间过程。实验结果显示，IGNN-Solver 在保持准确性的同时，实现了 $1.5\times$ 到 $8\times$ 的推理加速。随着图规模的扩大，这一优势愈加明显，为其在实际应用中的大规模部署铺平了道路。

> 
Abstract:Implicit graph neural networks (IGNNs), which exhibit strong expressive power with a single layer, have recently demonstrated remarkable performance in capturing long-range dependencies (LRD) in underlying graphs while effectively mitigating the over-smoothing problem. However, IGNNs rely on computationally expensive fixed-point iterations, which lead to significant speed and scalability limitations, hindering their application to large-scale graphs. To achieve fast fixed-point solving for IGNNs, we propose a novel graph neural solver, IGNN-Solver, which leverages the generalized Anderson Acceleration method, parameterized by a small GNN, and learns iterative updates as a graph-dependent temporal process. Extensive experiments demonstrate that the IGNN-Solver significantly accelerates inference, achieving a $1.5\times$ to $8\times$ speedup without sacrificing accuracy. Moreover, this advantage becomes increasingly pronounced as the graph scale grows, facilitating its large-scale deployment in real-world applications.
    

[Arxiv](https://arxiv.org/pdf/2410.08524)