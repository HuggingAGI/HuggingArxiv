# XLSR-Transducer：为自监督预训练模型设计的流式自动语音识别技术

发布时间：2024年07月05日

`LLM应用` `语音识别` `流式处理`

> XLSR-Transducer: Streaming ASR for Self-Supervised Pretrained Models

# 摘要

> 自监督预训练模型在自动语音识别的微调中表现出色，即便训练数据有限。但这些流行的预训练模型因采用全注意力上下文训练而不适用于流式ASR。本文介绍的XLSR-Transducer，以XLSR-53模型为编码器，在AMI数据集上显著提升了性能，相对Whisper large-v2和Zipformer转换器模型分别有4%和8%的WER改进。为实现流式处理，我们探索了XLSR-53模型中转换器层自注意力计算的不同掩蔽模式，并在低资源环境下验证了其在AMI和CommonVoice五种语言上的有效性。通过引入注意力下沉技术，我们不仅将左侧上下文减半，还实现了12%的WER相对提升。

> Self-supervised pretrained models exhibit competitive performance in automatic speech recognition on finetuning, even with limited in-domain supervised data for training. However, popular pretrained models are not suitable for streaming ASR because they are trained with full attention context. In this paper, we introduce XLSR-Transducer, where the XLSR-53 model is used as encoder in transducer setup. Our experiments on the AMI dataset reveal that the XLSR-Transducer achieves 4% absolute WER improvement over Whisper large-v2 and 8% over a Zipformer transducer model trained from scratch.To enable streaming capabilities, we investigate different attention masking patterns in the self-attention computation of transformer layers within the XLSR-53 model. We validate XLSR-Transducer on AMI and 5 languages from CommonVoice under low-resource scenarios. Finally, with the introduction of attention sinks, we reduce the left context by half while achieving a relative 12% improvement in WER.

![XLSR-Transducer：为自监督预训练模型设计的流式自动语音识别技术](../../../paper_images/2407.04439/x1.png)

![XLSR-Transducer：为自监督预训练模型设计的流式自动语音识别技术](../../../paper_images/2407.04439/x2.png)

![XLSR-Transducer：为自监督预训练模型设计的流式自动语音识别技术](../../../paper_images/2407.04439/x3.png)

![XLSR-Transducer：为自监督预训练模型设计的流式自动语音识别技术](../../../paper_images/2407.04439/x4.png)

![XLSR-Transducer：为自监督预训练模型设计的流式自动语音识别技术](../../../paper_images/2407.04439/x5.png)

[Arxiv](https://arxiv.org/abs/2407.04439)