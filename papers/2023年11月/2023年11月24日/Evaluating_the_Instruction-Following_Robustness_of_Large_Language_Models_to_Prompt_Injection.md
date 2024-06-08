# 探究大型语言模型在面对提示注入时的指令遵循稳定性

发布时间：2023年11月24日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在面对提示注入攻击时的脆弱性，并建立了一个基准来评估这些模型对这类攻击的抵抗力。研究关注的是LLMs在实际应用中的安全问题，特别是如何区分和处理注入的指令，这直接关联到LLMs在实际应用中的表现和安全性。因此，这篇论文的内容更符合LLM应用这一分类，因为它专注于LLMs在特定应用场景下的性能和安全问题。` `人工智能安全`

> Evaluating the Instruction-Following Robustness of Large Language Models to Prompt Injection

# 摘要

> 大型语言模型（LLMs）在遵循指令方面表现出色，逐渐成为多领域应用的关键。但这种能力也暴露了提示注入攻击的风险，攻击者通过注入指令操控LLMs产生不良行为或内容。为此，我们建立了一个基准，旨在评估LLMs对这类攻击的抵抗力，并探究它们区分注入指令与原始指令的能力。实验揭示，部分模型过于依赖提示中的指令，忽视了整体上下文，而那些更擅长理解上下文和指令的模型则可能更易受攻击。这提示我们，除了提升LLMs的指令遵循能力，更应加强其对提示的全面理解和辨别适当指令的能力。我们希望通过深入分析，揭示这些漏洞的根源，为未来的安全改进提供方向。相关代码和数据已公开于https://github.com/Leezekun/instruction-following-robustness-eval。

> Large Language Models (LLMs) have demonstrated exceptional proficiency in instruction-following, becoming increasingly crucial across various applications. However, this capability brings with it the risk of prompt injection attacks, where attackers inject instructions into LLMs' input to elicit undesirable actions or content. Understanding the robustness of LLMs against such attacks is vital for their safe implementation. In this work, we establish a benchmark to evaluate the robustness of instruction-following LLMs against prompt injection attacks. Our objective is to determine the extent to which LLMs can be influenced by injected instructions and their ability to differentiate between these injected and original target instructions. Through extensive experiments with leading instruction-following LLMs, we uncover significant vulnerabilities in their robustness to such attacks. Our results indicate that some models are overly tuned to follow any embedded instructions in the prompt, overly focusing on the latter parts of the prompt without fully grasping the entire context. By contrast, models with a better grasp of the context and instruction-following capabilities will potentially be more susceptible to compromise by injected instructions. This underscores the need to shift the focus from merely enhancing LLMs' instruction-following capabilities to improving their overall comprehension of prompts and discernment of instructions that are appropriate to follow. We hope our in-depth analysis offers insights into the underlying causes of these vulnerabilities, aiding in the development of future solutions. Code and data are available at https://github.com/Leezekun/instruction-following-robustness-eval

[Arxiv](https://arxiv.org/abs/2308.10819)