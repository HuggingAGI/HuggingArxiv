# 大型语言模型能否应对开放目标的立场检测挑战？

发布时间：2024年08月30日

`LLM应用` `社交媒体`

> Can Large Language Models Address Open-Target Stance Detection?

# 摘要

> 立场检测 (SD) 旨在判断文本对某一目标的态度，通常分为 "支持"、"反对" 或 "中立"。我们提出的开放目标立场检测 (OTSD) 方法，不依赖于训练时的目标信息，也不要求输入中包含目标。通过评估 GPT-3.5、Llama 3 和 Mistral 等大型语言模型 (LLM)，我们发现它们在目标生成方面优于依赖预定义目标的 TSE 方法，尤其是在目标明确提及的文本中。然而，在立场检测方面，LLM 在明确场景中表现出色，但在目标不明确提及的场景中则表现不佳。

> Stance detection (SD) assesses a text's position towards a target, typically labeled as "favor," "against," or "neutral." We introduce Open-Target Stance Detection (OTSD), where targets are neither seen during training nor provided as input. Evaluating Large Language Models (LLMs) like GPT-3.5, Llama 3, and Mistral, we compare their performance with the Target-Stance Extraction (TSE) approach, which has the advantage of using predefined targets. LLMs perform better than TSE in target generation when the real target is explicitly and not explicitly mentioned in the text. For stance detection, LLMs perform better in explicit scenarios but fail in non-explicit ones.

[Arxiv](https://arxiv.org/abs/2409.00222)