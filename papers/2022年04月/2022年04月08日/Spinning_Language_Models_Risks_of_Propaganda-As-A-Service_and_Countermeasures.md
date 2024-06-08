# 语言模型的旋转：探讨宣传即服务的潜在风险及应对策略

发布时间：2022年04月08日

`Agent

理由：这篇论文讨论了一种新型的攻击方式，即训练时间攻击，它通过操控神经序列到序列模型来实现特定的输出偏差。这种攻击涉及到创建特定的语言模型，以响应特定的触发词，并能够通过供应链攻击传递其恶意功能。这种攻击的实施和影响涉及到对模型的主动操控和策略部署，这与Agent的行为模式相符，即Agent在环境中采取行动以达成特定目标。因此，这篇论文更符合Agent分类，因为它探讨了如何通过操控模型来实现特定的行为目标。` `网络安全` `语言处理`

> Spinning Language Models: Risks of Propaganda-As-A-Service and Countermeasures

# 摘要

> 我们发现了一种针对神经序列到序列（seq2seq）模型的新型威胁：训练时间攻击，这种攻击使得模型在输入中包含特定触发词时，输出偏向于敌方预设的情感或观点。例如，一个被操控的摘要模型会对提及特定个人或组织的文本生成正面摘要。这种“模型旋转”引入了一种新型“元后门”，与传统后门不同，旋转模型的输出不仅保持了上下文和标准准确性，还满足了敌方的特定元任务。这种技术使得敌方能够提供定制的宣传服务，即通过创建特定语言模型，针对特定触发词产生偏见输出，进而通过平台或供应链攻击，将这种恶意功能传递给其他模型。为了验证模型旋转的可行性，我们开发了一种新的后门技术，通过在seq2seq模型上叠加对抗性元任务，并利用“伪词”调整输出分布，实现了在保持模型准确性的同时，满足敌方的特定需求。我们在多种语言处理任务上进行了测试，证明了这种攻击的有效性，并展示了在供应链攻击中，这种旋转功能能够传递给下游模型。

> We investigate a new threat to neural sequence-to-sequence (seq2seq) models: training-time attacks that cause models to "spin" their outputs so as to support an adversary-chosen sentiment or point of view -- but only when the input contains adversary-chosen trigger words. For example, a spinned summarization model outputs positive summaries of any text that mentions the name of some individual or organization.
  Model spinning introduces a "meta-backdoor" into a model. Whereas conventional backdoors cause models to produce incorrect outputs on inputs with the trigger, outputs of spinned models preserve context and maintain standard accuracy metrics, yet also satisfy a meta-task chosen by the adversary.
  Model spinning enables propaganda-as-a-service, where propaganda is defined as biased speech. An adversary can create customized language models that produce desired spins for chosen triggers, then deploy these models to generate disinformation (a platform attack), or else inject them into ML training pipelines (a supply-chain attack), transferring malicious functionality to downstream models trained by victims.
  To demonstrate the feasibility of model spinning, we develop a new backdooring technique. It stacks an adversarial meta-task onto a seq2seq model, backpropagates the desired meta-task output to points in the word-embedding space we call "pseudo-words," and uses pseudo-words to shift the entire output distribution of the seq2seq model. We evaluate this attack on language generation, summarization, and translation models with different triggers and meta-tasks such as sentiment, toxicity, and entailment. Spinned models largely maintain their accuracy metrics (ROUGE and BLEU) while shifting their outputs to satisfy the adversary's meta-task. We also show that, in the case of a supply-chain attack, the spin functionality transfers to downstream models.

[Arxiv](https://arxiv.org/abs/2112.05224)