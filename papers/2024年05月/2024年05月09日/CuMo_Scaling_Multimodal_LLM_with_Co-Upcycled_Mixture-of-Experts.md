# CuMo：借助协同升级的混合专家技术，扩展多模态大型语言模型的能力在这项研究中，我们提出了CuMo，一种新颖的框架，旨在通过引入协同升级的混合专家（Co-Upcycled Mixture-of-Experts）机制来扩展多模态大型语言模型（Multimodal LLM）的能力。CuMo的核心思想是通过有效地结合不同领域的专家知识，提升模型在处理多模态数据时的性能和灵活性。我们的实验结果表明，CuMo不仅能够显著提高模型的处理速度，还能在保持高准确率的同时，处理更加复杂和多样化的任务。这一创新性的方法为多模态AI技术的发展开辟了新的道路。

发布时间：2024年05月09日

`LLM应用

这篇论文介绍了一种名为CuMo的创新方法，旨在提升多模态大型语言模型的性能和可扩展性，同时保持较低的推理成本。CuMo通过引入混合专家（MoE）机制，特别是在视觉编码器和MLP连接器中使用Top-K稀疏门控混合专家块，来增强模型的能力。这种方法在多模态任务中表现出色，且仅依赖于开源数据集进行训练。由于论文主要关注的是LLM在多模态任务中的应用，特别是通过创新的方法提升模型性能，因此它属于LLM应用类别。` `人工智能` `计算机视觉`

> CuMo: Scaling Multimodal LLM with Co-Upcycled Mixture-of-Experts

# 摘要

> 近期，多模态大型语言模型的进步，主要集中在通过扩大文本-图像数据集和提升模型性能来应对多模态任务。然而，这些方法不仅计算成本高，还忽略了从视觉角度增强模型能力的重要性。借鉴混合专家（MoE）在大型语言模型中的成功应用，我们提出了CuMo，一种在训练时提升模型可扩展性，同时保持推理成本与小型模型相当的创新方法。CuMo通过将协同升级的Top-K稀疏门控混合专家块融入视觉编码器和MLP连接器，以最小的额外参数激活提升了多模态LLMs的性能。在视觉指令调整阶段，CuMo首先预训练MLP块，然后从这些预训练的MLP块初始化MoE块中的每个专家，并使用辅助损失确保专家的均衡加载。CuMo在多个VQA和视觉指令遵循基准测试中超越了现有的多模态LLMs，且仅依赖于开源数据集进行训练。CuMo的代码和模型权重已在GitHub上开源，地址为https://github.com/SHI-Labs/CuMo。

> Recent advancements in Multimodal Large Language Models (LLMs) have focused primarily on scaling by increasing text-image pair data and enhancing LLMs to improve performance on multimodal tasks. However, these scaling approaches are computationally expensive and overlook the significance of improving model capabilities from the vision side. Inspired by the successful applications of Mixture-of-Experts (MoE) in LLMs, which improves model scalability during training while keeping inference costs similar to those of smaller models, we propose CuMo. CuMo incorporates Co-upcycled Top-K sparsely-gated Mixture-of-experts blocks into both the vision encoder and the MLP connector, thereby enhancing the multimodal LLMs with minimal additional activated parameters during inference. CuMo first pre-trains the MLP blocks and then initializes each expert in the MoE block from the pre-trained MLP block during the visual instruction tuning stage. Auxiliary losses are used to ensure a balanced loading of experts. CuMo outperforms state-of-the-art multimodal LLMs across various VQA and visual-instruction-following benchmarks using models within each model size group, all while training exclusively on open-sourced datasets. The code and model weights for CuMo are open-sourced at https://github.com/SHI-Labs/CuMo.

[Arxiv](https://arxiv.org/abs/2405.05949)