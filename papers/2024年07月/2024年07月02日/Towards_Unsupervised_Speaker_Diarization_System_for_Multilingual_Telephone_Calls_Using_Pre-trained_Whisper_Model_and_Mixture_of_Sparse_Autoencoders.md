# 本研究旨在构建一个无监督的多语言电话通话说话人日志系统，该系统结合了预训练的 Whisper 模型与稀疏自编码器的混合技术。

发布时间：2024年07月02日

`LLM应用` `语音识别`

> Towards Unsupervised Speaker Diarization System for Multilingual Telephone Calls Using Pre-trained Whisper Model and Mixture of Sparse Autoencoders

# 摘要

> 当前的说话人日志系统依赖于大量手动标注数据，这在实际应用中既耗时又困难。此外，语言特定的限制大大限制了这些系统在多语言环境中的应用。为此，我们提出了一种基于聚类的多语言电话说话人日志系统，该系统支持多种语言，无需大规模标注数据，通过多语言Whisper模型提取说话人特征，并采用创新的Mix-SAE网络架构进行无监督聚类。实验表明，Mix-SAE在效率上超越了其他自编码器聚类方法。我们的系统不仅在有限标注数据下展现出巨大潜力，还能有效融入复杂度低的多任务语音分析系统，涵盖语音转文本、语言识别和说话人日志等功能。

> Existing speaker diarization systems heavily rely on large amounts of manually annotated data, which is labor-intensive and challenging to collect in real-world scenarios. Additionally, the language-specific constraint in speaker diarization systems significantly hinders their applicability and scalability in multilingual settings. In this paper, we therefore propose a cluster-based speaker diarization system for multilingual telephone call applications. The proposed system supports multiple languages and does not require large-scale annotated data for the training process as leveraging the multilingual Whisper model to extract speaker embeddings and proposing a novel Mixture of Sparse Autoencoders (Mix-SAE) network architecture for unsupervised speaker clustering. Experimental results on the evaluating dataset derived from two-speaker subsets of CALLHOME and CALLFRIEND telephonic speech corpora demonstrate superior efficiency of the proposed Mix-SAE network to other autoencoder-based clustering methods. The overall performance of our proposed system also indicates the promising potential of our approach in developing unsupervised multilingual speaker diarization applications within the context of limited annotated data and enhancing the integration ability into comprehensive multi-task speech analysis systems (i.e. multiple tasks of speech-to-text, language detection, speaker diarization integrated in a low-complexity system).

[Arxiv](https://arxiv.org/abs/2407.01963)