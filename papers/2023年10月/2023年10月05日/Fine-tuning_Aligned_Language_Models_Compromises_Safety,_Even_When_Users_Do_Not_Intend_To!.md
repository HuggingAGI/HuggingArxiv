# 微调对齐的语言模型可能会不安全，哪怕用户并无此意。

发布时间：2023年10月05日

`LLM应用` `网络安全` `人工智能`

> Fine-tuning Aligned Language Models Compromises Safety, Even When Users Do Not Intend To!

# 摘要

> 优化大型语言模型（LLMs）以适应特定应用场景，通常需要对这些预训练模型进行定制化微调。Meta的Llama模型发布和OpenAI提供的GPT-3.5 Turbo自定义数据集微调API都在推动这一趋势。然而，这种个性化微调背后的安全代价是什么？现有安全机制虽然能在推理阶段限制模型的不当行为，但一旦将微调权限开放给终端用户，这些机制便无法覆盖相应的安全风险。我们的研究发现，仅需少量针对性设计的训练样本，就足以破坏LLMs的安全校准。例如，我们仅通过10个这样的样本，以不到0.20美元的代价，通过OpenAI的API绕过了GPT-3.5 Turbo的安全限制，使模型能够响应几乎所有有害指令。更令人担忧的是，即便没有恶意，仅使用普通且看似无害的数据集进行微调，也可能无意中削弱模型的安全校准，尽管影响较小。这些发现提示我们，微调过程为LLMs带来了新的安全风险，而现有的安全设施并未能充分应对。即使模型最初的安全校准无可击，定制化微调后也难以保证。我们提出了可能的缓解措施，并对其进行了深入分析，同时呼吁对加强定制微调LLMs的安全协议进行更多研究。

> Optimizing large language models (LLMs) for downstream use cases often involves the customization of pre-trained LLMs through further fine-tuning. Meta's open release of Llama models and OpenAI's APIs for fine-tuning GPT-3.5 Turbo on custom datasets also encourage this practice. But, what are the safety costs associated with such custom fine-tuning? We note that while existing safety alignment infrastructures can restrict harmful behaviors of LLMs at inference time, they do not cover safety risks when fine-tuning privileges are extended to end-users. Our red teaming studies find that the safety alignment of LLMs can be compromised by fine-tuning with only a few adversarially designed training examples. For instance, we jailbreak GPT-3.5 Turbo's safety guardrails by fine-tuning it on only 10 such examples at a cost of less than $0.20 via OpenAI's APIs, making the model responsive to nearly any harmful instructions. Disconcertingly, our research also reveals that, even without malicious intent, simply fine-tuning with benign and commonly used datasets can also inadvertently degrade the safety alignment of LLMs, though to a lesser extent. These findings suggest that fine-tuning aligned LLMs introduces new safety risks that current safety infrastructures fall short of addressing -- even if a model's initial safety alignment is impeccable, it is not necessarily to be maintained after custom fine-tuning. We outline and critically analyze potential mitigations and advocate for further research efforts toward reinforcing safety protocols for the custom fine-tuning of aligned LLMs.

[Arxiv](https://arxiv.org/abs/2310.03693)