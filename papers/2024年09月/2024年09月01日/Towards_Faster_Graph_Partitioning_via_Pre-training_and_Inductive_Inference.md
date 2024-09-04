# 借助预训练与归纳推理，加速图划分进程

发布时间：2024年09月01日

`LLM应用` `计算机科学` `图处理`

> Towards Faster Graph Partitioning via Pre-training and Inductive Inference

# 摘要

> 图划分 (GP) 问题旨在将图节点集划分为密集连接的块。受 IEEE HPEC 图挑战赛和预训练技术（如大型语言模型）的启发，我们提出了 PR-GPT，一种基于预训练和细化范式的新方法。首先，我们在小型合成图上预训练深度图学习 (DGL) 模型。利用 DGL 的归纳推理，预训练模型可直接应用于大型图，生成可行的 GP 结果。此外，我们利用这些结果作为高效 GP 方法（如 InfoMap）的初始化，进一步提升划分质量。PR-GPT 的在线泛化和细化不仅提高了质量转移能力，还确保了高推理效率，无需重新训练。通过减少细化方法处理的图规模，PR-GPT 还支持流式 GP。实验表明，PR-GPT 在大规模图上实现更快 GP，且质量损失极小。代码将在 https://github.com/KuroginQin/PRGPT 公开。

> Graph partitioning (GP) is a classic problem that divides the node set of a graph into densely-connected blocks. Following the IEEE HPEC Graph Challenge and recent advances in pre-training techniques (e.g., large-language models), we propose PR-GPT (Pre-trained & Refined Graph ParTitioning) based on a novel pre-training & refinement paradigm. We first conduct the offline pre-training of a deep graph learning (DGL) model on small synthetic graphs with various topology properties. By using the inductive inference of DGL, one can directly generalize the pre-trained model (with frozen model parameters) to large graphs and derive feasible GP results. We also use the derived partition as a good initialization of an efficient GP method (e.g., InfoMap) to further refine the quality of partitioning. In this setting, the online generalization and refinement of PR-GPT can not only benefit from the transfer ability regarding quality but also ensure high inference efficiency without re-training. Based on a mechanism of reducing the scale of a graph to be processed by the refinement method, PR-GPT also has the potential to support streaming GP. Experiments on the Graph Challenge benchmark demonstrate that PR-GPT can ensure faster GP on large-scale graphs without significant quality degradation, compared with running a refinement method from scratch. We will make our code public at https://github.com/KuroginQin/PRGPT.

[Arxiv](https://arxiv.org/abs/2409.00670)