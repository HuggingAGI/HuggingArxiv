# 自监督无线电预训练：朝着用于频谱图学习的基础模型迈进

发布时间：2024年11月14日

`其他` `无线电`

> Self-Supervised Radio Pre-training: Toward Foundational Models for Spectrogram Learning

# 摘要

> 基础深度学习（DL）模型是通用型的，通过在大型、多样且未标注的数据集中训练，通常运用自监督学习技术，在自然语言处理等领域取得了显著进步。这些预训练模型能针对相关下游任务进行微调，加快开发速度、降低训练成本，且常常能提升性能。在本研究中，我们推出了掩码频谱建模，这是一种用于在无线电信号上预训练基础DL模型的全新自监督学习方式。采用卷积LSTM架构实现高效的时空处理，我们用从空中测量收集的未标注无线电数据集对模型进行预训练。接着，针对频谱预测和分割这两个下游任务对预训练模型进行微调。实验结果显示，我们的方法在预测精度和分割方面均表现出有竞争力的性能，证实了其在开发基础无线电模型方面的有效性。

> Foundational deep learning (DL) models are general models, trained on large, diverse, and unlabelled datasets, typically using self-supervised learning techniques have led to significant advancements especially in natural language processing. These pretrained models can be fine-tuned for related downstream tasks, offering faster development and reduced training costs, while often achieving improved performance. In this work, we introduce Masked Spectrogram Modeling, a novel self-supervised learning approach for pretraining foundational DL models on radio signals. Adopting a Convolutional LSTM architecture for efficient spatio-temporal processing, we pretrain the model with an unlabelled radio dataset collected from over-the-air measurements. Subsequently, the pretrained model is fine-tuned for two downstream tasks: spectrum forecasting and segmentation. Experimental results demonstrate that our methodology achieves competitive performance in both forecasting accuracy and segmentation, validating its effectiveness for developing foundational radio models.

[Arxiv](https://arxiv.org/abs/2411.09849)