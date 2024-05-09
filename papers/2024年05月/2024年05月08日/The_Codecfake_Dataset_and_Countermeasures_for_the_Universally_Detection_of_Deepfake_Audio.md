# Codecfake数据集与深度伪造音频检测的通用对策在这项研究中，我们介绍了Codecfake数据集，这是一个专为深度伪造音频检测而设计的新型数据集。我们的目标是提供一个全面的资源，以帮助研究人员开发和测试针对深度伪造音频的检测算法。此外，我们还探讨了一系列反制措施，旨在提高检测算法的鲁棒性和准确性，以应对不断进化的深度伪造技术。通过结合数据集和反制措施，我们希望推动该领域的研究，并为保护公众免受深度伪造音频的潜在威胁做出贡献。

发布时间：2024年05月08日

`Agent

这篇论文主要关注的是基于ALM（可能是指某种特定的大型模型，如生成对抗网络GAN或变分自编码器VAE等）的深度伪造音频检测问题。作者通过深入研究ALM音频生成的内在机制，并创建了一个专门用于检测的数据集Codecfake，以及提出了CSAM策略来提高检测模型的泛化能力和领域平衡。这些工作都是为了构建一个能够有效检测深度伪造音频的Agent，因此属于Agent分类。虽然涉及到了大型模型的应用，但重点在于检测策略和数据集的创建，而不是LLM的理论研究或应用开发，因此不属于LLM应用或LLM理论分类。同时，文中并未提及RAG（Retrieval-Augmented Generation）相关的技术或应用，因此也不属于RAG分类。` `深度伪造检测` `音频处理`

> The Codecfake Dataset and Countermeasures for the Universally Detection of Deepfake Audio

# 摘要

> 随着基于ALM的深度伪造音频的泛滥，我们急需有效的检测手段。传统的深度伪造音频生成过程繁琐，而ALM则通过神经编解码技术直接将离散代码转换为音频，其强大的鲁棒性和多功能性对现有的音频深度伪造检测模型构成了巨大挑战。为此，我们深入研究了ALM音频生成的内在机制，并创建了Codecfake数据集，这是一个包含多种语言和测试条件的大规模开源数据集，专为ALM音频检测设计。为了解决深度伪造音频的普遍检测问题，并克服原始SAM的领域偏差，我们提出了CSAM策略，旨在实现领域平衡和泛化。实验证明，采用CSAM策略在Codecfake和声码器数据集上联合训练的模型，其平均等错误率仅为0.616%，远优于基线模型。

> With the proliferation of Audio Language Model (ALM) based deepfake audio, there is an urgent need for effective detection methods. Unlike traditional deepfake audio generation, which often involves multi-step processes culminating in vocoder usage, ALM directly utilizes neural codec methods to decode discrete codes into audio. Moreover, driven by large-scale data, ALMs exhibit remarkable robustness and versatility, posing a significant challenge to current audio deepfake detection (ADD) models. To effectively detect ALM-based deepfake audio, we focus on the mechanism of the ALM-based audio generation method, the conversion from neural codec to waveform. We initially construct the Codecfake dataset, an open-source large-scale dataset, including two languages, millions of audio samples, and various test conditions, tailored for ALM-based audio detection. Additionally, to achieve universal detection of deepfake audio and tackle domain ascent bias issue of original SAM, we propose the CSAM strategy to learn a domain balanced and generalized minima. Experiment results demonstrate that co-training on Codecfake dataset and vocoded dataset with CSAM strategy yield the lowest average Equal Error Rate (EER) of 0.616% across all test conditions compared to baseline models.

[Arxiv](https://arxiv.org/abs/2405.04880)