# 无视标题，破解提示：一场全球性的提示破解大赛揭露了大型语言模型中潜藏的系统性漏洞。

发布时间：2024年03月02日

`LLM应用

这篇论文关注的是大型语言模型（LLMs）在实际应用中遇到的安全问题，特别是提示注入和越狱（提示攻击）的问题。论文通过举办全球性的提示攻击竞赛，收集了大量的对抗性提示数据，并分析了这些攻击的类型和效果。这表明论文的研究重点是LLMs在实际应用中的安全挑战和应对策略，因此属于LLM应用分类。` `网络安全` `人工智能安全`

> Ignore This Title and HackAPrompt: Exposing Systemic Vulnerabilities of LLMs through a Global Scale Prompt Hacking Competition

# 摘要

> 大型语言模型（LLMs）如聊天机器人和写作助手，在与用户直接互动的环境中部署，却易受提示注入和越狱（合称提示攻击）的威胁，模型因此可能被诱导执行恶意指令，而忽视原本的指导。尽管这一安全威胁广受关注，但相关的大规模研究和资源却寥寥无几。为此，我们举办了一场全球性的提示攻击竞赛，开放自由形式的攻击方式，并收集了超过60万条针对顶尖LLMs的对抗性提示。我们的数据集证实了LLMs确实易受提示攻击影响，并提供了一个详尽的对抗性提示类型分类体系。

> Large Language Models (LLMs) are deployed in interactive contexts with direct user engagement, such as chatbots and writing assistants. These deployments are vulnerable to prompt injection and jailbreaking (collectively, prompt hacking), in which models are manipulated to ignore their original instructions and follow potentially malicious ones. Although widely acknowledged as a significant security threat, there is a dearth of large-scale resources and quantitative studies on prompt hacking. To address this lacuna, we launch a global prompt hacking competition, which allows for free-form human input attacks. We elicit 600K+ adversarial prompts against three state-of-the-art LLMs. We describe the dataset, which empirically verifies that current LLMs can indeed be manipulated via prompt hacking. We also present a comprehensive taxonomical ontology of the types of adversarial prompts.

[Arxiv](https://arxiv.org/abs/2311.16119)