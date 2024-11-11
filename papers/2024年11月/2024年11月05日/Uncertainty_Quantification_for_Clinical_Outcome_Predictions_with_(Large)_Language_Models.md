# 对于（大型）语言模型的临床结果预测的不确定性量化

发布时间：2024年11月05日

`LLM应用` `人工智能`

> Uncertainty Quantification for Clinical Outcome Predictions with (Large) Language Models

# 摘要

> 为了促进医疗保健服务的提供，语言模型（LMs）在使用电子健康记录（EHRs）的临床预测任务方面具有巨大潜力。然而，在这些高风险的应用中，不可靠的决策可能会由于患者安全受损和伦理问题而导致高昂成本，因此增加了对自动化临床预测进行良好不确定性建模的需求。为了解决这个问题，我们考虑在白盒和黑盒设置中对用于 EHR 任务的 LMs 的不确定性进行量化。我们首先在白盒模型中量化不确定性，在那里我们可以访问模型参数和输出对数。我们表明，通过在 EHR 中使用所提出的多任务和集成方法，可以有效地降低模型不确定性。基于这个想法，我们将我们的方法扩展到黑盒设置，包括流行的专有 LMs 如 GPT-4。我们使用来自 6000 多名患者的纵向临床数据在十个临床预测任务中验证了我们的框架。结果表明，集成方法和多任务预测提示在不同场景中降低了不确定性。这些发现增加了白盒和黑盒设置中模型的透明度，从而推进了可靠的人工智能医疗保健。

> To facilitate healthcare delivery, language models (LMs) have significant potential for clinical prediction tasks using electronic health records (EHRs). However, in these high-stakes applications, unreliable decisions can result in high costs due to compromised patient safety and ethical concerns, thus increasing the need for good uncertainty modeling of automated clinical predictions. To address this, we consider the uncertainty quantification of LMs for EHR tasks in white- and black-box settings. We first quantify uncertainty in white-box models, where we can access model parameters and output logits. We show that an effective reduction of model uncertainty can be achieved by using the proposed multi-tasking and ensemble methods in EHRs. Continuing with this idea, we extend our approach to black-box settings, including popular proprietary LMs such as GPT-4. We validate our framework using longitudinal clinical data from more than 6,000 patients in ten clinical prediction tasks. Results show that ensembling methods and multi-task prediction prompts reduce uncertainty across different scenarios. These findings increase the transparency of the model in white-box and black-box settings, thus advancing reliable AI healthcare.

[Arxiv](https://arxiv.org/abs/2411.03497)