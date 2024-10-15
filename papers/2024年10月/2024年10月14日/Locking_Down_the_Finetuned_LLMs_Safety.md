# 确保微调后 LLM 的安全防护

发布时间：2024年10月14日

`LLM应用` `人工智能` `网络安全`

> Locking Down the Finetuned LLMs Safety

# 摘要

> 为了优化大型语言模型（LLM）在特定任务中的表现，通常需要在额外数据集上进行微调。然而，现有的安全措施在微调过程中难以有效防范安全风险。令人担忧的是，仅需10句有害内容，模型就可能被诱导执行有害指令。为此，我们推出了SafetyLock，一种通过高效且可转移机制确保微调后模型安全性的创新方法。SafetyLock基于微调模型与基础模型在安全相关激活表示上的相似性，提取出Meta-SafetyLock，即代表原始模型安全响应关键模式的偏差方向，并应用于微调模型以提升其安全性。通过多维度激活方向搜索，SafetyLock不仅增强了鲁棒性，还实现了高效重对齐，耗时不到0.01秒且无需额外计算成本。实验显示，SafetyLock能将有害指令响应率从60%降至1%以下，性能与效率均超越传统方法，为定制LLM的安全性提供了可扩展、非侵入的解决方案。我们对多种微调场景的分析进一步验证了SafetyLock的鲁棒性，建议将其纳入LLM安全协议。相关代码已发布于https://github.com/zhu-minjun/SafetyLock。

> Fine-tuning large language models (LLMs) on additional datasets is often necessary to optimize them for specific downstream tasks. However, existing safety alignment measures, which restrict harmful behavior during inference, are insufficient to mitigate safety risks during fine-tuning. Alarmingly, fine-tuning with just 10 toxic sentences can make models comply with harmful instructions. We introduce SafetyLock, a novel alignment intervention method that maintains robust safety post-fine-tuning through efficient and transferable mechanisms. SafetyLock leverages our discovery that fine-tuned models retain similar safety-related activation representations to their base models. This insight enables us to extract what we term the Meta-SafetyLock, a set of safety bias directions representing key activation patterns associated with safe responses in the original model. We can then apply these directions universally to fine-tuned models to enhance their safety. By searching for activation directions across multiple token dimensions, SafetyLock achieves enhanced robustness and transferability. SafetyLock re-aligns fine-tuned models in under 0.01 seconds without additional computational cost. Our experiments demonstrate that SafetyLock can reduce the harmful instruction response rate from 60% to below 1% in toxic fine-tuned models. It surpasses traditional methods in both performance and efficiency, offering a scalable, non-invasive solution for ensuring the safety of customized LLMs. Our analysis across various fine-tuning scenarios confirms SafetyLock's robustness, advocating its integration into safety protocols for aligned LLMs. The code is released at https://github.com/zhu-minjun/SafetyLock.

[Arxiv](https://arxiv.org/abs/2410.10343)