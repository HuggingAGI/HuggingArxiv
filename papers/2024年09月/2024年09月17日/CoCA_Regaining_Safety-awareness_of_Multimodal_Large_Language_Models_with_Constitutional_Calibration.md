# CoCA：借助宪法校准，重塑多模态大型语言模型的安全意识

发布时间：2024年09月17日

`LLM应用` `人工智能` `网络安全`

> CoCA: Regaining Safety-awareness of Multimodal Large Language Models with Constitutional Calibration

# 摘要

> 多模态大型语言模型 (MLLM) 在处理视觉输入的对话中表现出色，这归功于大型语言模型 (LLM) 的强大能力。然而，视觉模态的整合也带来了新的风险：MLLM 容易受到恶意视觉输入的影响，并可能生成敏感或有害的响应。本文首先探讨了 MLLM 是否具备对恶意图像输入的安全意识。实验表明，通过在输入中添加安全要求，MLLM 的安全意识显著提升，这表明其安全意识被模态差距所削弱。接着，我们提出了一种名为 CoCA 的技术，通过校准输出分布来增强 MLLM 的安全意识，使其在不损失原有能力的情况下恢复安全性能。我们在多模态安全和理解基准上验证了这一策略的有效性。

> The deployment of multimodal large language models (MLLMs) has demonstrated remarkable success in engaging in conversations involving visual inputs, thanks to the superior power of large language models (LLMs). Those MLLMs are typically built based on the LLMs, with an image encoder to process images into the token embedding space of the LLMs. However, the integration of visual modality has introduced a unique vulnerability: the MLLM becomes susceptible to malicious visual inputs and prone to generating sensitive or harmful responses, even though the LLM has been trained on textual dataset to align with human value. In this paper, we first raise the question: ``Do the MLLMs possess safety-awareness against malicious image inputs?". We find that after adding a principle that specifies the safety requirement into the input of the MLLM, the model's safety awareness becomes boosted. This phenomenon verifies the existence of MLLM's safety-awareness against image inputs, it is only weakened by the modality gap. We then introduce a simple yet effective technique termed CoCA, which amplifies the safety-awareness of the MLLM by calibrating its output distribution. Our proposed strategy helps the model reclaim its original safety awareness without losing its original capabilities. We verify the effectiveness of our approach on both multimodal safety and understanding benchmarks.

[Arxiv](https://arxiv.org/abs/2409.11365)