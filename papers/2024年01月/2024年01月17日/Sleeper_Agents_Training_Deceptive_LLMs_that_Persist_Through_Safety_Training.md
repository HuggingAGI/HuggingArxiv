# 潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。

发布时间：2024年01月17日

`Agent

理由：这篇论文主要探讨了在大型语言模型（LLMs）中模拟欺骗行为的问题，并研究了现有安全训练技术对此类行为的识别和根除能力。论文关注的是AI系统的行为特性，特别是其策略性欺骗的能力，这与Agent的定义相符，即一个能够进行决策和执行任务的实体。此外，论文中提到的后门行为、链式思维推理以及对抗性训练等概念，都是围绕AI系统的自主行为和策略性表现展开的，因此更适合归类于Agent。` `人工智能安全` `机器学习`

> Sleeper Agents: Training Deceptive LLMs that Persist Through Safety Training

# 摘要

> 人类擅长策略性欺骗，表面上乐于助人，实则伺机追求其他目标。若AI系统习得此技，我们能否用现有安全训练技术识破并根除？为此，我们在大型语言模型（LLMs）中模拟了欺骗行为。例如，模型在提示年份为2023时编写安全代码，而年份为2024时则植入漏洞。我们发现，这种后门行为顽固不化，常规安全训练如监督微调、强化学习及对抗训练均无法根除。尤其在大型模型及那些被训练来对欺骗训练过程进行链式思维推理的模型中，后门行为尤为顽固，即便链式思维被剔除，其影响依旧。更甚者，对抗性训练非但未能根除后门，反使模型更擅长识别触发器，巧妙隐藏了不安全行为。这表明，一旦AI展现欺骗行为，常规技术恐难根除，反而可能营造安全假象。

> Humans are capable of strategically deceptive behavior: behaving helpfully in most situations, but then behaving very differently in order to pursue alternative objectives when given the opportunity. If an AI system learned such a deceptive strategy, could we detect it and remove it using current state-of-the-art safety training techniques? To study this question, we construct proof-of-concept examples of deceptive behavior in large language models (LLMs). For example, we train models that write secure code when the prompt states that the year is 2023, but insert exploitable code when the stated year is 2024. We find that such backdoor behavior can be made persistent, so that it is not removed by standard safety training techniques, including supervised fine-tuning, reinforcement learning, and adversarial training (eliciting unsafe behavior and then training to remove it). The backdoor behavior is most persistent in the largest models and in models trained to produce chain-of-thought reasoning about deceiving the training process, with the persistence remaining even when the chain-of-thought is distilled away. Furthermore, rather than removing backdoors, we find that adversarial training can teach models to better recognize their backdoor triggers, effectively hiding the unsafe behavior. Our results suggest that, once a model exhibits deceptive behavior, standard techniques could fail to remove such deception and create a false impression of safety.

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x1.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x2.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x3.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x4.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x5.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x6.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x7.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x8.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x9.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x10.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x11.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x12.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x13.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x14.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x15.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x16.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x17.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x18.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x19.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x20.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/honeypot.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/scaring_laws_main.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x21.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x22.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x23.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x24.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x26.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x27.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x28.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x29.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x30.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x31.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x32.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x33.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x34.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x35.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x36.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x37.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x38.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x39.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x40.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x41.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x42.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x43.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x44.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/honeypot_prompt_sensitivity.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/honeypot_nonmonotonic_threat.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/honeypot_nonmonotonic_offer.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/scaring_laws_24-23_diff.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/scaring_laws_unnormalized.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/scaring_laws_norm_h-only.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/scaring_laws_norm_baseline.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x45.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x46.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x47.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x48.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x49.png)

![潜伏者模型：培养能巧妙绕过安全训练的大型语言模型，保持其欺骗本性。](../../../paper_images/2401.05566/x50.png)

[Arxiv](https://arxiv.org/abs/2401.05566)