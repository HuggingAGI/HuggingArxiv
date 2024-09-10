# 构建鲁棒知识密集型问答模型：大型语言模型的探索之路

发布时间：2024年09月09日

`RAG` `问答系统` `人工智能`

> Towards Building a Robust Knowledge Intensive Question Answering Model with Large Language Models

# 摘要

> 随着LLM的发展，问答系统的智能和流畅性得到了显著提升，而检索增强技术的引入则让模型更有效地利用外部信息。然而，检索信息中的噪声和错误却对模型的鲁棒性构成了挑战。为此，我们首先构建了一个模拟多种干扰场景的数据集，包括关键信息缺失、噪声和冲突。为应对噪声导致的准确性下降，我们提出了一种基于数据增强的微调方法，以提升LLM的抗噪能力。同时，对比学习方法也被引入，以保持模型对外部信息的辨别力。实验结果显示，我们的方法不仅增强了模型的鲁棒性，还提升了其对外部信息的辨别能力。

> The development of LLMs has greatly enhanced the intelligence and fluency of question answering, while the emergence of retrieval enhancement has enabled models to better utilize external information. However, the presence of noise and errors in retrieved information poses challenges to the robustness of LLMs. In this work, to evaluate the model's performance under multiple interferences, we first construct a dataset based on machine reading comprehension datasets simulating various scenarios, including critical information absence, noise, and conflicts. To address the issue of model accuracy decline caused by noisy external information, we propose a data augmentation-based fine-tuning method to enhance LLM's robustness against noise. Additionally, contrastive learning approach is utilized to preserve the model's discrimination capability of external information. We have conducted experiments on both existing LLMs and our approach, the results are evaluated by GPT-4, which indicates that our proposed methods improve model robustness while strengthening the model's discrimination capability.

[Arxiv](https://arxiv.org/abs/2409.05385)