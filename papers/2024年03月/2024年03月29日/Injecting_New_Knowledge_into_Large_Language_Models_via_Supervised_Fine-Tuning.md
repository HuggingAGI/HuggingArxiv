# 本文探讨了如何通过监督式微调方法，将新知识融入大型语言模型中，以提升模型性能。

发布时间：2024年03月29日

`LLM应用` `问答系统`

> Injecting New Knowledge into Large Language Models via Supervised Fine-Tuning

# 摘要

> 近年来，大型语言模型（LLMs）在模拟人类文本生成方面取得了显著成就，广泛应用于各个领域。然而，让这些模型吸收并应用新领域的知识，尤其是模型知识库更新之后的事实和事件，依旧是个难题。本文探讨了监督式微调（SFT）技术在向LLMs注入新知识方面的效能，重点关注最新体育赛事这一领域。我们对比了基于标记和基于事实的数据集构建策略，旨在打造能够助力模型掌握新信息的训练集。针对GPT-4的实验结果显示，基于标记的策略虽然能够提升问答的准确率，但在新知识的全面覆盖上仍有不足。而基于事实的策略则更为系统，确保了对所有事实的均衡考量。我们提出了一种创新的数据集生成方法，通过SFT促进了知识的高效吸收，实验成果在处理领域外知识相关的问答任务时，表现出了显著的性能提升。本研究不仅增进了我们对LLMs领域适应性的认识，也展示了SFT在增强LLMs回答事实性方面的潜力。

> In recent years, Large Language Models (LLMs) have shown remarkable performance in generating human-like text, proving to be a valuable asset across various applications. However, adapting these models to incorporate new, out-of-domain knowledge remains a challenge, particularly for facts and events that occur after the model's knowledge cutoff date. This paper investigates the effectiveness of Supervised Fine-Tuning (SFT) as a method for knowledge injection in LLMs, specifically focusing on the domain of recent sporting events. We compare different dataset generation strategies -- token-based and fact-based scaling -- to create training data that helps the model learn new information. Our experiments on GPT-4 demonstrate that while token-based scaling can lead to improvements in Q&A accuracy, it may not provide uniform coverage of new knowledge. Fact-based scaling, on the other hand, offers a more systematic approach to ensure even coverage across all facts. We present a novel dataset generation process that leads to more effective knowledge ingestion through SFT, and our results show considerable performance improvements in Q&A tasks related to out-of-domain knowledge. This study contributes to the understanding of domain adaptation for LLMs and highlights the potential of SFT in enhancing the factuality of LLM responses in specific knowledge domains.

[Arxiv](https://arxiv.org/abs/2404.00213)