# 通过自我反思标记来增强多模态大型语言模型，以实现基于知识的视觉问答

发布时间：2024年11月25日

`LLM应用` `多模态` `视觉问答`

> Augmenting Multimodal LLMs with Self-Reflective Tokens for Knowledge-based Visual Question Answering

# 摘要

> 多模态大型语言模型（MLLMs）是大型语言模型处理多模态输入（融合文本与图像数据）的自然拓展。因其能应对涉及两种模态的复杂任务，近来备受关注。不过，其有效性局限于训练时获取的知识，限制了实际应用。在此项工作中，我们引入一种新方法，通过整合外部知识源增强 MLLMs 的适应性。我们提出的模型——反射型 LLaVA（ReflectiVA），借助反射标记动态判定对外部知识的需求，并预测从外部数据库检索的信息的相关性。标记依照两阶段双模型训练方案加以训练。这最终让 MLLM 能够管理外部知识，同时在无需外部知识的任务中保持流畅性和性能。通过我们的实验，我们展示了 ReflectiVA 在基于知识的视觉问答中的功效，凸显了其相较于现有方法的卓越性能。源代码和训练模型在 https://github.com/aimagelab/ReflectiVA 可公开获取。

> Multimodal LLMs (MLLMs) are the natural extension of large language models to handle multimodal inputs, combining text and image data. They have recently garnered attention due to their capability to address complex tasks involving both modalities. However, their effectiveness is limited to the knowledge acquired during training, which restricts their practical utility. In this work, we introduce a novel method to enhance the adaptability of MLLMs by integrating external knowledge sources. Our proposed model, Reflective LLaVA (ReflectiVA), utilizes reflective tokens to dynamically determine the need for external knowledge and predict the relevance of information retrieved from an external database. Tokens are trained following a two-stage two-model training recipe. This ultimately enables the MLLM to manage external knowledge while preserving fluency and performance on tasks where external knowledge is not needed. Through our experiments, we demonstrate the efficacy of ReflectiVA for knowledge-based visual question answering, highlighting its superior performance compared to existing methods. Source code and trained models are publicly available at https://github.com/aimagelab/ReflectiVA.

[Arxiv](https://arxiv.org/abs/2411.16863)