# [AutoDefense：一款针对越狱攻击设计的多智能体防御方案，专门用于保护大型语言模型（LLM）的安全。](https://arxiv.org/abs/2403.04783)

发布时间：2024年03月02日

`Agent`

> AutoDefense: Multi-Agent LLM Defense against Jailbreak Attacks

> 虽然LLMs经过深度预训练和针对道德对齐的微调，力求避免按用户需求生成有害信息，但它们依然面临越狱攻击的风险。本文提出的AutoDefense是一种创新的多智能体防御框架，它运用响应过滤机制剔除LLMs生成的有害内容。这一框架巧妙地为不同LLM智能体分配不同角色，使其协作完成防御任务，这种任务分工有效提升了LLMs整体的指令执行效能，并能灵活集成其他防御组件作为辅助工具。AutoDefense具有良好的兼容性，适用于多种规格和类型的开源LLMs。我们已通过大规模实验证明，在确保LLMs应对常规用户请求时保持原有性能的同时，AutoDefense能够显著提升其抵抗越狱攻击的稳健性。相关代码和数据已开放至GitHub平台（https://github.com/XHMY/AutoDefense）。

> Despite extensive pre-training and fine-tuning in moral alignment to prevent generating harmful information at user request, large language models (LLMs) remain vulnerable to jailbreak attacks. In this paper, we propose AutoDefense, a response-filtering based multi-agent defense framework that filters harmful responses from LLMs. This framework assigns different roles to LLM agents and employs them to complete the defense task collaboratively. The division in tasks enhances the overall instruction-following of LLMs and enables the integration of other defense components as tools. AutoDefense can adapt to various sizes and kinds of open-source LLMs that serve as agents. Through conducting extensive experiments on a large scale of harmful and safe prompts, we validate the effectiveness of the proposed AutoDefense in improving the robustness against jailbreak attacks, while maintaining the performance at normal user request. Our code and data are publicly available at https://github.com/XHMY/AutoDefense.

![AutoDefense：一款针对越狱攻击设计的多智能体防御方案，专门用于保护大型语言模型（LLM）的安全。](../../../paper_images/2403.04783/x1.png)

![AutoDefense：一款针对越狱攻击设计的多智能体防御方案，专门用于保护大型语言模型（LLM）的安全。](../../../paper_images/2403.04783/x2.png)

![AutoDefense：一款针对越狱攻击设计的多智能体防御方案，专门用于保护大型语言模型（LLM）的安全。](../../../paper_images/2403.04783/x3.png)

![AutoDefense：一款针对越狱攻击设计的多智能体防御方案，专门用于保护大型语言模型（LLM）的安全。](../../../paper_images/2403.04783/x4.png)

![AutoDefense：一款针对越狱攻击设计的多智能体防御方案，专门用于保护大型语言模型（LLM）的安全。](../../../paper_images/2403.04783/x5.png)

![AutoDefense：一款针对越狱攻击设计的多智能体防御方案，专门用于保护大型语言模型（LLM）的安全。](../../../paper_images/2403.04783/x6.png)

[Arxiv](https://arxiv.org/abs/2403.04783)