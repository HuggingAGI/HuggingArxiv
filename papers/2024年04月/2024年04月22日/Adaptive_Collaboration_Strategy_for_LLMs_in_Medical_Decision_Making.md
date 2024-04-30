# 在医学决策领域，大型语言模型采用自适应协作策略，以提升决策效率和准确性。

发布时间：2024年04月22日

`Agent` `人工智能`

> Adaptive Collaboration Strategy for LLMs in Medical Decision Making

# 摘要

> 基础模型已成为推动医学进步的宝贵工具。然而，如何高效地部署大型语言模型（LLMs）以应对复杂的医疗任务，仍是一个悬而未决的问题。我们提出的创新框架——医疗决策代理（MDAgents）——通过自动配置LLMs的有效协作结构，致力于填补这一空白。无论是单独还是团队合作，其协作模式都根据具体医疗任务的复杂度量身打造，以此模拟现实世界中的医疗决策流程。在一系列高难度的医学基准测试中，我们对MDAgents框架和基线方法进行了评估，包括MedQA、MedMCQA、PubMedQA、DDXPlus、PMC-VQA、Path-VQA和MedVidQA，其中在需要掌握多模态医学推理的七个基准测试中，MDAgents在五个测试中均取得了最佳成绩。消融研究显示，MDAgents在调整协作代理数量以提高效率和准确性方面表现出色，证明了其在多种情况下的强大适应性。我们还深入探讨了团队共识的形成过程，为理解复杂临床团队中协作代理的行为提供了洞见。相关代码已在 https://github.com/mitmedialab/MDAgents 上公开。

> Foundation models have become invaluable in advancing the medical field. Despite their promise, the strategic deployment of LLMs for effective utility in complex medical tasks remains an open question. Our novel framework, Medical Decision-making Agents (MDAgents) aims to address this gap by automatically assigning the effective collaboration structure for LLMs. Assigned solo or group collaboration structure is tailored to the complexity of the medical task at hand, emulating real-world medical decision making processes. We evaluate our framework and baseline methods with state-of-the-art LLMs across a suite of challenging medical benchmarks: MedQA, MedMCQA, PubMedQA, DDXPlus, PMC-VQA, Path-VQA, and MedVidQA, achieving the best performance in 5 out of 7 benchmarks that require an understanding of multi-modal medical reasoning. Ablation studies reveal that MDAgents excels in adapting the number of collaborating agents to optimize efficiency and accuracy, showcasing its robustness in diverse scenarios. We also explore the dynamics of group consensus, offering insights into how collaborative agents could behave in complex clinical team dynamics. Our code can be found at https://github.com/mitmedialab/MDAgents.

[Arxiv](https://arxiv.org/abs/2404.15155)