# MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量

发布时间：2024年04月09日

`LLM理论` `资源效率` `语言模型`

> MiniCPM: Unveiling the Potential of Small Language Models with Scalable Training Strategies

# 摘要

> 随着对参数高达万亿的大型语言模型（LLMs）兴趣的增长，人们开始关注资源效率和实际开销，尤其是实验成本之高。这一现状凸显了挖掘小型语言模型（SLMs）作为节能替代方案的必要性。我们在此背景下推出了MiniCPM，特别是1.2B和2.4B的非嵌入参数版本，它们不仅在各自领域表现卓越，还能与7B-13B LLMs相媲美。我们的研究聚焦SLMs，并在模型和数据的扩展性上展现了未来LLM研究的潜力。在模型扩展上，我们通过大量模型风洞实验实现了稳定和最佳扩展。数据扩展方面，我们提出了一种预热-稳定-衰减（WSD）学习率调度器（LRS），有利于持续训练和领域适应。我们深入分析了WSD LRS中的训练动态。借助WSD LRS，我们能有效探究数据-模型的缩放法则，无需在模型和数据两方面进行大量重新训练实验，从而得出比Chinchilla更优的计算效率。此外，我们还推出了MiniCPM系列，包括MiniCPM-DPO、MiniCPM-MoE和MiniCPM-128K，它们卓越的性能进一步巩固了MiniCPM在多种SLM应用中的地位。这些模型已在https://github.com/OpenBMB/MiniCPM上公开。

> The burgeoning interest in developing Large Language Models (LLMs) with up to trillion parameters has been met with concerns regarding resource efficiency and practical expense, particularly given the immense cost of experimentation. This scenario underscores the importance of exploring the potential of Small Language Models (SLMs) as a resource-efficient alternative. In this context, we introduce MiniCPM, specifically the 1.2B and 2.4B non-embedding parameter variants, not only excel in their respective categories but also demonstrate capabilities on par with 7B-13B LLMs. While focusing on SLMs, our approach exhibits scalability in both model and data dimensions for future LLM research. Regarding model scaling, we employ extensive model wind tunnel experiments for stable and optimal scaling. For data scaling, we introduce a Warmup-Stable-Decay (WSD) learning rate scheduler (LRS), conducive to continuous training and domain adaptation. We present an in-depth analysis of the intriguing training dynamics that occurred in the WSD LRS. With WSD LRS, we are now able to efficiently study data-model scaling law without extensive retraining experiments on both axes of model and data, from which we derive the much higher compute optimal data-model ratio than Chinchilla Optimal. Additionally, we introduce MiniCPM family, including MiniCPM-DPO, MiniCPM-MoE and MiniCPM-128K, whose excellent performance further cementing MiniCPM's foundation in diverse SLM applications. MiniCPM models are available publicly at https://github.com/OpenBMB/MiniCPM .

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/batchsize.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/batchsizeconnect.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/loss_vs_lr.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/x1.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/x2.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/x3.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/x4.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/x5.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/x6.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/x7.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/x8.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/stable_mixture.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/decay_data_mixture.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/x9.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/x10.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/mtbench_graph.jpg)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/x11.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/x12.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/fit_continuetrain.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/x13.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/x14.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/smiling-face-with-smiling-eyes_1f60a.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/face-with-tears-of-joy_1f602.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/smiling-face-with-heart-eyes_1f60d.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/face-blowing-a-kiss_1f618.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/winking-face-with-tongue_1f61c.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/pensive-face_1f614.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/thinking-face_1f914.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/money-mouth-face_1f911.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/folded-hands_1f64f.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/pile-of-poo_1f4a9.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/smiling-face-with-smiling-eyes_1f60a.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/face-with-tears-of-joy_1f602.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/smiling-face-with-heart-eyes_1f60d.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/face-blowing-a-kiss_1f618.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/winking-face-with-tongue_1f61c.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/pensive-face_1f614.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/thinking-face_1f914.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/money-mouth-face_1f911.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/folded-hands_1f64f.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/pile-of-poo_1f4a9.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/smiling-face-with-smiling-eyes_1f60a.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/pouting-face_1f621.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/face-with-tears-of-joy_1f602.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/rolling-on-the-floor-laughing_1f923.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/exploding-head_1f92f.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/pensive-face_1f614.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/broken-heart_1f494.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/light-bulb_1f4a1.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/smiling-face-with-smiling-eyes_1f60a.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/smiling-face-with-heart-eyes_1f60d.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/smiling-face-with-smiling-eyes_1f60a.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/pouting-face_1f621.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/face-with-tears-of-joy_1f602.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/rolling-on-the-floor-laughing_1f923.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/exploding-head_1f92f.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/pensive-face_1f614.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/broken-heart_1f494.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/light-bulb_1f4a1.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/smiling-face-with-smiling-eyes_1f60a.png)

![MiniCPM：借助可扩展训练策略，挖掘小型语言模型的潜在力量](../../../paper_images/2404.06395/smiling-face-with-heart-eyes_1f60d.png)

[Arxiv](https://arxiv.org/abs/2404.06395)