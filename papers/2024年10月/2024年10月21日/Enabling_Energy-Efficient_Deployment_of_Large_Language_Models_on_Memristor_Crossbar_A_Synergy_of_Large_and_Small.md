# 忆阻器交叉阵列上的大型语言模型节能部署：大小协同之道

发布时间：2024年10月21日

`LLM理论` `计算机视觉` `半导体`

> Enabling Energy-Efficient Deployment of Large Language Models on Memristor Crossbar: A Synergy of Large and Small

# 摘要

> 大型语言模型 (LLM) 因其广泛的应用潜力备受瞩目，但其规模的扩大也带来了训练和部署的高计算需求。忆阻器交叉阵列因其小尺寸和高能效在计算机视觉 (CV) 模型中表现出色，且其高密度特性使其成为管理 LLM 极端模型大小的理想选择。然而，在忆阻器交叉阵列上部署 LLM 面临三大挑战：模型规模迅速增长、多头注意力块的非权重静态乘法、以及复杂非线性操作的执行。为此，我们设计了一种新型忆阻器交叉阵列架构，可在单芯片或封装上部署最先进的 LLM，显著提升效率。测试结果显示，与传统忆阻器交叉阵列相比，我们的架构在面积开销和能耗方面分别提升了 39 倍和 18 倍；与现代 TPU/GPU 系统相比，面积延迟积减少了 68 倍，能耗降低了 69%。

> Large language models (LLMs) have garnered substantial attention due to their promising applications in diverse domains. Nevertheless, the increasing size of LLMs comes with a significant surge in the computational requirements for training and deployment. Memristor crossbars have emerged as a promising solution, which demonstrated a small footprint and remarkably high energy efficiency in computer vision (CV) models. Memristors possess higher density compared to conventional memory technologies, making them highly suitable for effectively managing the extreme model size associated with LLMs. However, deploying LLMs on memristor crossbars faces three major challenges. Firstly, the size of LLMs increases rapidly, already surpassing the capabilities of state-of-the-art memristor chips. Secondly, LLMs often incorporate multi-head attention blocks, which involve non-weight stationary multiplications that traditional memristor crossbars cannot support. Third, while memristor crossbars excel at performing linear operations, they are not capable of executing complex nonlinear operations in LLM such as softmax and layer normalization. To address these challenges, we present a novel architecture for the memristor crossbar that enables the deployment of state-of-the-art LLM on a single chip or package, eliminating the energy and time inefficiencies associated with off-chip communication. Our testing on BERT_Large showed negligible accuracy loss. Compared to traditional memristor crossbars, our architecture achieves enhancements of up to 39X in area overhead and 18X in energy consumption. Compared to modern TPU/GPU systems, our architecture demonstrates at least a 68X reduction in the area-delay product and a significant 69% energy consumption reduction.

[Arxiv](https://arxiv.org/abs/2410.15977)