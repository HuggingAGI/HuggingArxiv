# 增强检索音频深度伪造检测

发布时间：2024年04月22日

`分类：RAG

这篇论文讨论了深度伪造音频检测的问题，并提出了一种检索增强检测框架。它利用了检索增强生成（RAG）的概念，通过引入相似的检索样本来提升检测效果。这与RAG（Retrieval-Augmented Generation）的基本概念相符，即利用检索到的信息来辅助生成任务。因此，这篇论文应该归类为RAG。` `音频处理`

> Retrieval-Augmented Audio Deepfake Detection

# 摘要

> 随着文本到语音和声音转换技术的进步，我们能够制作出极其逼真的音频深度伪造，这引发了对其可能被滥用的日益关注。目前，大多数深度伪造检测方法主要依赖单一模型的模糊知识，这不仅限制了检测性能，也带来了透明度的挑战。借鉴检索增强生成的思路，我们提出了一种检索增强检测框架，通过引入相似的检索样本来提升检测效果。此外，我们还对多融合注意力分类器进行了扩展，以适应我们的新框架。大量实验证明，我们的框架在性能上超越了传统方法，并在2021年ASVspoof深度伪造数据集上取得了行业领先的成果，在2019年和2021年的LA数据集上也表现优异。深入分析样本后发现，检索器能够稳定地检索出与查询音频声学特征高度相似的同一说话人的样本，这显著提升了检测的准确性。

> With recent advances in speech synthesis including text-to-speech (TTS) and voice conversion (VC) systems enabling the generation of ultra-realistic audio deepfakes, there is growing concern about their potential misuse. However, most deepfake (DF) detection methods rely solely on the fuzzy knowledge learned by a single model, resulting in performance bottlenecks and transparency issues. Inspired by retrieval-augmented generation (RAG), we propose a retrieval-augmented detection (RAD) framework that augments test samples with similar retrieved samples for enhanced detection. We also extend the multi-fusion attentive classifier to integrate it with our proposed RAD framework. Extensive experiments show the superior performance of the proposed RAD framework over baseline methods, achieving state-of-the-art results on the ASVspoof 2021 DF set and competitive results on the 2019 and 2021 LA sets. Further sample analysis indicates that the retriever consistently retrieves samples mostly from the same speaker with acoustic characteristics highly consistent with the query audio, thereby improving detection performance.

![增强检索音频深度伪造检测](../../../paper_images/2404.13892/x1.png)

![增强检索音频深度伪造检测](../../../paper_images/2404.13892/x2.png)

![增强检索音频深度伪造检测](../../../paper_images/2404.13892/x3.png)

![增强检索音频深度伪造检测](../../../paper_images/2404.13892/x4.png)

![增强检索音频深度伪造检测](../../../paper_images/2404.13892/x5.png)

[Arxiv](https://arxiv.org/abs/2404.13892)