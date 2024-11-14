# NVCiM-PT：一个由 NVCiM 辅助的用于边缘大型语言模型的提示调整框架

发布时间：2024年11月12日

`LLM应用` `边缘计算` `人工智能`

> NVCiM-PT: An NVCiM-assisted Prompt Tuning Framework for Edge LLMs

# 摘要

> 部署在边缘设备上的大型语言模型（LLMs），即边缘 LLMs，需要在有限的资源约束下，根据用户生成的数据不断微调其模型参数。然而，由于大多数现有学习方法依赖于高资源和低学习能力，因此不适用于边缘 LLMs。提示调整（PT）最近作为一种有效的边缘 LLMs 微调方法出现，它仅修改 LLM 参数的一小部分，但它受到用户领域转移的影响，导致重复训练和资源效率损失。解决领域转移问题的传统技术通常涉及复杂的神经网络和复杂的训练，这与边缘 LLMs 的 PT 不兼容。因此，一个开放的研究问题是如何在有限资源的情况下解决边缘 LLMs 的领域转移问题。在本文中，我们为边缘 LLMs 提出了一个提示调整框架，利用非易失性内存计算（NVCiM）架构提供的优势。我们引入了一个新颖的 NVCiM 辅助的 PT 框架，将核心操作缩小到矩阵乘法，然后可以通过在 NVCiM 上进行原位计算来加速。据我们所知，这是第一项使用 NVCiM 来提高边缘 LLM PT 性能的工作。

> Large Language Models (LLMs) deployed on edge devices, known as edge LLMs, need to continuously fine-tune their model parameters from user-generated data under limited resource constraints. However, most existing learning methods are not applicable for edge LLMs because of their reliance on high resources and low learning capacity. Prompt tuning (PT) has recently emerged as an effective fine-tuning method for edge LLMs by only modifying a small portion of LLM parameters, but it suffers from user domain shifts, resulting in repetitive training and losing resource efficiency. Conventional techniques to address domain shift issues often involve complex neural networks and sophisticated training, which are incompatible for PT for edge LLMs. Therefore, an open research question is how to address domain shift issues for edge LLMs with limited resources. In this paper, we propose a prompt tuning framework for edge LLMs, exploiting the benefits offered by non-volatile computing-in-memory (NVCiM) architectures. We introduce a novel NVCiM-assisted PT framework, where we narrow down the core operations to matrix-matrix multiplication, which can then be accelerated by performing in-situ computation on NVCiM. To the best of our knowledge, this is the first work employing NVCiM to improve the edge LLM PT performance.

[Arxiv](https://arxiv.org/abs/2411.08244)