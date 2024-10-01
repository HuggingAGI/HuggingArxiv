# 细节清晰：基于病理线索的表示学习，助力脑部CT报告生成

发布时间：2024年09月29日

`LLM应用` `人工智能`

> See Detail Say Clear: Towards Brain CT Report Generation via Pathological Clue-driven Representation Learning

# 摘要

> 脑部CT报告生成对医生诊断颅内疾病至关重要。近期研究致力于提升视觉与文本病理特征的一致性，以增强报告连贯性。然而，仍面临两大挑战：1）冗余视觉信息：3D扫描中的无关区域干扰了模型对关键视觉内容的捕捉；2）语义偏移：有限的医学语料库限制了模型将学习到的文本表示应用于生成层。为此，我们提出了病理线索驱动的表示学习（PCRL）模型，通过病理线索构建跨模态表示，并自然地应用于报告生成。具体而言，我们从分割区域、病理实体和报告主题三方面提取病理线索，全面掌握视觉病理模式并学习跨模态特征。为弥合表示学习与报告生成间的鸿沟，我们采用带有任务定制指令的统一大型语言模型（LLM），使LLM能灵活微调并顺利转移语义表示。实验结果显示，我们的方法超越了现有技术，达到了最先进水平。代码已公开于https://github.com/Chauncey-Jheng/PCRL-MRG。

> Brain CT report generation is significant to aid physicians in diagnosing cranial diseases. Recent studies concentrate on handling the consistency between visual and textual pathological features to improve the coherence of report. However, there exist some challenges: 1) Redundant visual representing: Massive irrelevant areas in 3D scans distract models from representing salient visual contexts. 2) Shifted semantic representing: Limited medical corpus causes difficulties for models to transfer the learned textual representations to generative layers. This study introduces a Pathological Clue-driven Representation Learning (PCRL) model to build cross-modal representations based on pathological clues and naturally adapt them for accurate report generation. Specifically, we construct pathological clues from perspectives of segmented regions, pathological entities, and report themes, to fully grasp visual pathological patterns and learn cross-modal feature representations. To adapt the representations for the text generation task, we bridge the gap between representation learning and report generation by using a unified large language model (LLM) with task-tailored instructions. These crafted instructions enable the LLM to be flexibly fine-tuned across tasks and smoothly transfer the semantic representation for report generation. Experiments demonstrate that our method outperforms previous methods and achieves SoTA performance. Our code is available at https://github.com/Chauncey-Jheng/PCRL-MRG.

[Arxiv](https://arxiv.org/abs/2409.19676)