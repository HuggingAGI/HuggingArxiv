# 借助幻觉减少手动提示依赖，优化可提示分割过程

发布时间：2024年08月27日

`LLM应用` `计算机视觉` `人工智能`

> Leveraging Hallucinations to Reduce Manual Prompt Dependency in Promptable Segmentation

# 摘要

> 可提示分割通常依赖于实例特定的手动提示，以指导每个对象的分割。为了减少这种依赖，任务通用可提示分割应运而生，它通过单一任务通用提示处理不同对象的图像分割。目前，多模态大型语言模型（MLLMs）被用于从通用提示中推导出详细的实例特定提示，以提升分割精度。然而，MLLMs在推理时常出现幻觉，导致提示不准确。我们提出，合理利用这些幻觉可以揭示有价值的上下文信息，这些信息源自广泛的预训练知识。本文中，我们利用幻觉从图像中提取任务相关信息，并验证其准确性，以优化生成提示。我们设计了迭代提示-掩码循环生成框架（ProMaC），包含提示生成器和掩码生成器。提示生成器通过多尺度思维链提示，首先探索幻觉以提取图像的扩展上下文知识，然后精炼这些幻觉以形成精确的实例特定提示，进而指导掩码生成器通过掩码语义对齐生成与任务语义一致的掩码。生成的掩码进一步引导提示生成器聚焦于任务相关区域，减少无关幻觉，共同提升提示和掩码的质量。在五个基准测试中，ProMaC展现了其有效性。代码详见https://lwpyh.github.io/ProMaC/。

> Promptable segmentation typically requires instance-specific manual prompts to guide the segmentation of each desired object. To minimize such a need, task-generic promptable segmentation has been introduced, which employs a single task-generic prompt to segment various images of different objects in the same task. Current methods use Multimodal Large Language Models (MLLMs) to reason detailed instance-specific prompts from a task-generic prompt for improving segmentation accuracy. The effectiveness of this segmentation heavily depends on the precision of these derived prompts. However, MLLMs often suffer hallucinations during reasoning, resulting in inaccurate prompting. While existing methods focus on eliminating hallucinations to improve a model, we argue that MLLM hallucinations can reveal valuable contextual insights when leveraged correctly, as they represent pre-trained large-scale knowledge beyond individual images. In this paper, we utilize hallucinations to mine task-related information from images and verify its accuracy for enhancing precision of the generated prompts. Specifically, we introduce an iterative Prompt-Mask Cycle generation framework (ProMaC) with a prompt generator and a mask generator.The prompt generator uses a multi-scale chain of thought prompting, initially exploring hallucinations for extracting extended contextual knowledge on a test image.These hallucinations are then reduced to formulate precise instance-specific prompts, directing the mask generator to produce masks that are consistent with task semantics by mask semantic alignment. The generated masks iteratively induce the prompt generator to focus more on task-relevant image areas and reduce irrelevant hallucinations, resulting jointly in better prompts and masks. Experiments on 5 benchmarks demonstrate the effectiveness of ProMaC. Code given in https://lwpyh.github.io/ProMaC/.

[Arxiv](https://arxiv.org/abs/2408.15205)