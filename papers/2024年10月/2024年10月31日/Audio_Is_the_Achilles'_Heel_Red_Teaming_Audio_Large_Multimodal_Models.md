# 音频乃阿喀琉斯之踵：针对音频大型多模态模型展开红队测试

发布时间：2024年10月31日

`LLM应用` `多模态模型`

> Audio Is the Achilles' Heel: Red Teaming Audio Large Multimodal Models

# 摘要

> 大型多模态模型（LMMs）把大型语言模型（LLMs）和模态编码器加以结合，将多模态信息（视觉和听觉）与文本相匹配，已展现出在现实环境中与人类交互的能力。不过，这类模型带来了新的安全挑战，即那些在文本方面安全对齐的模型，对于多模态输入是否也能有一致的保障。尽管近期针对视觉 LMMs 有安全对齐的研究，但音频 LMMs 的安全性仍有待深入探索。在这项工作中，我们从三个方面全面考察了五个先进音频 LMMs 的安全性：（i）音频和文本格式的有害问题；（ii）伴有分散注意力的非语音音频的文本格式有害问题；（iii）特定于语音的越狱。在这些情况下，我们的结果显示，开源音频 LMMs 对有害音频问题的平均攻击成功率达 69.14％，并且在受到非语音音频噪声干扰时存在安全漏洞。我们对 Gemini-1.5-Pro 进行的特定语音越狱，在有害查询基准上的攻击成功率为 70.67％。我们给出了可能导致这些所报告的安全不一致情况的见解。警告：本文包含冒犯性示例。

> Large Multimodal Models (LMMs) have demonstrated the ability to interact with humans under real-world conditions by combining Large Language Models (LLMs) and modality encoders to align multimodal information (visual and auditory) with text. However, such models raise new safety challenges of whether models that are safety-aligned on text also exhibit consistent safeguards for multimodal inputs. Despite recent safety-alignment research on vision LMMs, the safety of audio LMMs remains under-explored. In this work, we comprehensively red team the safety of five advanced audio LMMs under three settings: (i) harmful questions in both audio and text formats, (ii) harmful questions in text format accompanied by distracting non-speech audio, and (iii) speech-specific jailbreaks. Our results under these settings demonstrate that open-source audio LMMs suffer an average attack success rate of 69.14% on harmful audio questions, and exhibit safety vulnerabilities when distracted with non-speech audio noise. Our speech-specific jailbreaks on Gemini-1.5-Pro achieve an attack success rate of 70.67% on the harmful query benchmark. We provide insights on what could cause these reported safety-misalignments. Warning: this paper contains offensive examples.

[Arxiv](https://arxiv.org/abs/2410.23861)