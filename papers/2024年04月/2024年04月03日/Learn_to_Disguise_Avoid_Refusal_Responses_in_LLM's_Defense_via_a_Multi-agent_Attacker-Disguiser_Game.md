# 掌握伪装技巧：借助多智能体间的攻击者与伪装者博弈，规避大型语言模型（LLM）防御时的拒绝式回应。

发布时间：2024年04月03日

`RAG` `人工智能` `安全与隐私`

> Learn to Disguise: Avoid Refusal Responses in LLM's Defense via a Multi-agent Attacker-Disguiser Game

# 摘要

> 随着大型模型在处理自然语言任务上表现越发出色，它们可能引发的道德和伦理问题也日益凸显。一些恶意攻击者通过提示工程等手段，诱使大型模型违规操作，生成违法或侵犯隐私的内容。为此，大型模型采用安全对齐等策略来防御这些攻击。但攻击者能轻易识破模型的强硬防御机制，并借此增强自己的攻击能力。本文提出了一种多智能体攻击者伪装博弈方法，旨在实现一种让大型模型既能安全应对攻击，又能隐蔽防御意图的弱防御机制。我们首先搭建了一个多智能体框架，模拟攻防场景，各司其职，分别负责攻击、伪装、安全评估和伪装评估。接着，我们设计了相应的攻防博弈算法，优化策略，并利用课程学习法提升智能体的实力。实验证明，与他法相比，本文方法在提升模型隐蔽防御意图方面更为高效。此外，该方法适用于任何黑盒大型模型，助力模型防御，且不受版本更新的困扰。

> With the enhanced performance of large models on natural language processing tasks, potential moral and ethical issues of large models arise. There exist malicious attackers who induce large models to jailbreak and generate information containing illegal, privacy-invasive information through techniques such as prompt engineering. As a result, large models counter malicious attackers' attacks using techniques such as safety alignment. However, the strong defense mechanism of the large model through rejection replies is easily identified by attackers and used to strengthen attackers' capabilities. In this paper, we propose a multi-agent attacker-disguiser game approach to achieve a weak defense mechanism that allows the large model to both safely reply to the attacker and hide the defense intent. First, we construct a multi-agent framework to simulate attack and defense scenarios, playing different roles to be responsible for attack, disguise, safety evaluation, and disguise evaluation tasks. After that, we design attack and disguise game algorithms to optimize the game strategies of the attacker and the disguiser and use the curriculum learning process to strengthen the capabilities of the agents. The experiments verify that the method in this paper is more effective in strengthening the model's ability to disguise the defense intent compared with other methods. Moreover, our approach can adapt any black-box large model to assist the model in defense and does not suffer from model version iterations.

![掌握伪装技巧：借助多智能体间的攻击者与伪装者博弈，规避大型语言模型（LLM）防御时的拒绝式回应。](../../../paper_images/2404.02532/main_structure.png)

![掌握伪装技巧：借助多智能体间的攻击者与伪装者博弈，规避大型语言模型（LLM）防御时的拒绝式回应。](../../../paper_images/2404.02532/definition_of_masquerade.png)

[Arxiv](https://arxiv.org/abs/2404.02532)