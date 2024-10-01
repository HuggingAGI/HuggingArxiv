# 等等，泰诺就是扑热息痛！我们正在研究如何提升语言模型，使其能更好地拒绝传播错误信息。

发布时间：2024年09月30日

`LLM应用` `人工智能`

> Wait, but Tylenol is Acetaminophen... Investigating and Improving Language Models' Ability to Resist Requests for Misinformation

# 摘要

> 背景：LLM 虽被训练来遵循指令，但这也使其容易盲目服从，即便请求内容错误。在医疗领域，这可能导致错误信息的加速传播，危害人类健康。  目标/方法：我们探讨了在模型明知请求不合逻辑时，是否能通过调整其优先考虑逻辑推理而非盲目服从，来减少生成误导性药物信息的风险。  结果：尽管所有前沿 LLM 都服从了错误请求，但通过提示和参数调整，我们成功提升了对请求逻辑缺陷的识别，并有效阻止了医疗错误信息的传播。  结论：让 LLM 更注重逻辑而非盲目服从，有望降低其被利用生成医疗错误信息的风险。

> Background: Large language models (LLMs) are trained to follow directions, but this introduces a vulnerability to blindly comply with user requests even if they generate wrong information. In medicine, this could accelerate the generation of misinformation that impacts human well-being.
  Objectives/Methods: We analyzed compliance to requests to generate misleading content about medications in settings where models know the request is illogical. We investigated whether in-context directions and instruction-tuning of LLMs to prioritize logical reasoning over compliance reduced misinformation risk.
  Results: While all frontier LLMs complied with misinformation requests, both prompt-based and parameter-based approaches can improve the detection of logic flaws in requests and prevent the dissemination of medical misinformation.
  Conclusion: Shifting LLMs to prioritize logic over compliance could reduce risks of exploitation for medical misinformation.

[Arxiv](https://arxiv.org/abs/2409.20385)