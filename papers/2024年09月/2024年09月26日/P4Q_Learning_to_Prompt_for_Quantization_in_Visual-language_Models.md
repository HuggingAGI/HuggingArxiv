# P4Q：视觉-语言模型中通过提示学习实现量化

发布时间：2024年09月26日

`LLM应用` `计算机视觉` `人工智能`

> P4Q: Learning to Prompt for Quantization in Visual-language Models

# 摘要

> 大规模预训练的视觉-语言模型 (VLMs) 在视觉和多模态任务中表现出色，但其高昂的训练样本和计算资源需求使得在下游应用中的部署充满挑战。微调和量化是降低成本的关键，但现有方法各有弊端：量化感知训练 (QAT) 成本高昂，低比特后训练量化 (PTQ) 性能下降明显。为此，我们提出了“量化提示” (P4Q) 方法，通过轻量级架构和对比损失监督提升 PTQ 模型的识别性能，并利用可学习提示和低比特适配器重新对齐图像与文本特征，有效减少低比特量化带来的性能损失。此外，我们还引入了基于余弦相似度的蒸馏损失，进一步提升量化模型的性能。实验结果显示，P4Q 不仅超越了现有方法，甚至在某些指标上与全精度模型不相上下。例如，8 比特 P4Q 在 ImageNet 数据集上实现了 66.94% 的 Top-1 准确率，比全精度模型高出 2.24%，且参数几乎无增加。

> Large-scale pre-trained Vision-Language Models (VLMs) have gained prominence in various visual and multimodal tasks, yet the deployment of VLMs on downstream application platforms remains challenging due to their prohibitive requirements of training samples and computing resources. Fine-tuning and quantization of VLMs can substantially reduce the sample and computation costs, which are in urgent need. There are two prevailing paradigms in quantization, Quantization-Aware Training (QAT) can effectively quantize large-scale VLMs but incur a huge training cost, while low-bit Post-Training Quantization (PTQ) suffers from a notable performance drop. We propose a method that balances fine-tuning and quantization named ``Prompt for Quantization'' (P4Q), in which we design a lightweight architecture to leverage contrastive loss supervision to enhance the recognition performance of a PTQ model. Our method can effectively reduce the gap between image features and text features caused by low-bit quantization, based on learnable prompts to reorganize textual representations and a low-bit adapter to realign the distributions of image and text features. We also introduce a distillation loss based on cosine similarity predictions to distill the quantized model using a full-precision teacher. Extensive experimental results demonstrate that our P4Q method outperforms prior arts, even achieving comparable results to its full-precision counterparts. For instance, our 8-bit P4Q can theoretically compress the CLIP-ViT/B-32 by 4 $\times$ while achieving 66.94\% Top-1 accuracy, outperforming the learnable prompt fine-tuned full-precision model by 2.24\% with negligible additional parameters on the ImageNet dataset.

[Arxiv](https://arxiv.org/abs/2409.17634)