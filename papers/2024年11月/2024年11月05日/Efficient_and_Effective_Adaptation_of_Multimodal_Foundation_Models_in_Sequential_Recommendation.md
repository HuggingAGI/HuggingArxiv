# 在顺序推荐中多模态基础模型的高效和有效适应

发布时间：2024年11月05日

`其他` `推荐系统` `多模态`

> Efficient and Effective Adaptation of Multimodal Foundation Models in Sequential Recommendation

# 摘要

> 多模态基础模型（MFMs）通过先进的表示学习彻底改变了顺序推荐系统。虽然参数高效微调（PEFT）通常用于适配这些模型，但研究往往优先考虑参数效率，而忽略了 GPU 内存和训练速度。为了解决这个问题，我们引入了 IISAN 框架，显著提高了效率。然而，IISAN 仅限于对称的 MFMs 以及相同的文本和图像编码器，阻碍了使用最先进的大型语言模型。为了克服这一点，我们开发了 IISAN-Versa，这是一种通用的即插即用架构，与对称和非对称的 MFMs 都兼容。IISAN-Versa 采用解耦的 PEFT 结构，并利用了模态内和模态间的适配。它通过组层丢弃和维度变换对齐的简单而有效的组合有效地处理了不对称性。我们的研究表明，IISAN-Versa 有效地适配了大型文本编码器，并且我们进一步确定了一种缩放效应，即通常较大的编码器表现更好。IISAN-Versa 在我们定义的多模态场景中也表现出强大的通用性，这些场景包括从图像和视频生成的原始标题和说明。此外，IISAN-Versa 在 Microlens 公共基准上取得了最先进的性能。我们将发布我们的代码和数据集以支持未来的研究。

> Multimodal foundation models (MFMs) have revolutionized sequential recommender systems through advanced representation learning. While Parameter-efficient Fine-tuning (PEFT) is commonly used to adapt these models, studies often prioritize parameter efficiency, neglecting GPU memory and training speed. To address this, we introduced the IISAN framework, significantly enhancing efficiency. However, IISAN was limited to symmetrical MFMs and identical text and image encoders, preventing the use of state-of-the-art Large Language Models. To overcome this, we developed IISAN-Versa, a versatile plug-and-play architecture compatible with both symmetrical and asymmetrical MFMs. IISAN-Versa employs a Decoupled PEFT structure and utilizes both intra- and inter-modal adaptation. It effectively handles asymmetry through a simple yet effective combination of group layer-dropping and dimension transformation alignment. Our research demonstrates that IISAN-Versa effectively adapts large text encoders, and we further identify a scaling effect where larger encoders generally perform better. IISAN-Versa also demonstrates strong versatility in our defined multimodal scenarios, which include raw titles and captions generated from images and videos. Additionally, IISAN-Versa achieved state-of-the-art performance on the Microlens public benchmark. We will release our code and datasets to support future research.

[Arxiv](https://arxiv.org/abs/2411.02992)