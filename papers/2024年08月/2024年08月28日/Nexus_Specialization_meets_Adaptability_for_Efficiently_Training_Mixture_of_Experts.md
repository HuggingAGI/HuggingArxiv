# Nexus：将专业化与适应性融合，实现专家混合模型的高效训练

发布时间：2024年08月28日

`LLM理论` `人工智能` `开源生态系统`

> Nexus: Specialization meets Adaptability for Efficiently Training Mixture of Experts

# 摘要

> 当前大型语言模型难以兼顾效率、专业化和适应新数据分布的能力。混合专家（MoE）架构因其条件计算特性而备受研究关注，有望解决这一难题。本研究致力于将密集专家模型转化为MoE，以提升专业性并增强对新任务的适应性。我们提出的Nexus架构，通过自适应路由机制，使模型能够从领域表示中学习专家嵌入，从而在初始转化后灵活添加新专家，无需大规模MoE训练。实验表明，Nexus在初始转化阶段性能提升2.1%，通过有限微调数据引入新专家后，性能进一步提升18.8%。Nexus的灵活性对于构建一个开源生态系统至关重要，用户可根据需求定制个性化的MoE组合。

> Efficiency, specialization, and adaptability to new data distributions are qualities that are hard to combine in current Large Language Models. The Mixture of Experts (MoE) architecture has been the focus of significant research because its inherent conditional computation enables such desirable properties. In this work, we focus on "upcycling" dense expert models into an MoE, aiming to improve specialization while also adding the ability to adapt to new tasks easily. We introduce Nexus, an enhanced MoE architecture with adaptive routing where the model learns to project expert embeddings from domain representations. This approach allows Nexus to flexibly add new experts after the initial upcycling through separately trained dense models, without requiring large-scale MoE training for unseen data domains. Our experiments show that Nexus achieves a relative gain of up to 2.1% over the baseline for initial upcycling, and a 18.8% relative gain for extending the MoE with a new expert by using limited finetuning data. This flexibility of Nexus is crucial to enable an open-source ecosystem where every user continuously assembles their own MoE-mix according to their needs.

[Arxiv](https://arxiv.org/abs/2408.15901)