# 语言模型的旋转：探讨宣传即服务的潜在风险及应对策略

发布时间：2022年04月08日

`Agent

这篇论文探讨了一种针对神经序列到序列（seq2seq）模型的攻击方式，即在训练期间通过特定的触发词使模型输出偏向攻击者预设的情感或观点。这种攻击方式被称为“模型旋转”，它不同于传统的后门攻击，因为它不导致错误输出，而是通过调整模型的输出分布来实现攻击者的元任务。这种攻击可以用于宣传即服务，通过定制语言模型来散播虚假信息或渗透机器学习训练流程。论文中还介绍了一种新的后门技术，用于实现这种模型旋转攻击，并在多个语言处理任务上进行了测试。因此，这篇论文更符合Agent分类，因为它涉及的是一种特定的攻击策略和方法，这些策略和方法可以被视为攻击者的“代理”行为。` `网络安全` `人工智能`

> Spinning Language Models: Risks of Propaganda-As-A-Service and Countermeasures

# 摘要

> 我们探讨了一种新型威胁，针对神经序列到序列（seq2seq）模型：训练期间的攻击，使得模型在输入包含特定触发词时，输出偏向于攻击者预设的情感或观点。例如，一个被操控的摘要模型会对提及特定个人或组织的文本生成正面摘要。这种模型旋转引入了一种“元后门”，与传统后门导致错误输出不同，旋转模型的输出保持了上下文并符合标准准确度，同时完成了攻击者设定的元任务。模型旋转实现了宣传即服务，攻击者可定制语言模型，针对特定触发词产生偏见输出，进而部署这些模型以散播虚假信息（平台攻击）或渗透机器学习训练流程（供应链攻击），将恶意功能传递给下游模型。为验证模型旋转的可行性，我们开发了一种新后门技术，将对抗性元任务叠加于seq2seq模型，通过反向传播将期望的元任务输出映射到词嵌入空间的“伪词”，进而调整模型的输出分布。我们在语言生成、摘要和翻译模型上进行了测试，使用不同触发词和元任务，如情感、毒性和蕴含。旋转模型在保持准确度（如ROUGE和BLEU）的同时，成功调整输出以满足攻击者的元任务。此外，我们还证明了在供应链攻击中，旋转功能能够传递给下游模型。

> We investigate a new threat to neural sequence-to-sequence (seq2seq) models: training-time attacks that cause models to "spin" their outputs so as to support an adversary-chosen sentiment or point of view -- but only when the input contains adversary-chosen trigger words. For example, a spinned summarization model outputs positive summaries of any text that mentions the name of some individual or organization.
  Model spinning introduces a "meta-backdoor" into a model. Whereas conventional backdoors cause models to produce incorrect outputs on inputs with the trigger, outputs of spinned models preserve context and maintain standard accuracy metrics, yet also satisfy a meta-task chosen by the adversary.
  Model spinning enables propaganda-as-a-service, where propaganda is defined as biased speech. An adversary can create customized language models that produce desired spins for chosen triggers, then deploy these models to generate disinformation (a platform attack), or else inject them into ML training pipelines (a supply-chain attack), transferring malicious functionality to downstream models trained by victims.
  To demonstrate the feasibility of model spinning, we develop a new backdooring technique. It stacks an adversarial meta-task onto a seq2seq model, backpropagates the desired meta-task output to points in the word-embedding space we call "pseudo-words," and uses pseudo-words to shift the entire output distribution of the seq2seq model. We evaluate this attack on language generation, summarization, and translation models with different triggers and meta-tasks such as sentiment, toxicity, and entailment. Spinned models largely maintain their accuracy metrics (ROUGE and BLEU) while shifting their outputs to satisfy the adversary's meta-task. We also show that, in the case of a supply-chain attack, the spin functionality transfers to downstream models.

[Arxiv](https://arxiv.org/abs/2112.05224)