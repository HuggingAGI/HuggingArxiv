# CLIP-DFGS：一种专为 CLIP 设计的困难样本挖掘方法，助力人物重识别的泛化能力。

发布时间：2024年10月15日

`LLM应用` `人工智能`

> CLIP-DFGS: A Hard Sample Mining Method for CLIP in Generalizable Person Re-Identification

# 摘要

> 近期，CLIP 等预训练视觉-语言模型在人物重识别 (ReID) 领域展现出潜力，但在泛化任务中表现仍不尽如人意。这可能源于 CLIP 预训练数据集中大规模多样化的图像-文本对未能充分捕捉某些细粒度特征。为此，我们提出了基于深度优先搜索的硬样本挖掘方法 DFGS，旨在通过提供更具挑战性的样本来强化 CLIP 的细粒度特征提取能力。DFGS 可同时应用于图像和文本编码器。借助 CLIP 的跨模态学习优势，我们利用 DFGS 提取高难度样本，构建具有高度区分性的迷你批次，从而为模型提供更难以区分的挑战性样本，提升其个体识别能力。实验结果表明，DFGS 显著优于其他方法，证实了其在提升 CLIP 泛化 ReID 性能中的有效性。

> Recent advancements in pre-trained vision-language models like CLIP have shown promise in person re-identification (ReID) applications. However, their performance in generalizable person re-identification tasks remains suboptimal. The large-scale and diverse image-text pairs used in CLIP's pre-training may lead to a lack or insufficiency of certain fine-grained features. In light of these challenges, we propose a hard sample mining method called DFGS (Depth-First Graph Sampler), based on depth-first search, designed to offer sufficiently challenging samples to enhance CLIP's ability to extract fine-grained features. DFGS can be applied to both the image encoder and the text encoder in CLIP. By leveraging the powerful cross-modal learning capabilities of CLIP, we aim to apply our DFGS method to extract challenging samples and form mini-batches with high discriminative difficulty, providing the image model with more efficient and challenging samples that are difficult to distinguish, thereby enhancing the model's ability to differentiate between individuals. Our results demonstrate significant improvements over other methods, confirming the effectiveness of DFGS in providing challenging samples that enhance CLIP's performance in generalizable person re-identification.

[Arxiv](https://arxiv.org/abs/2410.11255)