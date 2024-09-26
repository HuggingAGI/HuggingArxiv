# Semi-LLIE：结合 Mamba 技术，通过半监督对比学习提升低光图像增强效果

发布时间：2024年09月25日

`LLM应用` `图像处理` `计算机视觉`

> Semi-LLIE: Semi-supervised Contrastive Learning with Mamba-based Low-light Image Enhancement

# 摘要

> 尽管低光图像增强技术取得了显著进展，但配对数据的缺乏仍是瓶颈。为此，我们提出了一种基于均值教师的半监督框架（Semi-LLIE），将未配对数据融入训练。然而，朴素均值教师方法在低光增强中面临两大挑战：像素级一致性损失导致色彩失真，以及现有方法忽视局部结构信息，难以恢复细节。为解决这些问题，我们引入了语义感知的对比损失，确保照明分布的准确传递，并设计了基于Mamba的增强骨干网络，通过多尺度特征学习提升细节表现。此外，我们利用大规模视觉语言模型（RAM）的感知损失，进一步丰富图像文本细节。实验证明，Semi-LLIE在各项指标上均超越现有技术。

> Despite the impressive advancements made in recent low-light image enhancement techniques, the scarcity of paired data has emerged as a significant obstacle to further advancements. This work proposes a mean-teacher-based semi-supervised low-light enhancement (Semi-LLIE) framework that integrates the unpaired data into model training. The mean-teacher technique is a prominent semi-supervised learning method, successfully adopted for addressing high-level and low-level vision tasks. However, two primary issues hinder the naive mean-teacher method from attaining optimal performance in low-light image enhancement. Firstly, pixel-wise consistency loss is insufficient for transferring realistic illumination distribution from the teacher to the student model, which results in color cast in the enhanced images. Secondly, cutting-edge image enhancement approaches fail to effectively cooperate with the mean-teacher framework to restore detailed information in dark areas due to their tendency to overlook modeling structured information within local regions. To mitigate the above issues, we first introduce a semantic-aware contrastive loss to faithfully transfer the illumination distribution, contributing to enhancing images with natural colors. Then, we design a Mamba-based low-light image enhancement backbone to effectively enhance Mamba's local region pixel relationship representation ability with a multi-scale feature learning scheme, facilitating the generation of images with rich textural details. Further, we propose novel perceptive loss based on the large-scale vision-language Recognize Anything Model (RAM) to help generate enhanced images with richer textual details. The experimental results indicate that our Semi-LLIE surpasses existing methods in both quantitative and qualitative metrics.

[Arxiv](https://arxiv.org/abs/2409.16604)