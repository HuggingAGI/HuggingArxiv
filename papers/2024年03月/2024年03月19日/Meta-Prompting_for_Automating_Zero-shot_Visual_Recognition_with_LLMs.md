# 本文探讨了如何利用大型语言模型（LLMs）通过元提示技术，实现零样本视觉识别任务的自动化，以期提高模型在未见类别上的识别能力。

发布时间：2024年03月19日

`分类：LLM应用` `视觉识别`

> Meta-Prompting for Automating Zero-shot Visual Recognition with LLMs

# 摘要

> 大型语言模型（LLM）生成的类别特定提示的集成化，已成为提升视觉-语言模型（VLM）零样本识别能力的有效手段。现行方法通过手工为LLM定制提示来生成VLM的下游任务提示，但这种方法不仅需要人工编写任务特定的提示，而且可能无法全面覆盖与目标类别相关的多样化视觉概念和任务风格。为了彻底实现零样本识别中提示生成过程的自动化，避免人工干预，我们提出了一种新方法——视觉识别的元提示（MPVR）。MPVR仅需目标任务的简短自然语言描述及其类别标签列表，便能自动产出一系列多样化的类别特定提示，构建出强大的零样本分类器。在多个流行的零样本图像识别基准测试中，MPVR展现出良好的泛化能力，这些测试覆盖了截然不同的领域。例如，MPVR在使用GPT和Mixtral LLM时，相较于CLIP在零样本识别上分别实现了最多19.8%和18.2%的提升（在20个数据集上平均提升了5.0%和4.5%）。

> Prompt ensembling of Large Language Model (LLM) generated category-specific prompts has emerged as an effective method to enhance zero-shot recognition ability of Vision-Language Models (VLMs). To obtain these category-specific prompts, the present methods rely on hand-crafting the prompts to the LLMs for generating VLM prompts for the downstream tasks. However, this requires manually composing these task-specific prompts and still, they might not cover the diverse set of visual concepts and task-specific styles associated with the categories of interest. To effectively take humans out of the loop and completely automate the prompt generation process for zero-shot recognition, we propose Meta-Prompting for Visual Recognition (MPVR). Taking as input only minimal information about the target task, in the form of its short natural language description, and a list of associated class labels, MPVR automatically produces a diverse set of category-specific prompts resulting in a strong zero-shot classifier. MPVR generalizes effectively across various popular zero-shot image recognition benchmarks belonging to widely different domains when tested with multiple LLMs and VLMs. For example, MPVR obtains a zero-shot recognition improvement over CLIP by up to 19.8% and 18.2% (5.0% and 4.5% on average over 20 datasets) leveraging GPT and Mixtral LLMs, respectively

![本文探讨了如何利用大型语言模型（LLMs）通过元提示技术，实现零样本视觉识别任务的自动化，以期提高模型在未见类别上的识别能力。](../../../paper_images/2403.11755/x1.png)

![本文探讨了如何利用大型语言模型（LLMs）通过元提示技术，实现零样本视觉识别任务的自动化，以期提高模型在未见类别上的识别能力。](../../../paper_images/2403.11755/x2.png)

![本文探讨了如何利用大型语言模型（LLMs）通过元提示技术，实现零样本视觉识别任务的自动化，以期提高模型在未见类别上的识别能力。](../../../paper_images/2403.11755/x3.png)

![本文探讨了如何利用大型语言模型（LLMs）通过元提示技术，实现零样本视觉识别任务的自动化，以期提高模型在未见类别上的识别能力。](../../../paper_images/2403.11755/x4.png)

![本文探讨了如何利用大型语言模型（LLMs）通过元提示技术，实现零样本视觉识别任务的自动化，以期提高模型在未见类别上的识别能力。](../../../paper_images/2403.11755/x5.png)

![本文探讨了如何利用大型语言模型（LLMs）通过元提示技术，实现零样本视觉识别任务的自动化，以期提高模型在未见类别上的识别能力。](../../../paper_images/2403.11755/x6.png)

[Arxiv](https://arxiv.org/abs/2403.11755)