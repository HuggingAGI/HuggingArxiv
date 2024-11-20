# DLBacktrace：一种适用于任何深度学习模型的、与模型无关的可解释性方法

发布时间：2024年11月19日

`LLM应用` `人工智能`

> DLBacktrace: A Model Agnostic Explainability for any Deep Learning Models

# 摘要

> 人工智能发展迅速，催生了愈发复杂的深度学习模型，这些模型常像不透明的“黑箱”，决策过程透明度有限。这一缺乏可解释性的状况带来了巨大挑战，尤其在高风险应用里，理解模型输出背后的原理和输出本身同等重要。本研究着眼于人工智能系统对可解释性的迫切需求，强调其在培养信任、确保责任和推动关键任务领域合理部署方面的作用。为应对深度学习中的可解释性难题，我们引入了AryaXAI团队研发的创新技术DLBacktrace，用于阐明众多领域的模型决策，涵盖简单多层感知机（MLPs）、卷积神经网络（CNNs）、大型语言模型（LLMs）、计算机视觉模型等。
  我们对DLBacktrace算法进行了全面介绍，并给出了基准测试结果，通过不同任务的指标，将其性能与SHAP、LIME、GradCAM、Integrated Gradients、SmoothGrad和Attention Rollout等已有的可解释性方法进行对比。所提出的DLBacktrace技术与PyTorch和TensorFlow中构建的各类模型架构兼容，支持Llama 3.2等模型、其他NLP架构（如BERT和LSTMs）、ResNet和U-Net等计算机视觉模型，以及用于表格数据的自定义深度神经网络（DNN）模型。这种灵活性彰显了DLBacktrace在提升各类应用中模型透明度方面的适应性和有效性。该库已开源，可在https://github.com/AryaXAI/DLBacktrace获取。

> The rapid advancement of artificial intelligence has led to increasingly sophisticated deep learning models, which frequently operate as opaque 'black boxes' with limited transparency in their decision-making processes. This lack of interpretability presents considerable challenges, especially in high-stakes applications where understanding the rationale behind a model's outputs is as essential as the outputs themselves. This study addresses the pressing need for interpretability in AI systems, emphasizing its role in fostering trust, ensuring accountability, and promoting responsible deployment in mission-critical fields. To address the interpretability challenge in deep learning, we introduce DLBacktrace, an innovative technique developed by the AryaXAI team to illuminate model decisions across a wide array of domains, including simple Multi Layer Perceptron (MLPs), Convolutional Neural Networks (CNNs), Large Language Models (LLMs), Computer Vision Models, and more.
  We provide a comprehensive overview of the DLBacktrace algorithm and present benchmarking results, comparing its performance against established interpretability methods, such as SHAP, LIME, GradCAM, Integrated Gradients, SmoothGrad, and Attention Rollout, using diverse task-based metrics. The proposed DLBacktrace technique is compatible with various model architectures built in PyTorch and TensorFlow, supporting models like Llama 3.2, other NLP architectures such as BERT and LSTMs, computer vision models like ResNet and U-Net, as well as custom deep neural network (DNN) models for tabular data. This flexibility underscores DLBacktrace's adaptability and effectiveness in enhancing model transparency across a broad spectrum of applications. The library is open-sourced and available at https://github.com/AryaXAI/DLBacktrace .

[Arxiv](https://arxiv.org/abs/2411.12643)