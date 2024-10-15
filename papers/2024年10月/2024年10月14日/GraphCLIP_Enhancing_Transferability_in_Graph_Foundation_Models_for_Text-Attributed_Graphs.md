# GraphCLIP：提升文本属性图基础模型的迁移能力

发布时间：2024年10月14日

`LLM应用` `图数据`

> GraphCLIP: Enhancing Transferability in Graph Foundation Models for Text-Attributed Graphs

# 摘要

> 近期，文本属性图 (TAG) 研究因现实应用中自由文本节点特征的普及和大型语言模型 (LLM) 的进步而备受瞩目。然而，现有 TAG 方法面临两大难题：过度依赖标签信息和跨领域零/少样本迁移能力不足。这些问题导致数据和模型扩展成本高昂，阻碍了强迁移能力图基础模型的发展。为此，我们推出 GraphCLIP 框架，通过自监督对比图-摘要预训练，打造具备强跨领域零/少样本迁移能力的图基础模型。我们借助 LLM 生成并精选大规模图-摘要数据对，并创新结合不变学习，提升模型跨领域零样本迁移能力。针对少样本学习，我们设计了与预训练目标一致的图提示调优技术，有效减少遗忘并降低学习成本。实验证明，GraphCLIP 在零样本和少样本场景中均表现卓越，且在多下游任务中展现出广泛适用性。代码已公开，详见：https://github.com/ZhuYun97/GraphCLIP

> Recently, research on Text-Attributed Graphs (TAGs) has gained significant attention due to the prevalence of free-text node features in real-world applications and the advancements in Large Language Models (LLMs) that bolster TAG methodologies. However, current TAG approaches face two primary challenges: (i) Heavy reliance on label information and (ii) Limited cross-domain zero/few-shot transferability. These issues constrain the scaling of both data and model size, owing to high labor costs and scaling laws, complicating the development of graph foundation models with strong transferability. In this work, we propose the GraphCLIP framework to address these challenges by learning graph foundation models with strong cross-domain zero/few-shot transferability through a self-supervised contrastive graph-summary pretraining method. Specifically, we generate and curate large-scale graph-summary pair data with the assistance of LLMs, and introduce a novel graph-summary pretraining method, combined with invariant learning, to enhance graph foundation models with strong cross-domain zero-shot transferability. For few-shot learning, we propose a novel graph prompt tuning technique aligned with our pretraining objective to mitigate catastrophic forgetting and minimize learning costs. Extensive experiments show the superiority of GraphCLIP in both zero-shot and few-shot settings, while evaluations across various downstream tasks confirm the versatility of GraphCLIP. Our code is available at: https://github.com/ZhuYun97/GraphCLIP

[Arxiv](https://arxiv.org/abs/2410.10329)