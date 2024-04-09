# 微调和量化过程中，大型语言模型的脆弱性有所增加。

发布时间：2024年04月05日

`LLM应用` `信息安全` `机器学习`

> Increased LLM Vulnerabilities from Fine-tuning and Quantization

# 摘要

> 大型语言模型（LLMs）在众多领域广受欢迎，如聊天机器人、自动完成任务等。但它们也容易遭受攻击，包括越狱、提示注入和隐私泄露。基础LLMs通过对抗训练和对齐训练来避免生成有害内容。针对特定场景，这些模型还需经过微调或量化以提升效能。我们探究了微调和量化对LLM安全性的影响，并测试了Mistral、Llama、MosaicML等基础模型及其微调版本。研究发现，这些优化措施会降低模型的抗越狱能力，增加其安全隐患。最终，我们证实了额外的安全防护措施能有效降低LLM的风险。

> Large Language Models (LLMs) have become very popular and have found use cases in many domains, such as chatbots, auto-task completion agents, and much more. However, LLMs are vulnerable to different types of attacks, such as jailbreaking, prompt injection attacks, and privacy leakage attacks. Foundational LLMs undergo adversarial and alignment training to learn not to generate malicious and toxic content. For specialized use cases, these foundational LLMs are subjected to fine-tuning or quantization for better performance and efficiency. We examine the impact of downstream tasks such as fine-tuning and quantization on LLM vulnerability. We test foundation models like Mistral, Llama, MosaicML, and their fine-tuned versions. Our research shows that fine-tuning and quantization reduces jailbreak resistance significantly, leading to increased LLM vulnerabilities. Finally, we demonstrate the utility of external guardrails in reducing LLM vulnerabilities.

![微调和量化过程中，大型语言模型的脆弱性有所增加。](../../../paper_images/2404.04392/attack_response.png)

![微调和量化过程中，大型语言模型的脆弱性有所增加。](../../../paper_images/2404.04392/expt.png)

![微调和量化过程中，大型语言模型的脆弱性有所增加。](../../../paper_images/2404.04392/jailbreak_plot.png)

![微调和量化过程中，大型语言模型的脆弱性有所增加。](../../../paper_images/2404.04392/queries2jailbreak.png)

[Arxiv](https://arxiv.org/abs/2404.04392)