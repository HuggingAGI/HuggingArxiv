# 在大型语言模型中，采用潜在距离引导的对齐训练方法。

发布时间：2024年04月09日

`LLM理论` `人工智能`

> Latent Distance Guided Alignment Training for Large Language Models

# 摘要

> 大型语言模型（LLMs）需与人类偏好保持一致，这是其核心特性。目前主流的一致性方法RLHF和DPO，虽有效却因需大量人工注释而成本高昂。为了减轻这一负担，研究人员致力于开发无需人工注释的一致性训练新方法。我们提出了一种名为潜在距离引导对齐训练（LD-Align）的新方法，旨在通过潜在空间的样本重建来实现模型与高质量数据集的对齐，类似于自动编码过程。我们利用潜在空间中样本对的距离来进行DPO基础的对齐训练。经过大量实验和评估验证，LD-Align在提升一致性方面表现出色。

> Ensuring alignment with human preferences is a crucial characteristic of large language models (LLMs). Presently, the primary alignment methods, RLHF and DPO, require extensive human annotation, which is expensive despite their efficacy. The significant expenses associated with current alignment techniques motivate researchers to investigate the development of annotation-free alignment training methods. In pursuit of improved alignment without relying on external annotation, we introduce Latent Distance Guided Alignment Training (LD-Align). This approach seeks to align the model with a high-quality supervised fine-tune dataset using guidance from a latent space. The latent space is generated through sample reconstruction, akin to auto-encoding. Consequently, we utilize the distance between sample pairs in the latent space to guide DPO-based alignment training. Extensive experimentation and evaluation show the efficacy of our proposed method in achieving notable alignment.

[Arxiv](https://arxiv.org/abs/2404.06390)