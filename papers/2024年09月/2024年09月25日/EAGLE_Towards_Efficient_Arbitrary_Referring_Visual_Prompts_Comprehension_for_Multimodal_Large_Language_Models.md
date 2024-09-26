# EAGLE：为多模态大型语言模型打造高效、灵活的视觉提示理解工具

发布时间：2024年09月25日

`LLM应用` `人工智能` `计算机视觉`

> EAGLE: Towards Efficient Arbitrary Referring Visual Prompts Comprehension for Multimodal Large Language Models

# 摘要

> 多模态大型语言模型 (MLLM) 因其强大的内容推理和指令跟随能力，近期备受瞩目。为了更好地指导 MLLM，除了传统语言表达，通过在图像上绘制来引用物体的方法（即“引用视觉提示”）因其高效性而流行。现有方法通过专用编码模块捕捉提示区域的语义，并微调多模态数据集以适应 MLLM。然而，这种设计存在冗余，且在处理多样化的实际场景时泛化能力有限。为此，我们提出 EAGLE，一种能在较少训练下理解任意视觉提示的 MLLM。EAGLE 将提示作为彩色补丁保留在图像上，并将其嵌入为空间概念，由 MLLM 自身理解其语义。此外，我们还引入几何无关学习范式 (GAL)，进一步解耦区域理解与提示格式。实验证明，我们的方法高效且有效。

> Recently, Multimodal Large Language Models (MLLMs) have sparked great research interests owing to their exceptional content-reasoning and instruction-following capabilities. To effectively instruct an MLLM, in addition to conventional language expressions, the practice of referring to objects by painting with brushes on images has emerged as a prevalent tool (referred to as "referring visual prompts") due to its efficacy in aligning the user's intention with specific image regions. To accommodate the most common referring visual prompts, namely points, boxes, and masks, existing approaches initially utilize specialized feature encoding modules to capture the semantics of the highlighted areas indicated by these prompts. Subsequently, these encoded region features are adapted to MLLMs through fine-tuning on a meticulously curated multimodal instruction dataset. However, such designs suffer from redundancy in architecture. Moreover, they face challenges in effectively generalizing when encountering a diverse range of arbitrary referring visual prompts in real-life scenarios. To address the above issues, we propose EAGLE, a novel MLLM that empowers comprehension of arbitrary referring visual prompts with less training efforts than existing approaches. Specifically, our EAGLE maintains the innate format of the referring visual prompts as colored patches rendered on the given image for conducting the instruction tuning. Our approach embeds referring visual prompts as spatial concepts conveying specific spatial areas comprehensible to the MLLM, with the semantic comprehension of these regions originating from the MLLM itself. Besides, we also propose a Geometry-Agnostic Learning paradigm (GAL) to further disentangle the MLLM's region-level comprehension with the specific formats of referring visual prompts. Extensive experiments are conducted to prove the effectiveness of our proposed method.

[Arxiv](https://arxiv.org/abs/2409.16723)