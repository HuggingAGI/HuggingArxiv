# FullAnno：一款专为提升 MLLMs 图像理解能力而设计的数据引擎

发布时间：2024年09月20日

`LLM应用` `计算机视觉` `数据标注`

> FullAnno: A Data Engine for Enhancing Image Comprehension of MLLMs

# 摘要

> 多模态大型语言模型 (MLLM) 在视觉语言任务中表现出色，但依赖于高质量的监督微调数据。现有方法通过 GPT-4V 筛选数据，但受限于其商业性和简单提示。为此，我们开发了 FullAnno 系统，一个能生成大规模、高质量图像注释的数据引擎，涵盖对象类别、位置、区域描述、文本信息及密集字幕。通过多专家模型和丰富提示，FullAnno 实现了级联注释过程。我们重新注释了 COCO 和 Visual Genome 数据集，对象注释增至三倍，字幕长度提升 15 倍。实验证明，这显著提升了 LLaVA-v1.5 的性能。重新注释的数据可访问：https://arcana-project-page.github.io

> Multimodal Large Language Models (MLLMs) have shown promise in a broad range of vision-language tasks with their strong reasoning and generalization capabilities. However, they heavily depend on high-quality data in the Supervised Fine-Tuning (SFT) phase. The existing approaches aim to curate high-quality data via GPT-4V, but they are not scalable due to the commercial nature of GPT-4V and the simplicity of the prompts used to instruct the model. To this end, we devised the FullAnno system, which is a data engine that can generate large-scale, high-quality, and fine-grained image annotations consisting of the category and position of objects, region descriptions, text information, as well as image dense captions. This engine is characterized by its cascade annotation process, which involves multiple expert models and employs rich prompts to instruct LLMs in generating dense image captions. We re-annotated the COCO and Visual Genome datasets using our FullAnno system, tripling the number of object annotations and increasing the length of the original image captions by a factor of 15. Experiments show that the regenerated annotation can significantly enhance the capabilities of LLaVA-v1.5 on several benchmarks. The re-annotated data are available at: https://arcana-project-page.github.io

[Arxiv](https://arxiv.org/abs/2409.13540)