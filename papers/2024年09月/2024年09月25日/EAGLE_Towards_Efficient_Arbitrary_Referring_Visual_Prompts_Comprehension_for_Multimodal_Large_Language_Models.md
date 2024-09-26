# EAGLE：为多模态大型语言模型打造高效、精准的视觉提示理解工具

发布时间：2024年09月25日

`LLM应用` `人工智能` `计算机视觉`

> EAGLE: Towards Efficient Arbitrary Referring Visual Prompts Comprehension for Multimodal Large Language Models

# 摘要

> 近期，多模态大型语言模型（MLLM）因其强大的内容推理和指令跟随能力，成为研究热点。为了更有效地指导MLLM，除了传统语言表达，通过在图像上绘制物体来引用的“视觉提示”方法应运而生，因其能精准对齐用户意图与图像区域而广受欢迎。现有方法通过专用编码模块捕捉提示区域的语义，并通过微调适应MLLM，但存在架构冗余和泛化难题。为此，我们推出EAGLE，一种能在较少训练下理解任意视觉提示的MLLM。EAGLE保留提示的原始格式，将其嵌入为MLLM可理解的空间概念，并提出几何无关学习范式（GAL），进一步解耦区域理解与提示格式。实验证明，EAGLE在理解和泛化能力上表现优异。

> Recently, Multimodal Large Language Models (MLLMs) have sparked great research interests owing to their exceptional content-reasoning and instruction-following capabilities. To effectively instruct an MLLM, in addition to conventional language expressions, the practice of referring to objects by painting with brushes on images has emerged as a prevalent tool (referred to as "referring visual prompts") due to its efficacy in aligning the user's intention with specific image regions. To accommodate the most common referring visual prompts, namely points, boxes, and masks, existing approaches initially utilize specialized feature encoding modules to capture the semantics of the highlighted areas indicated by these prompts. Subsequently, these encoded region features are adapted to MLLMs through fine-tuning on a meticulously curated multimodal instruction dataset. However, such designs suffer from redundancy in architecture. Moreover, they face challenges in effectively generalizing when encountering a diverse range of arbitrary referring visual prompts in real-life scenarios. To address the above issues, we propose EAGLE, a novel MLLM that empowers comprehension of arbitrary referring visual prompts with less training efforts than existing approaches. Specifically, our EAGLE maintains the innate format of the referring visual prompts as colored patches rendered on the given image for conducting the instruction tuning. Our approach embeds referring visual prompts as spatial concepts conveying specific spatial areas comprehensible to the MLLM, with the semantic comprehension of these regions originating from the MLLM itself. Besides, we also propose a Geometry-Agnostic Learning paradigm (GAL) to further disentangle the MLLM's region-level comprehension with the specific formats of referring visual prompts. Extensive experiments are conducted to prove the effectiveness of our proposed method.

[Arxiv](https://arxiv.org/abs/2409.16723)