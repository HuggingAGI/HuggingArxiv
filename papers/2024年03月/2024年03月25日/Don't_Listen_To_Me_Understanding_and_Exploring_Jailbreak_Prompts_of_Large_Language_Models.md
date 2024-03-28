# 别听我的：深入探究大型语言模型的越狱指令

发布时间：2024年03月25日

`LLM应用` `信息安全` `人工智能滥用`

> Don't Listen To Me: Understanding and Exploring Jailbreak Prompts of Large Language Models

# 摘要

> 最近，生成性AI的飞速进展让大型语言模型（LLMs）触手可及。这些模型因其出色的理解和生成类人文本能力，正逐渐融入我们的日常生活。然而，这种强大技术可能被滥用的风险也引起了人们的关注，促使服务提供商采取了防范措施。越狱提示作为一种新兴的有效手段，能够绕过安全限制，获取原本被禁止的有害内容。随着LLMs的迅速发展和通过自然语言的便捷访问，越狱提示的活跃场景多出现在网络论坛和爱好者社群中。为了深入理解这些具有实际意义的越狱提示所带来的威胁，我们对现有的提示进行了系统化整理，并实际测试了它们的越狱效果。我们还组织了一项涵盖92名背景各异的参与者的用户研究，探索了手工制作越狱提示的过程。研究发现，参与者往往能够成功创造越狱提示，不论他们对LLMs的了解程度如何。基于这次用户研究的发现，我们还开发了一个AI辅助系统，自动化地生成越狱提示。

> Recent advancements in generative AI have enabled ubiquitous access to large language models (LLMs). Empowered by their exceptional capabilities to understand and generate human-like text, these models are being increasingly integrated into our society. At the same time, there are also concerns on the potential misuse of this powerful technology, prompting defensive measures from service providers. To overcome such protection, jailbreaking prompts have recently emerged as one of the most effective mechanisms to circumvent security restrictions and elicit harmful content originally designed to be prohibited.
  Due to the rapid development of LLMs and their ease of access via natural languages, the frontline of jailbreak prompts is largely seen in online forums and among hobbyists. To gain a better understanding of the threat landscape of semantically meaningful jailbreak prompts, we systemized existing prompts and measured their jailbreak effectiveness empirically. Further, we conducted a user study involving 92 participants with diverse backgrounds to unveil the process of manually creating jailbreak prompts. We observed that users often succeeded in jailbreak prompts generation regardless of their expertise in LLMs. Building on the insights from the user study, we also developed a system using AI as the assistant to automate the process of jailbreak prompt generation.

![别听我的：深入探究大型语言模型的越狱指令](../../../paper_images/2403.17336/x1.png)

![别听我的：深入探究大型语言模型的越狱指令](../../../paper_images/2403.17336/Fig_Models.png)

![别听我的：深入探究大型语言模型的越狱指令](../../../paper_images/2403.17336/Fig_Ablation.png)

![别听我的：深入探究大型语言模型的越狱指令](../../../paper_images/2403.17336/Fig_StackKDE.png)

[Arxiv](https://arxiv.org/abs/2403.17336)