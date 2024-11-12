# 通过多模态自监督学习增强心血管疾病预测

发布时间：2024年11月08日

`其他` `心血管疾病预测`

> Enhancing Cardiovascular Disease Prediction through Multi-Modal Self-Supervised Learning

# 摘要

> 心血管疾病的准确预测对于早期诊断和干预仍然至关重要，这需要强大而精确的预测模型。最近，人们对多模态学习越来越感兴趣，以发现仅通过单模态数据集无法获得的新见解。通过结合心脏磁共振图像、心电图信号和可用的医疗信息，我们的方法能够利用跨模态的共享信息捕获个人心血管健康的整体状况。整合来自多个模态的信息并受益于自监督学习技术，我们的模型为在有限的注释数据集中增强心血管疾病预测提供了一个全面的框架。
    我们使用掩码自动编码器对心电图（ECG）编码器进行预训练，使其能够从原始心电图数据中提取相关特征，并使用图像编码器从心脏磁共振图像中提取相关特征。随后，我们利用多模态对比学习目标将知识从昂贵且复杂的模态（心脏磁共振图像）转移到便宜且简单的模态，如心电图和医疗信息。最后，我们在特定的预测任务（如心肌梗死）上对预训练的编码器进行微调。我们提出的方法通过利用不同的可用模态增强了图像信息，在平衡准确率方面比监督方法高出 7.6%。

> Accurate prediction of cardiovascular diseases remains imperative for early diagnosis and intervention, necessitating robust and precise predictive models. Recently, there has been a growing interest in multi-modal learning for uncovering novel insights not available through uni-modal datasets alone. By combining cardiac magnetic resonance images, electrocardiogram signals, and available medical information, our approach enables the capture of holistic status about individuals' cardiovascular health by leveraging shared information across modalities. Integrating information from multiple modalities and benefiting from self-supervised learning techniques, our model provides a comprehensive framework for enhancing cardiovascular disease prediction with limited annotated datasets.
  We employ a masked autoencoder to pre-train the electrocardiogram ECG encoder, enabling it to extract relevant features from raw electrocardiogram data, and an image encoder to extract relevant features from cardiac magnetic resonance images. Subsequently, we utilize a multi-modal contrastive learning objective to transfer knowledge from expensive and complex modality, cardiac magnetic resonance image, to cheap and simple modalities such as electrocardiograms and medical information. Finally, we fine-tuned the pre-trained encoders on specific predictive tasks, such as myocardial infarction. Our proposed method enhanced the image information by leveraging different available modalities and outperformed the supervised approach by 7.6% in balanced accuracy.

[Arxiv](https://arxiv.org/abs/2411.05900)