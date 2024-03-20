# DetToolChain 是一项创新的提示策略，旨在充分发掘 MLLM 的检测潜能。

发布时间：2024年03月19日

`LLM应用` `计算机视觉` `零样本学习`

> DetToolChain: A New Prompting Paradigm to Unleash Detection Ability of MLLM

> 我们创新推出的DetToolChain，致力于解锁GPT-4V、Gemini等多模态大型语言模型在零样本目标检测领域的潜能。该方法结合了借鉴高精度检测先验的检测提示工具包，以及一种全新的逐层思考实施策略。工具包中的提示巧妙引导MLLM聚焦于区域细节、遵循测量规范解读坐标，并通过融合场景图等方式利用上下文信息进行推理。在此基础上，新型检测链式思考技术能智能化地将复杂任务拆解为多个简单子任务，对预测结果进行诊断，并制定逐步优化边界框的方案。实验证明，我们的框架在各类检测任务中表现出色，尤其在解决难题上。相较于当前最先进方法，装配DetToolChain的GPT-4V在开放词汇检测的MS COCO新类别集上提升AP50指标达+21.5%，在零样本参照表达理解的RefCOCO验证集上提升准确率+24.23%，在D-cube全面描述对象检测任务上提升平均精度+14.5%。

> We present DetToolChain, a novel prompting paradigm, to unleash the zero-shot object detection ability of multimodal large language models (MLLMs), such as GPT-4V and Gemini. Our approach consists of a detection prompting toolkit inspired by high-precision detection priors and a new Chain-of-Thought to implement these prompts. Specifically, the prompts in the toolkit are designed to guide the MLLM to focus on regional information (e.g., zooming in), read coordinates according to measure standards (e.g., overlaying rulers and compasses), and infer from the contextual information (e.g., overlaying scene graphs). Building upon these tools, the new detection chain-of-thought can automatically decompose the task into simple subtasks, diagnose the predictions, and plan for progressive box refinements. The effectiveness of our framework is demonstrated across a spectrum of detection tasks, especially hard cases. Compared to existing state-of-the-art methods, GPT-4V with our DetToolChain improves state-of-the-art object detectors by +21.5% AP50 on MS COCO Novel class set for open-vocabulary detection, +24.23% Acc on RefCOCO val set for zero-shot referring expression comprehension, +14.5% AP on D-cube describe object detection FULL setting.

![DetToolChain 是一项创新的提示策略，旨在充分发掘 MLLM 的检测潜能。](../../../paper_images/2403.12488/x1.png)

![DetToolChain 是一项创新的提示策略，旨在充分发掘 MLLM 的检测潜能。](../../../paper_images/2403.12488/x2.png)

![DetToolChain 是一项创新的提示策略，旨在充分发掘 MLLM 的检测潜能。](../../../paper_images/2403.12488/x3.png)

![DetToolChain 是一项创新的提示策略，旨在充分发掘 MLLM 的检测潜能。](../../../paper_images/2403.12488/x4.png)

![DetToolChain 是一项创新的提示策略，旨在充分发掘 MLLM 的检测潜能。](../../../paper_images/2403.12488/x5.png)

![DetToolChain 是一项创新的提示策略，旨在充分发掘 MLLM 的检测潜能。](../../../paper_images/2403.12488/x6.png)

![DetToolChain 是一项创新的提示策略，旨在充分发掘 MLLM 的检测潜能。](../../../paper_images/2403.12488/x7.png)

![DetToolChain 是一项创新的提示策略，旨在充分发掘 MLLM 的检测潜能。](../../../paper_images/2403.12488/x8.png)

[Arxiv](https://arxiv.org/abs/2403.12488)