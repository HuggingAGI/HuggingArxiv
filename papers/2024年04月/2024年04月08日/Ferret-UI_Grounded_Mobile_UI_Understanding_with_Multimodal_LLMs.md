# Ferret-UI 利用多模态大型语言模型，实现对移动用户界面的深入理解。

发布时间：2024年04月08日

`LLM应用` `用户界面` `移动应用`

> Ferret-UI: Grounded Mobile UI Understanding with Multimodal LLMs

# 摘要

> 近期多模态大型语言模型（MLLMs）的发展引人注目，但这些模型在理解用户界面（UI）屏幕并进行有效互动方面仍有不足。本文介绍了Ferret-UI，一款专为提升移动UI屏幕理解能力而设计的新型MLLM，它具备强大的参考、定位和推理功能。考虑到UI屏幕通常具有更长的长宽比和更小的关键元素（如图标、文本），我们在Ferret的基础上引入了“任意分辨率”功能，以便放大细节并利用更丰富的视觉特性。具体做法是，根据屏幕的原始长宽比将其分割为两个子图像（纵向屏幕为垂直分割，横向屏幕为水平分割），并对这两个子图像进行独立编码后送入LLMs处理。我们从众多基础UI任务中精心搜集训练样本，例如图标识别、文本查找和控件列表等，并为这些样本添加区域注释，以便更好地进行精确指示和定位。为了提升模型的推理能力，我们还编制了一个包含复杂任务的数据集，如详细描述、感知/交互对话和功能推断。经过针对性训练，Ferret-UI不仅在理解UI屏幕上表现出色，还能执行开放式指令。在模型评估方面，我们构建了一个全面基准测试，涵盖了所有相关任务。Ferret-UI的表现不仅超越了大多数开源UI MLLMs，还在所有基础UI任务上都超过了GPT-4V。

> Recent advancements in multimodal large language models (MLLMs) have been noteworthy, yet, these general-domain MLLMs often fall short in their ability to comprehend and interact effectively with user interface (UI) screens. In this paper, we present Ferret-UI, a new MLLM tailored for enhanced understanding of mobile UI screens, equipped with referring, grounding, and reasoning capabilities. Given that UI screens typically exhibit a more elongated aspect ratio and contain smaller objects of interest (e.g., icons, texts) than natural images, we incorporate "any resolution" on top of Ferret to magnify details and leverage enhanced visual features. Specifically, each screen is divided into 2 sub-images based on the original aspect ratio (i.e., horizontal division for portrait screens and vertical division for landscape screens). Both sub-images are encoded separately before being sent to LLMs. We meticulously gather training samples from an extensive range of elementary UI tasks, such as icon recognition, find text, and widget listing. These samples are formatted for instruction-following with region annotations to facilitate precise referring and grounding. To augment the model's reasoning ability, we further compile a dataset for advanced tasks, including detailed description, perception/interaction conversations, and function inference. After training on the curated datasets, Ferret-UI exhibits outstanding comprehension of UI screens and the capability to execute open-ended instructions. For model evaluation, we establish a comprehensive benchmark encompassing all the aforementioned tasks. Ferret-UI excels not only beyond most open-source UI MLLMs, but also surpasses GPT-4V on all the elementary UI tasks.

[Arxiv](https://arxiv.org/abs/2404.05719)