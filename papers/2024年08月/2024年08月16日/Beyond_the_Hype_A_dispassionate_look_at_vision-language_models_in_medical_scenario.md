# 冷静看待医疗场景中的视觉-语言模型，超越炒作的表象。

发布时间：2024年08月16日

`LLM应用` `人工智能`

> Beyond the Hype: A dispassionate look at vision-language models in medical scenario

# 摘要

> 近期，大型视觉语言模型 (LVLMs) 在多任务中的出色表现引起了 AI 界的广泛关注。但在医学等专业领域，其性能和可靠性尚未得到充分验证。当前评估多聚焦于基于多模态数据的简单视觉问答 (VQA)，忽略了 LVLMs 的深层特性。为此，我们推出了 RadVUQA，一个创新的放射学视觉理解与问答基准，旨在全面评估现有 LVLMs。RadVUQA 从五个维度进行验证：解剖学理解、多模态理解、定量与空间推理、生理学知识及鲁棒性。结果显示，无论是通用还是医学专用的 LVLMs，在多模态理解和定量推理方面均存在显著不足。这凸显了现有模型与临床需求间的巨大鸿沟，迫切需要开发更强大、更智能的 LVLMs。相关代码和数据集将在论文获批后公开。

> Recent advancements in Large Vision-Language Models (LVLMs) have demonstrated remarkable capabilities across diverse tasks, garnering significant attention in AI communities. However, their performance and reliability in specialized domains such as medicine remain insufficiently assessed. In particular, most assessments over-concentrate in evaluating VLMs based on simple Visual Question Answering (VQA) on multi-modality data, while ignoring the in-depth characteristic of LVLMs. In this study, we introduce RadVUQA, a novel Radiological Visual Understanding and Question Answering benchmark, to comprehensively evaluate existing LVLMs. RadVUQA mainly validates LVLMs across five dimensions: 1) Anatomical understanding, assessing the models' ability to visually identify biological structures; 2) Multimodal comprehension, which involves the capability of interpreting linguistic and visual instructions to produce desired outcomes; 3) Quantitative and spatial reasoning, evaluating the models' spatial awareness and proficiency in combining quantitative analysis with visual and linguistic information; 4) Physiological knowledge, measuring the models' capability to comprehend functions and mechanisms of organs and systems; and 5) Robustness, which assesses the models' capabilities against unharmonised and synthetic data. The results indicate that both generalized LVLMs and medical-specific LVLMs have critical deficiencies with weak multimodal comprehension and quantitative reasoning capabilities. Our findings reveal the large gap between existing LVLMs and clinicians, highlighting the urgent need for more robust and intelligent LVLMs. The code and dataset will be available after the acceptance of this paper.

[Arxiv](https://arxiv.org/abs/2408.08704)