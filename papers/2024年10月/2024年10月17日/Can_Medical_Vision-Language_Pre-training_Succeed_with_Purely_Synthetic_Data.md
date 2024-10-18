# 医学视觉-语言预训练，能否仅凭纯合成数据大获成功？

发布时间：2024年10月17日

`LLM应用` `人工智能`

> Can Medical Vision-Language Pre-training Succeed with Purely Synthetic Data?

# 摘要

> 医学视觉-语言预训练 (MedVLP) 在医学图像理解的零-shot 任务中取得了显著进展。然而，训练 MedVLP 模型需要大规模的高质量图像-文本数据，这在医学领域非常稀缺。最近，大语言模型 (LLM) 和扩散模型的进步使得生成大规模合成图像-文本对成为可能。这引发了一个问题：*MedVLP 能否仅依靠合成数据取得成功？* 为此，我们使用现成的生成模型创建了合成的放射报告和胸部 X 光图像，并构建了一个多样化的、高质量的合成数据集。我们的研究表明，仅在合成数据上训练的 MedVLP 模型在零-shot 分类的平均 AUC 上优于真实数据训练的模型 **3.8%**。同时，合成数据与真实数据的结合进一步提升了 **9.07%**。此外，在合成或混合数据上训练的 MedVLP 模型在零-shot 定位以及微调分类和分割任务中表现更佳。我们的分析表明，精心设计的合成数据训练的 MedVLP 可以超越受限于低质量样本和长尾分布的真实数据集训练的模型。

> Medical Vision-Language Pre-training (MedVLP) has made significant progress in enabling zero-shot tasks for medical image understanding. However, training MedVLP models typically requires large-scale datasets with paired, high-quality image-text data, which are scarce in the medical domain. Recent advancements in Large Language Models (LLMs) and diffusion models have made it possible to generate large-scale synthetic image-text pairs. This raises the question: *Can MedVLP succeed using purely synthetic data?* To address this, we use off-the-shelf generative models to create synthetic radiology reports and paired Chest X-ray (CXR) images, and propose an automated pipeline to build a diverse, high-quality synthetic dataset, enabling a rigorous study that isolates model and training settings, focusing entirely from the data perspective. Our results show that MedVLP models trained *exclusively on synthetic data* outperform those trained on real data by **3.8%** in averaged AUC on zero-shot classification. Moreover, using a combination of synthetic and real data leads to a further improvement of **9.07%**. Additionally, MedVLP models trained on synthetic or mixed data consistently outperform those trained on real data in zero-shot grounding, as well as in fine-tuned classification and segmentation tasks. Our analysis suggests MedVLP trained on well-designed synthetic data can outperform models trained on real datasets, which may be limited by low-quality samples and long-tailed distributions.

[Arxiv](https://arxiv.org/abs/2410.13523)