# ConVis：利用幻觉可视化技术进行对比解码，有效减轻多模态大型语言模型中的幻觉问题。

发布时间：2024年08月25日

`LLM应用` `人工智能` `图像处理`

> ConVis: Contrastive Decoding with Hallucination Visualization for Mitigating Hallucinations in Multimodal Large Language Models

# 摘要

> 多模态大型语言模型 (MLLMs) 在生成响应时若未能准确反映图像内容，其可靠性面临挑战。为此，我们创新性地提出了 ConVis，一种无需额外训练的对比解码技术。ConVis 通过文本到图像 (T2I) 模型，从幻觉描述中重建图像，进而对比原始与重建图像的概率分布，帮助 MLLMs 捕捉并抑制幻觉信号。这一方法简便高效，无需额外数据或模型调整，已在多个基准测试中证实能有效减少幻觉，提升模型可靠性。

> Hallucinations in Multimodal Large Language Models (MLLMs) where generated responses fail to accurately reflect the given image pose a significant challenge to their reliability. To address this, we introduce ConVis, a novel training-free contrastive decoding method. ConVis leverages a text-to-image (T2I) generation model to semantically reconstruct the given image from hallucinated captions. By comparing the contrasting probability distributions produced by the original and reconstructed images, ConVis enables MLLMs to capture visual contrastive signals that penalize hallucination generation. Notably, this method operates purely within the decoding process, eliminating the need for additional data or model updates. Our extensive experiments on five popular benchmarks demonstrate that ConVis effectively reduces hallucinations across various MLLMs, highlighting its potential to enhance model reliability.

[Arxiv](https://arxiv.org/abs/2408.13906)