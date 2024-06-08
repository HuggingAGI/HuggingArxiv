# GET：一种生成性脑电图变换器，专为连续基于上下文的神经信号处理而设计。

发布时间：2024年06月05日

`Agent

理由：这篇论文主要介绍了生成式EEG变压器（GET），这是一种专为脑电图（EEG）信号优化的变压器架构模型，用于生成连续的神经信号。虽然论文中提到了生成式AI在NLP领域的应用，但其核心贡献在于开发了一种新的模型来处理EEG数据，这在脑机接口（BCI）技术中具有实际应用价值。因此，这篇论文更符合Agent分类，因为它涉及到了特定领域的技术应用和改进，而不是纯粹的理论研究或LLM的应用。` `脑机接口` `医疗监测`

> GET: A Generative EEG Transformer for continuous context-based neural

# 摘要

> 利用高级人工神经网络生成连续脑电图（EEG）信号，为脑机接口（BCI）技术的革新开辟了新途径。这种技术潜力巨大，能从模拟脑活动动态到实时癫痫监测和BCI应用中大幅提升性能。我们通过专为EEG信号设计的生成式变压器网络，彻底改变了神经数据的解读与交互方式。生成式AI已在NLP、计算机视觉及艺术音乐创作等多个领域取得显著成就，其利用大规模数据集在预训练中构建上下文窗口的技术，在NLP领域尤为有效。尽管如此，生成式AI在BCI领域的应用，尤其是连续神经信号生成方面，仍显不足。为此，我们推出了生成式EEG变压器（GET），一种专为EEG数据优化的变压器架构模型。GET在多种EEG数据集上预训练，能生成保持上下文完整性的高质量神经信号。实证研究表明，GET不仅能准确再现训练数据的频谱特性，还能稳定生成连续神经信号。借鉴NLP领域的成功训练策略，GET为神经信号生成技术的发展和应用设定了新标杆。

> Generating continuous electroencephalography (EEG) signals through advanced artificial neural networks presents a novel opportunity to enhance brain-computer interface (BCI) technology. This capability has the potential to significantly enhance applications ranging from simulating dynamic brain activity and data augmentation to improving real-time epilepsy detection and BCI inference. By harnessing generative transformer neural networks, specifically designed for EEG signal generation, we can revolutionize the interpretation and interaction with neural data. Generative AI has demonstrated significant success across various domains, from natural language processing (NLP) and computer vision to content creation in visual arts and music. It distinguishes itself by using large-scale datasets to construct context windows during pre-training, a technique that has proven particularly effective in NLP, where models are fine-tuned for specific downstream tasks after extensive foundational training. However, the application of generative AI in the field of BCIs, particularly through the development of continuous, context-rich neural signal generators, has been limited. To address this, we introduce the Generative EEG Transformer (GET), a model leveraging transformer architecture tailored for EEG data. The GET model is pre-trained on diverse EEG datasets, including motor imagery and alpha wave datasets, enabling it to produce high-fidelity neural signals that maintain contextual integrity. Our empirical findings indicate that GET not only faithfully reproduces the frequency spectrum of the training data and input prompts but also robustly generates continuous neural signals. By adopting the successful training strategies of the NLP domain for BCIs, the GET sets a new standard for the development and application of neural signal generation technologies.

[Arxiv](https://arxiv.org/abs/2406.03115)