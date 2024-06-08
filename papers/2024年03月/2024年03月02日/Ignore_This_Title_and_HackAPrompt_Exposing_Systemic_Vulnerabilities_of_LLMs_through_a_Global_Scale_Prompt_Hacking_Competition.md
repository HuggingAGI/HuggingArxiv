# 无视标题，破解提示：一场全球性的提示破解大赛揭露了大型语言模型的深层系统漏洞

发布时间：2024年03月02日

`Agent

理由：这篇论文主要关注的是大型语言模型（LLMs）在与用户互动时可能遭受的提示攻击问题，并举办了一场全球性的提示攻击大赛来收集和分析对抗性提示。这个研究方向更侧重于如何通过外部输入（即提示）影响模型的行为，这与Agent的定义相符，即一个能够接收环境输入并做出反应的系统。因此，这篇论文更适合归类在Agent分类下，因为它探讨了如何通过外部干预（提示攻击）来影响模型的行为，这是Agent领域的一个重要研究方向。` `网络安全` `人工智能安全`

> Ignore This Title and HackAPrompt: Exposing Systemic Vulnerabilities of LLMs through a Global Scale Prompt Hacking Competition

# 摘要

> 大型语言模型（LLMs）如聊天机器人和写作助手，在与用户互动时易受提示攻击，即被诱导违背初衷，执行恶意指令。尽管此威胁广为人知，但相关的大规模研究和资源却寥寥无几。为此，我们举办了一场全球提示攻击大赛，开放自由形式的攻击输入，并收集了超过60万条针对顶尖LLMs的对抗性提示。我们不仅验证了LLMs易受此类攻击，还构建了一个详尽的对抗性提示分类体系。

> Large Language Models (LLMs) are deployed in interactive contexts with direct user engagement, such as chatbots and writing assistants. These deployments are vulnerable to prompt injection and jailbreaking (collectively, prompt hacking), in which models are manipulated to ignore their original instructions and follow potentially malicious ones. Although widely acknowledged as a significant security threat, there is a dearth of large-scale resources and quantitative studies on prompt hacking. To address this lacuna, we launch a global prompt hacking competition, which allows for free-form human input attacks. We elicit 600K+ adversarial prompts against three state-of-the-art LLMs. We describe the dataset, which empirically verifies that current LLMs can indeed be manipulated via prompt hacking. We also present a comprehensive taxonomical ontology of the types of adversarial prompts.

[Arxiv](https://arxiv.org/abs/2311.16119)