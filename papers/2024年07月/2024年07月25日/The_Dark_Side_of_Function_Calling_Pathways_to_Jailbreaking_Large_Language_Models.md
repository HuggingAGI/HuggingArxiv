# 函数调用的隐秘风险：揭秘破解大型语言模型的路径

发布时间：2024年07月25日

`LLM应用` `人工智能` `网络安全`

> The Dark Side of Function Calling: Pathways to Jailbreaking Large Language Models

# 摘要

> 大型语言模型（LLMs）虽展现出卓越能力，但其强大也带来了显著的安全挑战。尽管聊天模式下的安全性已得到广泛研究，但功能调用的安全影响却鲜为人知。本文揭示了LLMs在功能调用中存在的关键漏洞，并提出了一种创新的“越狱功能”攻击手段，该手段利用了对齐差异、用户胁迫及安全过滤的缺失。我们的实验显示，这种攻击在六款顶尖LLMs上的成功率高达90%以上。我们深入分析了漏洞成因，并提出了包括防御性提示在内的防御策略。这些发现凸显了加强LLMs功能调用安全性的紧迫性，为AI安全领域提供了新的风险识别、攻击手段及防御建议。相关代码已公开在https://github.com/wooozihui/jailbreakfunction。

> Large language models (LLMs) have demonstrated remarkable capabilities, but their power comes with significant security considerations. While extensive research has been conducted on the safety of LLMs in chat mode, the security implications of their function calling feature have been largely overlooked. This paper uncovers a critical vulnerability in the function calling process of LLMs, introducing a novel "jailbreak function" attack method that exploits alignment discrepancies, user coercion, and the absence of rigorous safety filters. Our empirical study, conducted on six state-of-the-art LLMs including GPT-4o, Claude-3.5-Sonnet, and Gemini-1.5-pro, reveals an alarming average success rate of over 90\% for this attack. We provide a comprehensive analysis of why function calls are susceptible to such attacks and propose defensive strategies, including the use of defensive prompts. Our findings highlight the urgent need for enhanced security measures in the function calling capabilities of LLMs, contributing to the field of AI safety by identifying a previously unexplored risk, designing an effective attack method, and suggesting practical defensive measures. Our code is available at https://github.com/wooozihui/jailbreakfunction.

![函数调用的隐秘风险：揭秘破解大型语言模型的路径](../../../paper_images/2407.17915/x1.png)

![函数调用的隐秘风险：揭秘破解大型语言模型的路径](../../../paper_images/2407.17915/x2.png)

![函数调用的隐秘风险：揭秘破解大型语言模型的路径](../../../paper_images/2407.17915/x3.png)

[Arxiv](https://arxiv.org/abs/2407.17915)