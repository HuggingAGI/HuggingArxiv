# PV-VTT：一个聚焦隐私的数据集，用于特定任务中的异常检测与自然语言解释

发布时间：2024年10月29日

`LLM应用` `计算机视觉` `犯罪检测`

> PV-VTT: A Privacy-Centric Dataset for Mission-Specific Anomaly Detection and Natural Language Interpretation

# 摘要

> 视频犯罪检测是计算机视觉和人工智能的重要应用。然而，现有的数据集多是通过分析整个视频片段来检测严重犯罪，常常忽视了可能预防犯罪的前兆活动（比如隐私侵犯）。为突破这一局限，我们推出了 PV-VTT（隐私侵犯视频转文本）这一独特的多模态数据集，旨在识别隐私侵犯行为。PV-VTT 对场景中的视频和文本都做了详细注释。为保障视频中个人的隐私，我们仅提供视频特征向量，不发布任何原始视频数据。这种注重隐私的方式让研究人员在使用数据集时能保护参与者的机密。鉴于隐私侵犯通常具有模糊性和上下文依赖性，我们提出了基于图神经网络（GNN）的视频描述模型。我们的模型为大型语言模型（LLM）生成基于 GNN 且带有图像的提示，给出了性价比高且质量优的视频描述。通过利用单个视频帧及相关文本，我们的方法减少了所需的输入令牌数，在保持描述质量的同时优化了 LLM API 的使用。大量实验证明了我们的方法在视频描述任务中的有效性和可解释性，也验证了我们 PV-VTT 数据集的灵活性。

> Video crime detection is a significant application of computer vision and artificial intelligence. However, existing datasets primarily focus on detecting severe crimes by analyzing entire video clips, often neglecting the precursor activities (i.e., privacy violations) that could potentially prevent these crimes. To address this limitation, we present PV-VTT (Privacy Violation Video To Text), a unique multimodal dataset aimed at identifying privacy violations. PV-VTT provides detailed annotations for both video and text in scenarios. To ensure the privacy of individuals in the videos, we only provide video feature vectors, avoiding the release of any raw video data. This privacy-focused approach allows researchers to use the dataset while protecting participant confidentiality. Recognizing that privacy violations are often ambiguous and context-dependent, we propose a Graph Neural Network (GNN)-based video description model. Our model generates a GNN-based prompt with image for Large Language Model (LLM), which deliver cost-effective and high-quality video descriptions. By leveraging a single video frame along with relevant text, our method reduces the number of input tokens required, maintaining descriptive quality while optimizing LLM API-usage. Extensive experiments validate the effectiveness and interpretability of our approach in video description tasks and flexibility of our PV-VTT dataset.

[Arxiv](https://arxiv.org/abs/2410.22623)