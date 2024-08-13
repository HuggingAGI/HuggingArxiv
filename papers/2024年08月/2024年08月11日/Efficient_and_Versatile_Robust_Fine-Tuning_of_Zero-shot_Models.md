# 零-shot 模型的鲁棒微调既高效又多功能

发布时间：2024年08月11日

`RAG` `计算机视觉`

> Efficient and Versatile Robust Fine-Tuning of Zero-shot Models

# 摘要

> 大规模图像-文本预训练模型不仅支持零-shot分类，还能在不同数据分布中保持稳定准确性。然而，在下游任务中优化这些模型往往需要微调，这不仅限制了对新数据的泛化能力，还消耗大量计算资源。为此，我们推出了Robust Adapter（R-Adapter），一种创新方法，旨在微调零-shot模型以适应下游任务，同时克服上述难题。R-Adapter通过嵌入轻量级模块并运用先进的自集成技术，有效提升模型对新数据的适应性并大幅削减存储开销。此外，我们设计的MPM-NCE损失专门针对视觉-语言任务的微调，确保图像与文本间精准匹配及特征学习的判别性。通过拓展鲁棒微调的应用领域，涵盖跨模态检索、开放词汇分割等多样任务，R-Adapter展现了其广泛的应用潜力。实验结果显示，R-Adapter在众多任务中均达到顶尖水平，仅调整了CLIP编码器参数的13%。

> Large-scale image-text pre-trained models enable zero-shot classification and provide consistent accuracy across various data distributions. Nonetheless, optimizing these models in downstream tasks typically requires fine-tuning, which reduces generalization to out-of-distribution (OOD) data and demands extensive computational resources. We introduce Robust Adapter (R-Adapter), a novel method for fine-tuning zero-shot models to downstream tasks while simultaneously addressing both these issues. Our method integrates lightweight modules into the pre-trained model and employs novel self-ensemble techniques to boost OOD robustness and reduce storage expenses substantially. Furthermore, we propose MPM-NCE loss designed for fine-tuning on vision-language downstream tasks. It ensures precise alignment of multiple image-text pairs and discriminative feature learning. By extending the benchmark for robust fine-tuning beyond classification to include diverse tasks such as cross-modal retrieval and open vocabulary segmentation, we demonstrate the broad applicability of R-Adapter. Our extensive experiments demonstrate that R-Adapter achieves state-of-the-art performance across a diverse set of tasks, tuning only 13% of the parameters of the CLIP encoders.

[Arxiv](https://arxiv.org/abs/2408.05749)