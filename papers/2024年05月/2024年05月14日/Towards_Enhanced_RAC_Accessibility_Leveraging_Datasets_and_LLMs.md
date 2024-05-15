# 迈向提升RAC可及性：借助数据集与大型语言模型之力在这篇文章中，我们将探讨如何通过整合数据集和大型语言模型（LLMs）来提高RAC（可能是某种技术或系统的缩写）的可访问性。我们将深入分析这些工具如何协同工作，以简化复杂任务的执行，并使更多人能够利用这些先进的技术。通过这种方式，我们不仅能够推动技术的普及，还能促进创新，让更多人受益于这些强大的资源。

发布时间：2024年05月14日

`LLM应用

这篇论文聚焦于将大型语言模型（LLMs）应用于哥伦比亚航空法规（RAC）的解释和普及，通过构建专门的数据集和微调LLMs来提高法规的可理解性和可访问性。这一应用展示了LLMs在特定领域内的实用价值，特别是在简化复杂技术文档和法规方面。因此，它属于LLM应用类别。` `航空法规` `法律技术`

> Towards Enhanced RAC Accessibility: Leveraging Datasets and LLMs

# 摘要

> 本文揭示了LLMs如何让哥伦比亚的航空法规（RAC）触手可及。面对RAC的复杂技术细节，我们创新性地简化了法规，使之更易理解。我们构建了首个RAC数据库，内含24,478个精心标注的问答对，并专为RAC应用微调了LLMs。文章详述了数据集的构建、专家标注和模型训练的方法。借助Gemma1.1 2b模型和Unsloth等尖端技术，我们优化了VRAM使用并引入了闪存注意力机制，以加速训练。这一创举为提升RAC的易懂性和可及性奠定了基石，有望助力新手，并减少对专家咨询的依赖，让航空业的法规导航更加顺畅。您可以访问数据集（https://huggingface.co/somosnlp/gemma-1.1-2b-it_ColombiaRAC_FullyCurated_format_chatML_V1）和模型（https://huggingface.co/datasets/somosnlp/ColombiaRAC_FullyCurated）了解更多信息。

> This paper explores the potential of large language models (LLMs) to make the Aeronautical Regulations of Colombia (RAC) more accessible. Given the complexity and extensive technicality of the RAC, this study introduces a novel approach to simplifying these regulations for broader understanding. By developing the first-ever RAC database, which contains 24,478 expertly labeled question-and-answer pairs, and fine-tuning LLMs specifically for RAC applications, the paper outlines the methodology for dataset assembly, expert-led annotation, and model training. Utilizing the Gemma1.1 2b model along with advanced techniques like Unsloth for efficient VRAM usage and flash attention mechanisms, the research aims to expedite training processes. This initiative establishes a foundation to enhance the comprehensibility and accessibility of RAC, potentially benefiting novices and reducing dependence on expert consultations for navigating the aviation industry's regulatory landscape.
  You can visit the dataset (https://huggingface.co/somosnlp/gemma-1.1-2b-it_ColombiaRAC_FullyCurated_format_chatML_V1) and the model (https://huggingface.co/datasets/somosnlp/ColombiaRAC_FullyCurated) here.

[Arxiv](https://arxiv.org/abs/2405.08792)