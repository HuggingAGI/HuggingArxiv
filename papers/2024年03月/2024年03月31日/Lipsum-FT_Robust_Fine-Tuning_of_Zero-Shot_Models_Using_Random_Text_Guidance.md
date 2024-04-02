# Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调

发布时间：2024年03月31日

`RAG` `视觉-语言模型` `机器学习`

> Lipsum-FT: Robust Fine-Tuning of Zero-Shot Models Using Random Text Guidance

# 摘要

> 大规模对比视觉-语言预训练模型无需针对特定下游数据进行训练，便能在众多图像分类任务中展现出色性能。然而，对这些零-shot模型进行额外微调虽可提升性能，却可能减弱其对数据分布变化的适应能力。本研究首先探究了实现鲁棒微调所需满足的条件，并基于特征失真理论和联合能量模型提出了相应的描述。接着，我们引入了一种创新的鲁棒微调算法Lipsum-FT，该算法充分发挥了视觉-语言预训练模型在语言建模方面的优势。通过在DomainNet和ImageNet上的分布变化场景进行的广泛测试，我们的Lipsum-FT方法已被证实优于现有的鲁棒微调技术。

> Large-scale contrastive vision-language pre-trained models provide the zero-shot model achieving competitive performance across a range of image classification tasks without requiring training on downstream data. Recent works have confirmed that while additional fine-tuning of the zero-shot model on the reference data results in enhanced downstream performance, it compromises the model's robustness against distribution shifts. Our investigation begins by examining the conditions required to achieve the goals of robust fine-tuning, employing descriptions based on feature distortion theory and joint energy-based models. Subsequently, we propose a novel robust fine-tuning algorithm, Lipsum-FT, that effectively utilizes the language modeling aspect of the vision-language pre-trained models. Extensive experiments conducted on distribution shift scenarios in DomainNet and ImageNet confirm the superiority of our proposed Lipsum-FT approach over existing robust fine-tuning methods.

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x1.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x2.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x3.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x4.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x5.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x6.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x7.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x8.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x9.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x10.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x11.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x12.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x13.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x14.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x15.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x16.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x17.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x18.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x19.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x20.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x21.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x22.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x23.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x24.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x25.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x26.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x27.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x28.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x29.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x30.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x31.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x32.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x33.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x34.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x35.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x36.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x37.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x38.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x39.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x40.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/_tnse_dnet.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/_tnse_inet.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x41.png)

![Lipsum-FT：借助随机文本引导，实现零-shot模型的稳健微调](../../../paper_images/2404.00860/x42.png)

[Arxiv](https://arxiv.org/abs/2404.00860)