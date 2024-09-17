# NEVLP：一个噪声鲁棒的高效视觉语言预训练框架

发布时间：2024年09月14日

`LLM应用` `计算机视觉`

> NEVLP: Noise-Robust Framework for Efficient Vision-Language Pre-training

# 摘要

> 视觉语言模型 (VLM) 的成功离不开大规模网络爬取数据的预训练。然而，网络数据的噪声和不完整性使得数据集规模对性能至关重要，导致端到端训练越来越难以实现。为此，我们提出了 NEVLP，一个噪声鲁棒的框架，用于高效的视觉语言预训练，仅需较少的预训练数据。我们通过变换器连接冻结的图像编码器和大型语言模型，并引入了噪声自适应学习和概念增强学习两种创新策略，以减轻噪声影响。噪声自适应学习通过变换器的记忆效应估计噪声概率，并采用噪声自适应正则化来调节跨模态对齐。概念增强学习则通过结合视觉概念丰富不完整文本，为图像-文本匹配和基于图像的文本生成提供先验信息，从而减轻文本不完整性。我们的框架在广泛的视觉语言任务中，包括图像-文本检索、图像描述生成和视觉问答，以较少的预训练数据实现了最先进的性能。

> The success of Vision Language Models (VLMs) on various vision-language tasks heavily relies on pre-training with large scale web-crawled datasets. However, the noisy and incomplete nature of web data makes dataset scale crucial for performance, rendering end-to-end training increasingly prohibitive. In this paper, we propose NEVLP, a noise-robust framework for efficient vision-language pre-training that requires less pre-training data. Specifically, we bridge the modality gap between a frozen image encoder and a large language model with a transformer and introduce two innovative learning strategies: noise-adaptive learning and concept-enhanced learning to mitigate the impact of noise. In noise-adaptive learning, we estimate the noise probability of each image-text pair based on the transformer's memorization effect and employ noise-adaptive regularization on image-text contrastive learning to condition cross-modal alignment. In concept-enhanced learning, we enrich incomplete text by incorporating visual concepts (objects in the image) to provide prior information about existing objects for image-text matching and image-grounded text generation, thereby mitigating text incompletion. Our framework effectively utilizes noisy web data and achieves state-of-the-art performance with less pre-training data across a wide range of vision-language tasks, including image-text retrieval, image captioning, and visual question answering.

[Arxiv](https://arxiv.org/abs/2409.09582)