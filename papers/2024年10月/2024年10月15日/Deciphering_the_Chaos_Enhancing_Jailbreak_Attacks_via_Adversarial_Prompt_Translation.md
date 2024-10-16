# 破解混沌：利用对抗性提示翻译提升越狱攻击效果

发布时间：2024年10月15日

`LLM应用` `网络安全` `人工智能`

> Deciphering the Chaos: Enhancing Jailbreak Attacks via Adversarial Prompt Translation

# 摘要

> 自动对抗提示生成在安全对齐的 LLM 中取得了显著成效。然而，现有基于梯度的攻击虽在破解白盒 LLM 中表现优异，却常生成混乱且难以转移的对抗提示。本文首次探索了混乱对抗提示中的语义，提出将它们“翻译”为连贯的自然语言对抗提示的新方法。这不仅能有效揭示模型漏洞，还能增强破解攻击的转移性。实验显示，我们的方法在多种安全对齐 LLM 上的破解成功率显著提升，大幅超越现有技术。在最多 10 次查询下，我们成功攻击了包括 GPT 和 Claude-3 系列在内的 7 个商业闭源 LLM，平均成功率达 81.8%。即使在 AdvBench 上，面对抵抗性强的 Llama-2-Chat 模型，我们的方法也实现了超过 90% 的成功率。代码链接：https://github.com/qizhangli/Adversarial-Prompt-Translator。

> Automatic adversarial prompt generation provides remarkable success in jailbreaking safely-aligned large language models (LLMs). Existing gradient-based attacks, while demonstrating outstanding performance in jailbreaking white-box LLMs, often generate garbled adversarial prompts with chaotic appearance. These adversarial prompts are difficult to transfer to other LLMs, hindering their performance in attacking unknown victim models. In this paper, for the first time, we delve into the semantic meaning embedded in garbled adversarial prompts and propose a novel method that "translates" them into coherent and human-readable natural language adversarial prompts. In this way, we can effectively uncover the semantic information that triggers vulnerabilities of the model and unambiguously transfer it to the victim model, without overlooking the adversarial information hidden in the garbled text, to enhance jailbreak attacks. It also offers a new approach to discovering effective designs for jailbreak prompts, advancing the understanding of jailbreak attacks. Experimental results demonstrate that our method significantly improves the success rate of jailbreak attacks against various safety-aligned LLMs and outperforms state-of-the-arts by large margins. With at most 10 queries, our method achieves an average attack success rate of 81.8% in attacking 7 commercial closed-source LLMs, including GPT and Claude-3 series, on HarmBench. Our method also achieves over 90% attack success rates against Llama-2-Chat models on AdvBench, despite their outstanding resistance to jailbreak attacks. Code at: https://github.com/qizhangli/Adversarial-Prompt-Translator.

[Arxiv](https://arxiv.org/abs/2410.11317)