# 针对视觉语言模型时代中语义分割的无监督域适应的研究

发布时间：2024年11月25日

`其他` `自动驾驶` `计算机视觉`

> A Study on Unsupervised Domain Adaptation for Semantic Segmentation in the Era of Vision-Language Models

# 摘要

> 尽管基于深度学习的计算机视觉近期有所进步，但领域迁移依旧是重大挑战之一。自动驾驶的语义分割面临着诸多领域迁移问题，比如因天气变化、新地理位置以及模型训练中频繁使用合成数据所引发的。无监督领域适应（UDA）方法应运而生，仅凭借该领域的未标注数据就能让模型适应新的目标领域。UDA 方法多种多样，但都采用 ImageNet 预训练模型。近来，视觉语言模型展现出强大的泛化能力，或许有助于领域适应。我们发现，仅把像 DACS 这类现有 UDA 方法的编码器换成视觉语言预训练编码器，在 GTA5 到 Cityscapes 的领域迁移中，性能能大幅提升，mIoU 最多提高 10.0％。就未见过领域的泛化性能而言，新采用的视觉语言预训练编码器在三个未见过的数据集上，mIoU 最多能增加 13.7％。不过，我们发现并非所有 UDA 方法都能轻易与新编码器适配，而且 UDA 性能并非总能转化为泛化性能。最后，我们在不利天气条件的领域迁移中开展实验，进一步验证在纯真实到真实领域迁移方面的发现。

> Despite the recent progress in deep learning based computer vision, domain shifts are still one of the major challenges. Semantic segmentation for autonomous driving faces a wide range of domain shifts, e.g. caused by changing weather conditions, new geolocations and the frequent use of synthetic data in model training. Unsupervised domain adaptation (UDA) methods have emerged which adapt a model to a new target domain by only using unlabeled data of that domain. The variety of UDA methods is large but all of them use ImageNet pre-trained models. Recently, vision-language models have demonstrated strong generalization capabilities which may facilitate domain adaptation. We show that simply replacing the encoder of existing UDA methods like DACS by a vision-language pre-trained encoder can result in significant performance improvements of up to 10.0% mIoU on the GTA5-to-Cityscapes domain shift. For the generalization performance to unseen domains, the newly employed vision-language pre-trained encoder provides a gain of up to 13.7% mIoU across three unseen datasets. However, we find that not all UDA methods can be easily paired with the new encoder and that the UDA performance does not always likewise transfer into generalization performance. Finally, we perform our experiments on an adverse weather condition domain shift to further verify our findings on a pure real-to-real domain shift.

[Arxiv](https://arxiv.org/abs/2411.16407)