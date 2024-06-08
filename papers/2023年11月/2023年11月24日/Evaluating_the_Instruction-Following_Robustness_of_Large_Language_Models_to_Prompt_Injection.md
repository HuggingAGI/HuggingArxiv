# 探究大型语言模型在面对提示注入时的指令遵循稳健性

发布时间：2023年11月24日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在面对提示注入攻击时的安全问题，并设立了基准来评估模型对这类攻击的抵抗力。研究关注的是LLMs在实际应用中的安全性能，特别是在遵循指令方面的风险和挑战。因此，这篇论文更符合LLM应用这一分类，因为它专注于LLMs在实际应用中的具体问题和解决方案，而不是理论研究或Agent的设计与应用。` `人工智能安全`

> Evaluating the Instruction-Following Robustness of Large Language Models to Prompt Injection

# 摘要

> 大型语言模型（LLMs）在遵循指令方面表现出色，逐渐成为多领域应用的关键。但这一优势也伴随着风险，如提示注入攻击，攻击者通过注入指令操控LLMs执行不当行为。为确保LLMs的安全应用，评估其对这类攻击的抵抗力至关重要。本研究设立了基准，旨在探究LLMs在面对注入指令时的影响程度及其区分注入与原始指令的能力。实验揭示，部分模型过于依赖提示中的指令，忽视整体上下文，而那些更擅长理解上下文和指令的模型则可能更易受攻击。这表明，我们应从单纯提升指令遵循能力转向全面提升对提示的理解和正确指令的辨识。我们希望通过深入分析，揭示这些漏洞的根源，为未来的安全改进提供方向。相关代码和数据已公开于https://github.com/Leezekun/instruction-following-robustness-eval。

> Large Language Models (LLMs) have demonstrated exceptional proficiency in instruction-following, becoming increasingly crucial across various applications. However, this capability brings with it the risk of prompt injection attacks, where attackers inject instructions into LLMs' input to elicit undesirable actions or content. Understanding the robustness of LLMs against such attacks is vital for their safe implementation. In this work, we establish a benchmark to evaluate the robustness of instruction-following LLMs against prompt injection attacks. Our objective is to determine the extent to which LLMs can be influenced by injected instructions and their ability to differentiate between these injected and original target instructions. Through extensive experiments with leading instruction-following LLMs, we uncover significant vulnerabilities in their robustness to such attacks. Our results indicate that some models are overly tuned to follow any embedded instructions in the prompt, overly focusing on the latter parts of the prompt without fully grasping the entire context. By contrast, models with a better grasp of the context and instruction-following capabilities will potentially be more susceptible to compromise by injected instructions. This underscores the need to shift the focus from merely enhancing LLMs' instruction-following capabilities to improving their overall comprehension of prompts and discernment of instructions that are appropriate to follow. We hope our in-depth analysis offers insights into the underlying causes of these vulnerabilities, aiding in the development of future solutions. Code and data are available at https://github.com/Leezekun/instruction-following-robustness-eval

[Arxiv](https://arxiv.org/abs/2308.10819)