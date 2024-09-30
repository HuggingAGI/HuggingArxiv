# MultiClimate：气候变化视频中的多模态立场检测

发布时间：2024年09月26日

`LLM应用` `气候变化` `多模态数据分析`

> MultiClimate: Multimodal Stance Detection on Climate Change Videos

# 摘要

> 近年来，气候变化在 NLP 领域备受关注。然而，在多模态数据中检测对气候变化的立场仍是一个研究不足且充满挑战的领域，主要障碍在于缺乏可靠的数据集。为此，我们推出了 MultiClimate，这是首个开源的手动注释立场检测数据集，涵盖 100 个与气候变化相关的 YouTube 视频及 4,209 个帧-转录对。我们运用了顶尖的视觉与语言模型，以及多模态模型进行立场检测。结果表明，仅使用文本的 BERT 模型在性能上显著超越了仅使用图像的 ResNet50 和 ViT 模型。而结合文本与图像的双模态模型则达到了 0.747/0.749 的准确率/F1 分数，创下新纪录。此外，我们的 100M 规模融合模型在性能上也优于 CLIP、BLIP 以及更大规模的 9B 多模态 IDEFICS 和仅文本的 Llama3、Gemma2 模型，这进一步凸显了多模态立场检测对大型语言模型而言仍是一大挑战。所有相关代码、数据集及补充材料均已公开，详见 https://github.com/werywjw/MultiClimate。

> Climate change (CC) has attracted increasing attention in NLP in recent years. However, detecting the stance on CC in multimodal data is understudied and remains challenging due to a lack of reliable datasets. To improve the understanding of public opinions and communication strategies, this paper presents MultiClimate, the first open-source manually-annotated stance detection dataset with $100$ CC-related YouTube videos and $4,209$ frame-transcript pairs. We deploy state-of-the-art vision and language models, as well as multimodal models for MultiClimate stance detection. Results show that text-only BERT significantly outperforms image-only ResNet50 and ViT. Combining both modalities achieves state-of-the-art, $0.747$/$0.749$ in accuracy/F1. Our 100M-sized fusion models also beat CLIP and BLIP, as well as the much larger 9B-sized multimodal IDEFICS and text-only Llama3 and Gemma2, indicating that multimodal stance detection remains challenging for large language models. Our code, dataset, as well as supplementary materials, are available at https://github.com/werywjw/MultiClimate.

[Arxiv](https://arxiv.org/abs/2409.18346)