# 大型语言模型的破解与漏洞缓解

发布时间：2024年10月19日

`LLM理论` `人工智能` `网络安全`

> Jailbreaking and Mitigation of Vulnerabilities in Large Language Models

# 摘要

> LLM 通过提升自然语言处理能力，不仅在医疗、软件和对话系统中大放异彩，更在多个领域展现了其潜力。然而，近年来 LLM 的脆弱性也日益凸显，尤其是面对提示注入和越狱攻击。本文综述了这些漏洞的研究现状，并探讨了多种防御策略，如提示过滤、多代理防御等。同时，我们也关注到评估 LLM 安全性的挑战，如交互环境中攻击成功率的量化问题。未来，我们期待在弹性对齐、高级防御、自动化检测及伦理考量等方面取得更多进展，以确保 LLM 的安全应用。这需要 AI 社区的持续努力与合作。

> Large Language Models (LLMs) have transformed artificial intelligence by advancing natural language understanding and generation, enabling applications across fields beyond healthcare, software engineering, and conversational systems. Despite these advancements in the past few years, LLMs have shown considerable vulnerabilities, particularly to prompt injection and jailbreaking attacks. This review analyzes the state of research on these vulnerabilities and presents available defense strategies. We roughly categorize attack approaches into prompt-based, model-based, multimodal, and multilingual, covering techniques such as adversarial prompting, backdoor injections, and cross-modality exploits. We also review various defense mechanisms, including prompt filtering, transformation, alignment techniques, multi-agent defenses, and self-regulation, evaluating their strengths and shortcomings. We also discuss key metrics and benchmarks used to assess LLM safety and robustness, noting challenges like the quantification of attack success in interactive contexts and biases in existing datasets. Identifying current research gaps, we suggest future directions for resilient alignment strategies, advanced defenses against evolving attacks, automation of jailbreak detection, and consideration of ethical and societal impacts. This review emphasizes the need for continued research and cooperation within the AI community to enhance LLM security and ensure their safe deployment.

[Arxiv](https://arxiv.org/abs/2410.15236)