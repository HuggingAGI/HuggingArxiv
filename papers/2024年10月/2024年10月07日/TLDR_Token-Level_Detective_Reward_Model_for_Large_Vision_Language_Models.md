# TLDR: 大型视觉语言模型的令牌级侦探奖励模型

发布时间：2024年10月07日

`LLM应用` `人工智能` `计算机视觉`

> TLDR: Token-Level Detective Reward Model for Large Vision Language Models

# 摘要

> 尽管奖励模型在提升多模态大型语言模型方面表现出色，但其自身仍显粗糙，信息量有限。现有模型仅通过单一的二进制反馈模仿人类注释，忽略了文本长度。在处理图像与文本的多模态模型中，简单奖励模型可能对文本产生隐性偏见，影响图像处理。为此，我们提出了 $\textbf{TLDR}$ 模型，为每个文本标记提供细致注释。通过基于扰动的方法生成合成硬负样本及其标记级标签，训练 TLDR 模型。TLDR 不仅助力现成模型自我修正，还作为幻觉评估工具。最终，TLDR 模型能将人类注释速度提升三倍，获取更丰富的高质量视觉语言数据。

> Although reward models have been successful in improving multimodal large language models, the reward models themselves remain brutal and contain minimal information. Notably, existing reward models only mimic human annotations by assigning only one binary feedback to any text, no matter how long the text is. In the realm of multimodal language models, where models are required to process both images and texts, a naive reward model may learn implicit biases toward texts and become less grounded in images. In this paper, we propose a $\textbf{T}$oken-$\textbf{L}$evel $\textbf{D}$etective $\textbf{R}$eward Model ($\textbf{TLDR}$) to provide fine-grained annotations to each text token. We first introduce a perturbation-based method to generate synthetic hard negatives and their token-level labels to train TLDR models. Then we show the rich usefulness of TLDR models both in assisting off-the-shelf models to self-correct their generations, and in serving as a hallucination evaluation tool. Finally, we show that TLDR models can significantly speed up human annotation by 3 times to acquire a broader range of high-quality vision language data.

[Arxiv](https://arxiv.org/abs/2410.04734)