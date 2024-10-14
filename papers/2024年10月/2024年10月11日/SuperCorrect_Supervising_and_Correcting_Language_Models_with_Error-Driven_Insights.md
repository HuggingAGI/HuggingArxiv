# SuperCorrect：借助错误驱动的洞察，监督并纠正语言模型

发布时间：2024年10月11日

`LLM应用` `人工智能`

> SuperCorrect: Supervising and Correcting Language Models with Error-Driven Insights

# 摘要

> 大型语言模型如GPT-4、PaLM和LLaMA在推理任务中表现出色，但小型模型如Llama-3-8B和DeepSeekMath-Base在复杂数学推理中仍显不足，主要因为它们难以识别和纠正推理错误。为此，我们推出了SuperCorrect，一个两阶段框架，利用大型教师模型指导和纠正小型学生模型的推理与反思过程。首先，我们提取教师模型的高级和详细思维模板，引导学生模型进行更精细的推理。接着，通过跨模型协作直接偏好优化（DPO），学生模型在训练中跟随教师模型的纠正轨迹，提升自我纠正能力。实验证明，SuperCorrect-7B在MATH/GSM8K基准测试中分别以显著优势超越了DeepSeekMath-7B和Qwen2.5-Math-7B，刷新了7B模型的SOTA记录。代码详见：https://github.com/YangLing0818/SuperCorrect-llm。

> Large language models (LLMs) like GPT-4, PaLM, and LLaMA have shown significant improvements in various reasoning tasks. However, smaller models such as Llama-3-8B and DeepSeekMath-Base still struggle with complex mathematical reasoning because they fail to effectively identify and correct reasoning errors. Recent reflection-based methods aim to address these issues by enabling self-reflection and self-correction, but they still face challenges in independently detecting errors in their reasoning steps. To overcome these limitations, we propose SuperCorrect, a novel two-stage framework that uses a large teacher model to supervise and correct both the reasoning and reflection processes of a smaller student model. In the first stage, we extract hierarchical high-level and detailed thought templates from the teacher model to guide the student model in eliciting more fine-grained reasoning thoughts. In the second stage, we introduce cross-model collaborative direct preference optimization (DPO) to enhance the self-correction abilities of the student model by following the teacher's correction traces during training. This cross-model DPO approach teaches the student model to effectively locate and resolve erroneous thoughts with error-driven insights from the teacher model, breaking the bottleneck of its thoughts and acquiring new skills and knowledge to tackle challenging problems. Extensive experiments consistently demonstrate our superiority over previous methods. Notably, our SuperCorrect-7B model significantly surpasses powerful DeepSeekMath-7B by 7.8%/5.3% and Qwen2.5-Math-7B by 15.1%/6.3% on MATH/GSM8K benchmarks, achieving new SOTA performance among all 7B models. Code: https://github.com/YangLing0818/SuperCorrect-llm

[Arxiv](https://arxiv.org/abs/2410.09008)