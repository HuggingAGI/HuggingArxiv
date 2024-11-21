# 对用于医学视觉基础的医学多模态大型语言模型进行参数高效微调

发布时间：2024年10月31日

`LLM应用` `多模态`

> Parameter-Efficient Fine-Tuning Medical Multimodal Large Language Models for Medical Visual Grounding

# 摘要

> 多模态大型语言模型（MLLMs）继承了大型语言模型（LLMs）出色的文本理解能力，并将其拓展至多模态场景，在多模态任务的通用领域成果斐然。但在医学领域，高昂的训练成本以及对海量医学数据的需求，给医学 MLLMs 的发展造成阻碍。而且，由于答案是自由文本形式，像视觉基础这类需要按规定形式输出的任务，对 MLLMs 来说颇具难度。迄今为止，医学视觉基础领域尚无医学 MLLMs 的相关成果。针对医学视觉基础任务，也就是依据短文本描述来识别医学图像中的位置，我们提出了用于医学视觉基础的参数高效微调医学多模态大型语言模型（PFMVG）。为验证该模型的性能，我们在医学视觉基础的公共基准数据集上进行评估，其结果颇具竞争力，且显著优于 GPT-4v。我们的代码将在同行评审后开源。

> Multimodal Large Language Models (MLLMs) inherit the superior text understanding capabilities of LLMs and extend these capabilities to multimodal scenarios. These models achieve excellent results in the general domain of multimodal tasks. However, in the medical domain, the substantial training costs and the requirement for extensive medical data pose challenges to the development of medical MLLMs. Furthermore, due to the free-text form of answers, tasks such as visual grounding that need to produce output in a prescribed form become difficult for MLLMs. So far, there have been no medical MLLMs works in medical visual grounding area. For the medical vision grounding task, which involves identifying locations in medical images based on short text descriptions, we propose Parameter-efficient Fine-tuning medical multimodal large language models for Medcial Visual Grounding (PFMVG). To validate the performance of the model, we evaluate it on a public benchmark dataset for medical visual grounding, where it achieves competitive results, and significantly outperforming GPT-4v. Our code will be open sourced after peer review.

[Arxiv](https://arxiv.org/abs/2410.23822)