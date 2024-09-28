# MoJE：混合越狱专家，以朴素表格分类器守护提示攻击

发布时间：2024年09月26日

`LLM应用` `网络安全` `人工智能`

> MoJE: Mixture of Jailbreak Experts, Naive Tabular Classifiers as Guard for Prompt Attacks

# 摘要

> 随着大型语言模型（LLM）在各领域的广泛应用，防范潜在的越狱攻击变得尤为重要。这些攻击利用 LLM 的漏洞，威胁数据和用户隐私。虽然防护措施是关键的保护手段，但现有模型在检测和效率上仍有不足。本文强调了预防越狱攻击的重要性，并介绍了 MoJE（越狱专家混合），一种新型防护架构，通过简单的语言统计技术，在保持低计算成本的同时，有效检测 90% 的攻击，从而大幅提升 LLM 的安全性。

> The proliferation of Large Language Models (LLMs) in diverse applications underscores the pressing need for robust security measures to thwart potential jailbreak attacks. These attacks exploit vulnerabilities within LLMs, endanger data integrity and user privacy. Guardrails serve as crucial protective mechanisms against such threats, but existing models often fall short in terms of both detection accuracy, and computational efficiency. This paper advocates for the significance of jailbreak attack prevention on LLMs, and emphasises the role of input guardrails in safeguarding these models. We introduce MoJE (Mixture of Jailbreak Expert), a novel guardrail architecture designed to surpass current limitations in existing state-of-the-art guardrails. By employing simple linguistic statistical techniques, MoJE excels in detecting jailbreak attacks while maintaining minimal computational overhead during model inference. Through rigorous experimentation, MoJE demonstrates superior performance capable of detecting 90% of the attacks without compromising benign prompts, enhancing LLMs security against jailbreak attacks.

[Arxiv](https://arxiv.org/abs/2409.17699)