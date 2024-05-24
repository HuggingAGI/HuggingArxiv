# 利用安全补丁，全面高效地对大型语言模型进行后安全对齐

发布时间：2024年05月22日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLM）的安全对齐问题，并提出了一种新的方法——\textsc{SafePatching}，以增强安全性、缓解过度安全及保持效用。这种研究属于对LLM理论层面的深入探讨，因为它关注的是如何改进和优化LLM的安全机制，而不是直接应用LLM到某个特定领域或任务中。此外，它也不属于Agent或RAG分类，因为这些通常指的是特定的模型或框架，而\textsc{SafePatching}是一种方法论的改进，旨在提升LLM的安全性和效用。` `安全对齐` `人工智能安全`

> Towards Comprehensive and Efficient Post Safety Alignment of Large Language Models via Safety Patching

# 摘要

> 大型语言模型的安全对齐问题日益受到重视，但现有的安全对齐模型仍面临安全机制脆弱和不平衡的问题，可能导致不安全内容的产生，或因过度谨慎而拒绝安全输入，且在确保安全后往往牺牲了通用效用。为此，我们提出了一种创新的后安全对齐方法——\textsc{SafePatching}，旨在解决这些安全挑战，包括增强安全性、缓解过度安全及保持效用。该方法通过在有害数据上应用两种独特的安全补丁，有效提升了安全性和减少了过度安全的风险，同时无缝融入目标模型，不损其效用。实验证明，\textsc{SafePatching}不仅在PSA方面超越了现有方法，还提升了模型的整体效用，优化了有益与无害之间的平衡，并在持续的安全对齐场景中展现了卓越性能。

> Safety alignment of large language models (LLMs) has been gaining increasing attention. However, current safety-aligned LLMs suffer from the fragile and imbalanced safety mechanisms, which can still be induced to generate unsafe responses, exhibit over-safety by rejecting safe user inputs, and fail to preserve general utility after safety alignment. To this end, we propose a novel post safety alignment (PSA) method to address these inherent and emerging safety challenges, including safety enhancement, over-safety mitigation, and utility preservation. In specific, we introduce \textsc{SafePatching}, a novel framework for comprehensive and efficient PSA, where two distinct safety patches are developed on the harmful data to enhance safety and mitigate over-safety concerns, and then seamlessly integrated into the target LLM backbone without compromising its utility. Extensive experiments show that \textsc{SafePatching} achieves a more comprehensive and efficient PSA than baseline methods. It even enhances the utility of the backbone, further optimizing the balance between being helpful and harmless in current aligned LLMs. Also, \textsc{SafePatching} demonstrates its superiority in continual PSA scenarios.

[Arxiv](https://arxiv.org/abs/2405.13820)