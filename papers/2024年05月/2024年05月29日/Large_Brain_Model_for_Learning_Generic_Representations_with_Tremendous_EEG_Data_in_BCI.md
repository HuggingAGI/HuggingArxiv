# 利用海量EEG数据，大型脑模型在BCI中学习通用表示，展现出强大的学习能力。

发布时间：2024年05月29日

`LLM应用

理由：这篇论文探讨了大型EEG模型（LEMs）的应用，特别是在EEG信号处理上的应用。它提出了一个统一的EEG基础模型LaBraM，并通过无监督预训练和微调来提高模型对EEG信号的通用感知力和泛化能力。这与大型语言模型（LLMs）在文本处理上的应用类似，因此属于LLM应用类别。此外，论文中提到的模型设计和训练方法，以及其在多个下游任务上的应用验证，都强调了其在实际应用中的价值和效果，进一步支持了这一分类。` `脑机接口` `神经科学`

> Large Brain Model for Learning Generic Representations with Tremendous EEG Data in BCI

# 摘要

> 当前的EEG深度学习模型多针对特定BCI数据集设计，限制了其感知与泛化能力。借鉴LLMs在文本处理上的成功，我们探索了大型EEG模型（LEMs），旨在通过无监督预训练赋予模型对EEG信号的通用感知力，并针对各类下游任务进行微调。但EEG数据集规模小、格式多变，如电极数、数据长度、任务设计不一，信噪比低。为此，我们提出了统一EEG基础模型LaBraM，通过分割EEG信号为通道补丁实现跨数据集学习，并利用向量量化神经频谱预测训练神经标记器，将原始EEG通道补丁编码为紧凑神经代码，预训练神经Transformer以预测掩码通道补丁的原始代码。LaBraM在约2500小时、来自20个不同类型的EEG信号上预训练，并在多类下游任务上验证，结果显示在异常检测、事件分类、情绪识别及步态预测等领域均超越现有最佳方法。代码地址：https://github.com/935963004/LaBraM。

> The current electroencephalogram (EEG) based deep learning models are typically designed for specific datasets and applications in brain-computer interaction (BCI), limiting the scale of the models and thus diminishing their perceptual capabilities and generalizability. Recently, Large Language Models (LLMs) have achieved unprecedented success in text processing, prompting us to explore the capabilities of Large EEG Models (LEMs). We hope that LEMs can break through the limitations of different task types of EEG datasets, and obtain universal perceptual capabilities of EEG signals through unsupervised pre-training. Then the models can be fine-tuned for different downstream tasks. However, compared to text data, the volume of EEG datasets is generally small and the format varies widely. For example, there can be mismatched numbers of electrodes, unequal length data samples, varied task designs, and low signal-to-noise ratio. To overcome these challenges, we propose a unified foundation model for EEG called Large Brain Model (LaBraM). LaBraM enables cross-dataset learning by segmenting the EEG signals into EEG channel patches. Vector-quantized neural spectrum prediction is used to train a semantically rich neural tokenizer that encodes continuous raw EEG channel patches into compact neural codes. We then pre-train neural Transformers by predicting the original neural codes for the masked EEG channel patches. The LaBraMs were pre-trained on about 2,500 hours of various types of EEG signals from around 20 datasets and validated on multiple different types of downstream tasks. Experiments on abnormal detection, event type classification, emotion recognition, and gait prediction show that our LaBraM outperforms all compared SOTA methods in their respective fields. Our code is available at https://github.com/935963004/LaBraM.

![利用海量EEG数据，大型脑模型在BCI中学习通用表示，展现出强大的学习能力。](../../../paper_images/2405.18765/x1.png)

![利用海量EEG数据，大型脑模型在BCI中学习通用表示，展现出强大的学习能力。](../../../paper_images/2405.18765/x2.png)

![利用海量EEG数据，大型脑模型在BCI中学习通用表示，展现出强大的学习能力。](../../../paper_images/2405.18765/x3.png)

![利用海量EEG数据，大型脑模型在BCI中学习通用表示，展现出强大的学习能力。](../../../paper_images/2405.18765/x4.png)

![利用海量EEG数据，大型脑模型在BCI中学习通用表示，展现出强大的学习能力。](../../../paper_images/2405.18765/x5.png)

![利用海量EEG数据，大型脑模型在BCI中学习通用表示，展现出强大的学习能力。](../../../paper_images/2405.18765/x6.png)

![利用海量EEG数据，大型脑模型在BCI中学习通用表示，展现出强大的学习能力。](../../../paper_images/2405.18765/x7.png)

![利用海量EEG数据，大型脑模型在BCI中学习通用表示，展现出强大的学习能力。](../../../paper_images/2405.18765/x8.png)

[Arxiv](https://arxiv.org/abs/2405.18765)