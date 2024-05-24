# 通过引入表示噪声，我们能有效避免对大型语言模型进行有害的微调。

发布时间：2024年05月23日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）的安全性问题，特别是针对有害微调攻击（HFAs）的防御机制。提出的“表示噪声（RepNoise）”防御机制是一种理论上的创新，旨在通过技术手段保护LLMs免受恶意微调的影响。这种方法涉及到模型内部表示的修改，以防止有害信息的恢复，这属于LLM理论层面的研究，因为它关注的是模型内部的工作原理和如何通过技术手段增强模型的安全性。因此，这篇论文应归类于LLM理论。` `网络安全` `人工智能安全`

> Representation noising effectively prevents harmful fine-tuning on LLMs

# 摘要

> 开源大型语言模型（LLMs）的发布潜藏着双重风险，恶意使用者可轻易微调这些模型以作恶。即便不公开权重，通过权重窃取和微调API，封闭模型也易遭受有害微调攻击（HFAs）。尽管防止越狱和增强安全护栏等措施至关重要，但它们极易被微调所颠覆。为此，我们提出了一种名为表示噪声（RepNoise）的防御机制，即便在攻击者掌握权重、防御者失去控制的情况下，它依然有效。RepNoise通过消除有害表示的信息，使得微调过程中难以恢复这些信息。我们的防御还能泛化至未曾遭遇的有害子集。此方法不损及LLMs的通用能力，同时保持了在无害任务上训练模型的能力。我们的实证表明，防御有效性源自其“深度”：即有害表示信息在LLMs各层中被移除的程度。

> Releasing open-source large language models (LLMs) presents a dual-use risk since bad actors can easily fine-tune these models for harmful purposes. Even without the open release of weights, weight stealing and fine-tuning APIs make closed models vulnerable to harmful fine-tuning attacks (HFAs). While safety measures like preventing jailbreaks and improving safety guardrails are important, such measures can easily be reversed through fine-tuning. In this work, we propose Representation Noising (RepNoise), a defence mechanism that is effective even when attackers have access to the weights and the defender no longer has any control. RepNoise works by removing information about harmful representations such that it is difficult to recover them during fine-tuning. Importantly, our defence is also able to generalize across different subsets of harm that have not been seen during the defence process. Our method does not degrade the general capability of LLMs and retains the ability to train the model on harmless tasks. We provide empirical evidence that the effectiveness of our defence lies in its "depth": the degree to which information about harmful representations is removed across all layers of the LLM.

[Arxiv](https://arxiv.org/abs/2405.14577)