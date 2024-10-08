# ActiView：探索多模态大型语言模型的主动感知能力

发布时间：2024年10月06日

`LLM应用` `人工智能` `计算机视觉`

> ActiView: Evaluating Active Perception Ability for Multimodal Large Language Models

# 摘要

> 主动感知是人类的一项关键能力，涉及根据环境理解设定目标并采取行动实现目标。尽管在评估多模态大型语言模型（MLLM）方面投入巨大，但主动感知仍被忽视。为此，我们推出了名为 ActiView 的新基准，专门用于评估 MLLM 的主动感知能力。鉴于全面评估主动感知难度大，我们聚焦于一种特殊的视觉问答（VQA）形式，既简化评估又对现有 MLLM 构成挑战。在给定图像的情况下，我们限制模型的感知范围，要求其根据推理主动调整感知范围以正确回答问题。通过对 27 个模型（包括专有和开源模型）的广泛测试，我们发现同时处理多张图像的能力对实现主动感知至关重要。结果表明，MLLM 在主动感知方面存在显著不足，凸显了该领域的重要性。我们期望 ActiView 能助力开发更自然、全面理解多模态输入的方法。

> Active perception, a crucial human capability, involves setting a goal based on the current understanding of the environment and performing actions to achieve that goal. Despite significant efforts in evaluating Multimodal Large Language Models (MLLMs), active perception has been largely overlooked. To address this gap, we propose a novel benchmark named ActiView to evaluate active perception in MLLMs. Since comprehensively assessing active perception is challenging, we focus on a specialized form of Visual Question Answering (VQA) that eases the evaluation yet challenging for existing MLLMs. Given an image, we restrict the perceptual field of a model, requiring it to actively zoom or shift its perceptual field based on reasoning to answer the question successfully. We conduct extensive evaluation over 27 models, including proprietary and open-source models, and observe that the ability to read and comprehend multiple images simultaneously plays a significant role in enabling active perception. Results reveal a significant gap in the active perception capability of MLLMs, indicating that this area deserves more attention. We hope that our benchmark could help develop methods for MLLMs to understand multimodal inputs in more natural and holistic ways.

[Arxiv](https://arxiv.org/abs/2410.04659)