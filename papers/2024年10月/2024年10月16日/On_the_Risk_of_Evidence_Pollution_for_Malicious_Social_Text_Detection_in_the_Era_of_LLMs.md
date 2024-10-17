# 在 LLM 时代，恶意社交文本检测面临证据污染的风险。

发布时间：2024年10月16日

`LLM应用` `网络安全` `社交媒体`

> On the Risk of Evidence Pollution for Malicious Social Text Detection in the Era of LLMs

# 摘要

> 证据增强检测器在识别恶意社交文本方面表现出色，但大型语言模型 (LLM) 的兴起带来了证据污染的风险。本文探讨了如何通过操纵证据来模拟滥用场景，并提出了三种防御策略。实验表明，证据污染严重影响了现有检测器，而防御策略虽有效，但在实际应用中仍面临挑战。进一步分析揭示，高质量的污染证据不仅损害模型校准，还可能放大负面影响。

> Evidence-enhanced detectors present remarkable abilities in identifying malicious social text with related evidence. However, the rise of large language models (LLMs) brings potential risks of evidence pollution to confuse detectors. This paper explores how to manipulate evidence, simulating potential misuse scenarios including basic pollution, and rephrasing or generating evidence by LLMs. To mitigate its negative impact, we propose three defense strategies from both the data and model sides, including machine-generated text detection, a mixture of experts, and parameter updating. Extensive experiments on four malicious social text detection tasks with ten datasets present that evidence pollution, especially the generate strategy, significantly compromises existing detectors. On the other hand, the defense strategies could mitigate evidence pollution, but they faced limitations for practical employment, such as the need for annotated data and huge inference costs. Further analysis illustrates that polluted evidence is of high quality, would compromise the model calibration, and could ensemble to amplify the negative impact.

[Arxiv](https://arxiv.org/abs/2410.12600)