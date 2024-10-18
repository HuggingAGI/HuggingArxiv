# 通过增强视觉能力，我们致力于提升多模态大型语言模型的性能。

发布时间：2024年10月17日

`LLM应用` `人工智能` `计算机视觉`

> Improving Multi-modal Large Language Model through Boosting Vision Capabilities

# 摘要

> 我们致力于提升视觉理解能力，以强化视觉-语言模型。为此，我们推出了 **Arcana**，一个多模态语言模型，并引入了两项创新技术。首先，我们设计了多模态 LoRA (MM-LoRA)，通过两个并行的 LoRA（一个针对视觉，一个针对语言），每个都有独立参数，从而实现更专业的模态学习，并更好地融合多模态信息。其次，我们开发了查询梯子适配器 (QLadder)，利用可学习的“梯子”结构，深入整合预训练视觉编码器的中间表示，使模型既能学习新视觉特征，又能保留原有视觉编码器的强大功能。这些技术共同提升了 Arcana 的视觉感知力，使其在多模态场景中能更精准、更贴合上下文地输出结果。实验和研究充分证明了 Arcana 的卓越性能和广泛适用性。相关代码和数据已公开，详见 [https://arcana-project-page.github.io](https://arcana-project-page.github.io)。

> We focus on improving the visual understanding capability for boosting the vision-language models. We propose \textbf{Arcana}, a multiModal language model, which introduces two crucial techniques. First, we present Multimodal LoRA (MM-LoRA), a module designed to enhance the decoder. Unlike traditional language-driven decoders, MM-LoRA consists of two parallel LoRAs -- one for vision and one for language -- each with its own parameters. This disentangled parameters design allows for more specialized learning in each modality and better integration of multimodal information. Second, we introduce the Query Ladder adapter (QLadder) to improve the visual encoder. QLadder employs a learnable ``\textit{ladder}'' structure to deeply aggregates the intermediate representations from the frozen pretrained visual encoder (e.g., CLIP image encoder). This enables the model to learn new and informative visual features, as well as remaining the powerful capabilities of the pretrained visual encoder. These techniques collectively enhance Arcana's visual perception power, enabling it to leverage improved visual information for more accurate and contextually relevant outputs across various multimodal scenarios. Extensive experiments and ablation studies demonstrate the effectiveness and generalization capability of our Arcana. The code and re-annotated data are available at \url{https://arcana-project-page.github.io}.

[Arxiv](https://arxiv.org/abs/2410.13733)