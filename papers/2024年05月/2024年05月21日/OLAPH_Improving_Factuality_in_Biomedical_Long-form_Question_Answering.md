# OLAPH：提升生物医学长篇问答的事实性

发布时间：2024年05月21日

`LLM应用

理由：这篇论文主要关注的是在医学领域中，如何通过特定的数据集和训练框架（MedLFQA和OLAPH）来提升大型语言模型（LLMs）的事实性，特别是在生成详尽内容和解答患者疑问时的应用。这涉及到具体的应用场景和解决方案，而不是理论研究或Agent的设计，因此最合适的分类是LLM应用。` `问答系统`

> OLAPH: Improving Factuality in Biomedical Long-form Question Answering

# 摘要

> 在医学领域，大型语言模型（LLMs）需具备生成详尽内容的能力，尤其是在解答患者疑问时，模型的回答必须基于事实。为此，我们开发了MedLFQA，一个专为生物医学领域定制的长篇问答基准数据集，用以自动评估事实性。同时，我们提出了OLAPH框架，这是一个创新的解决方案，通过自动评估提升事实性。OLAPH通过迭代训练LLMs，利用采样预测和偏好优化减少幻觉，即不断优化模型以匹配更事实性的回答。实验表明，即便在未用于训练的评估指标上，采用OLAPH训练的LLMs在事实性上均有显著提升。我们的7B LLM模型，经OLAPH训练后，在事实性上能与医学专家的回答媲美。我们相信，这项研究将为评估医学领域LLMs的长文本生成能力提供新的视角。相关代码和数据集已公开于https://github.com/dmis-lab/OLAPH。

> In the medical domain, numerous scenarios necessitate the long-form generation ability of large language models (LLMs). Specifically, when addressing patients' questions, it is essential that the model's response conveys factual claims, highlighting the need for an automated method to evaluate those claims. Thus, we introduce MedLFQA, a benchmark dataset reconstructed using long-form question-answering datasets related to the biomedical domain. We use MedLFQA to facilitate the automatic evaluations of factuality. We also propose OLAPH, a simple and novel framework that enables the improvement of factuality through automatic evaluations. The OLAPH framework iteratively trains LLMs to mitigate hallucinations using sampling predictions and preference optimization. In other words, we iteratively set the highest-scoring response as a preferred response derived from sampling predictions and train LLMs to align with the preferred response that improves factuality. We highlight that, even on evaluation metrics not used during training, LLMs trained with our OLAPH framework demonstrate significant performance improvement in factuality. Our findings reveal that a 7B LLM trained with our OLAPH framework can provide long answers comparable to the medical experts' answers in terms of factuality. We believe that our work could shed light on gauging the long-text generation ability of LLMs in the medical domain. Our code and datasets are available at https://github.com/dmis-lab/OLAPH}{https://github.com/dmis-lab/OLAPH.

[Arxiv](https://arxiv.org/abs/2405.12701)