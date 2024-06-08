# GET：一种生成性脑电图Transformer，专为连续基于上下文的神经信号处理而设计。

发布时间：2024年06月05日

`LLM应用

理由：这篇论文介绍了生成式EEG变压器（GET），这是一种专门为脑电图（EEG）数据设计的模型，用于生成连续的神经信号。虽然论文中提到了借鉴NLP领域的训练策略，但其主要关注点是应用这些策略于BCI领域，特别是在EEG信号的生成上。因此，这篇论文更符合LLM应用分类，因为它展示了如何将大型语言模型（LLM）的技术应用于神经信号生成的实际问题中。` `脑机接口`

> GET: A Generative EEG Transformer for continuous context-based neural

# 摘要

> 利用高级人工神经网络生成连续脑电图（EEG）信号，为脑机接口（BCI）技术的飞跃提供了新契机。这一技术潜力巨大，能从模拟脑活动动态到实时癫痫监测和BCI应用等多个方面大幅提升性能。通过专为EEG信号定制的生成式变压器网络，我们有望彻底革新神经数据的解读与互动。生成式AI已在NLP、计算机视觉及艺术音乐内容创作等领域大放异彩，其秘诀在于预训练时利用海量数据构建上下文窗口，这一策略在NLP中尤为见效，模型在基础训练后针对特定任务进行微调。尽管如此，生成式AI在BCI领域的应用，尤其是连续、富含上下文的神经信号生成方面，仍显不足。为此，我们推出了生成式EEG变压器（GET），这一模型专为EEG数据设计，通过在多样化的EEG数据集上预训练，能够生成保持上下文完整性的高质量神经信号。实证显示，GET不仅能精准复现训练数据和输入的频谱，还能稳定生成连续神经信号。借鉴NLP领域的成功训练策略，GET为神经信号生成技术树立了新标杆。

> Generating continuous electroencephalography (EEG) signals through advanced artificial neural networks presents a novel opportunity to enhance brain-computer interface (BCI) technology. This capability has the potential to significantly enhance applications ranging from simulating dynamic brain activity and data augmentation to improving real-time epilepsy detection and BCI inference. By harnessing generative transformer neural networks, specifically designed for EEG signal generation, we can revolutionize the interpretation and interaction with neural data. Generative AI has demonstrated significant success across various domains, from natural language processing (NLP) and computer vision to content creation in visual arts and music. It distinguishes itself by using large-scale datasets to construct context windows during pre-training, a technique that has proven particularly effective in NLP, where models are fine-tuned for specific downstream tasks after extensive foundational training. However, the application of generative AI in the field of BCIs, particularly through the development of continuous, context-rich neural signal generators, has been limited. To address this, we introduce the Generative EEG Transformer (GET), a model leveraging transformer architecture tailored for EEG data. The GET model is pre-trained on diverse EEG datasets, including motor imagery and alpha wave datasets, enabling it to produce high-fidelity neural signals that maintain contextual integrity. Our empirical findings indicate that GET not only faithfully reproduces the frequency spectrum of the training data and input prompts but also robustly generates continuous neural signals. By adopting the successful training strategies of the NLP domain for BCIs, the GET sets a new standard for the development and application of neural signal generation technologies.

[Arxiv](https://arxiv.org/abs/2406.03115)