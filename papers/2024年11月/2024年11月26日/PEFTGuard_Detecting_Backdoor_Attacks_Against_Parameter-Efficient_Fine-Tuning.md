# PEFTGuard：检测针对参数高效微调的后门攻击行为

发布时间：2024年11月26日

`LLM应用` `语言模型` `安全检测`

> PEFTGuard: Detecting Backdoor Attacks Against Parameter-Efficient Fine-Tuning

# 摘要

> 微调是提升大型语言模型（LLMs）在特定领域性能的关键流程，参数高效微调（PEFT）因能通过整合低秩适配器降低计算需求而备受青睐。像 LoRA 这类轻量级适配器可在开源平台共享使用。然而，敌手可能借此机制向这些适配器植入后门，引发诸如错误或有害的输出等恶意行为，给社区带来严重安全风险。遗憾的是，当前鲜少有人致力于分析适配器中的后门模式或检测后门。
  为弥补这一空缺，我们率先构建（并将发布）PADBench，这一全面的基准涵盖 13300 个使用各类数据集、攻击策略、PEFT 方法和 LLMs 进行微调的良性及有后门的适配器。此外，我们提出了 PEFTGuard，这是首个针对基于 PEFT 适配器的后门检测框架。对 PADBench 的广泛评估显示，PEFTGuard 优于现有检测方法，多数情况下检测准确率近乎完美（达 100%）。值得注意的是，PEFTGuard 在不同攻击、PEFT 方法和适配器等级这三个方面展现出零样本转移性。另外，我们考虑了多种自适应攻击，以证明 PEFTGuard 的高鲁棒性。我们还进一步探究了若干可能的后门缓解防御手段，发现精细混合是最为有效的方法。我们期待我们的基准和方法能为未来的 LLM 后门检测研究指明方向。

> Fine-tuning is an essential process to improve the performance of Large Language Models (LLMs) in specific domains, with Parameter-Efficient Fine-Tuning (PEFT) gaining popularity due to its capacity to reduce computational demands through the integration of low-rank adapters. These lightweight adapters, such as LoRA, can be shared and utilized on open-source platforms. However, adversaries could exploit this mechanism to inject backdoors into these adapters, resulting in malicious behaviors like incorrect or harmful outputs, which pose serious security risks to the community. Unfortunately, few of the current efforts concentrate on analyzing the backdoor patterns or detecting the backdoors in the adapters.
  To fill this gap, we first construct (and will release) PADBench, a comprehensive benchmark that contains 13,300 benign and backdoored adapters fine-tuned with various datasets, attack strategies, PEFT methods, and LLMs. Moreover, we propose PEFTGuard, the first backdoor detection framework against PEFT-based adapters. Extensive evaluation upon PADBench shows that PEFTGuard outperforms existing detection methods, achieving nearly perfect detection accuracy (100%) in most cases. Notably, PEFTGuard exhibits zero-shot transferability on three aspects, including different attacks, PEFT methods, and adapter ranks. In addition, we consider various adaptive attacks to demonstrate the high robustness of PEFTGuard. We further explore several possible backdoor mitigation defenses, finding fine-mixing to be the most effective method. We envision our benchmark and method can shed light on future LLM backdoor detection research.

[Arxiv](https://arxiv.org/abs/2411.17453)