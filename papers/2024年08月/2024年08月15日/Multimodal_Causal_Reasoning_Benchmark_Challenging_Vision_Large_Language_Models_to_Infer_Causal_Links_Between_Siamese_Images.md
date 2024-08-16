# 多模态因果推理基准：挑战大型视觉语言模型，推断暹罗图像间的因果联系

发布时间：2024年08月15日

`LLM应用` `人工智能` `计算机视觉`

> Multimodal Causal Reasoning Benchmark: Challenging Vision Large Language Models to Infer Causal Links Between Siamese Images

# 摘要

> 大型语言模型在文本信息中的因果推理能力卓越，但仅凭视觉线索时，视觉大型语言模型是否能保持这种简单直接的因果推理？为此，我们推出了多模态因果推理新基准 MuCR，旨在测试 VLLM 仅凭视觉线索（如动作、外观等）推断因果关系的能力。我们通过提示驱动的图像合成技术，生成包含语义因果的连体图像，有效评估 VLLM 的推理能力。同时，我们设计了多维评估指标，涵盖图像匹配、短语理解及句子解释，全面衡量 VLLM 的理解力。实验表明，当前顶尖 VLLM 在多模态因果推理上仍有提升空间。我们深入分析了其不足，并指出了未来研究方向。期待 MuCR 成为多模态因果推理领域的宝贵资源和基石。项目链接：https://github.com/Zhiyuan-Li-John/MuCR

> Large Language Models (LLMs) have showcased exceptional ability in causal reasoning from textual information. However, will these causalities remain straightforward for Vision Large Language Models (VLLMs) when only visual hints are provided? Motivated by this, we propose a novel Multimodal Causal Reasoning benchmark, namely MuCR, to challenge VLLMs to infer semantic cause-and-effect relationship when solely relying on visual cues such as action, appearance, clothing, and environment. Specifically, we introduce a prompt-driven image synthesis approach to create siamese images with embedded semantic causality and visual cues, which can effectively evaluate VLLMs' causal reasoning capabilities. Additionally, we develop tailored metrics from multiple perspectives, including image-level match, phrase-level understanding, and sentence-level explanation, to comprehensively assess VLLMs' comprehension abilities. Our extensive experiments reveal that the current state-of-the-art VLLMs are not as skilled at multimodal causal reasoning as we might have hoped. Furthermore, we perform a comprehensive analysis to understand these models' shortcomings from different views and suggest directions for future research. We hope MuCR can serve as a valuable resource and foundational benchmark in multimodal causal reasoning research. The project is available at: https://github.com/Zhiyuan-Li-John/MuCR

[Arxiv](https://arxiv.org/abs/2408.08105)