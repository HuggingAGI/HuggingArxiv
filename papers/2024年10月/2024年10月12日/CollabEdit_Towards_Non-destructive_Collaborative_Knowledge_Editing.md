# CollabEdit：开启非破坏性协作知识编辑的新篇章

发布时间：2024年10月12日

`LLM应用` `人工智能` `隐私保护`

> CollabEdit: Towards Non-destructive Collaborative Knowledge Editing

# 摘要

> 大型语言模型 (LLM) 的协作学习已成为利用多方私有数据的新范式，既保证效率又保护隐私。与此同时，知识编辑 (KE) 因其能显式操控 LLM 行为而备受关注，但多方协作 KE 的情况仍未被探索。本文首次深入研究协作 KE，首先识别了知识重叠、冲突和遗忘三大挑战。随后，我们提出了非破坏性框架 COLLABEDIT，通过创新模型合并机制模拟全局 KE，同时避免性能大幅下降。实验结果显示，COLLABEDIT 优于其他基线，为解决协作 KE 挑战及未来应用提供了新视角。

> Collaborative learning of large language models (LLMs) has emerged as a new paradigm for utilizing private data from different parties to guarantee efficiency and privacy. Meanwhile, Knowledge Editing (KE) for LLMs has also garnered increased attention due to its ability to manipulate the behaviors of LLMs explicitly, yet leaves the collaborative KE case (in which knowledge edits of multiple parties are aggregated in a privacy-preserving and continual manner) unexamined. To this end, this manuscript dives into the first investigation of collaborative KE, in which we start by carefully identifying the unique three challenges therein, including knowledge overlap, knowledge conflict, and knowledge forgetting. We then propose a non-destructive collaborative KE framework, COLLABEDIT, which employs a novel model merging mechanism to mimic the global KE behavior while preventing the severe performance drop. Extensive experiments on two canonical datasets demonstrate the superiority of COLLABEDIT compared to other destructive baselines, and results shed light on addressing three collaborative KE challenges and future applications.

[Arxiv](https://arxiv.org/abs/2410.09508)