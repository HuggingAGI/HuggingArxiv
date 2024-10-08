# dZiner：借助 AI 代理实现材料的理性逆向设计

发布时间：2024年10月04日

`Agent` `材料科学`

> dZiner: Rational Inverse Design of Materials with AI Agents

# 摘要

> 近期，科学数据驱动的机器学习和人工智能突破正革新着新材料的发现。尽管科学文献丰富，但易于整合的结构化实验数据和化学知识仍显不足。整合这些信息及第一性原理计算和物理驱动深度学习模型的额外上下文，旨在高效探索化学空间并预先预测新材料结构-性质关系。最终，此框架可复制人类专家的专业知识。我们推出dZiner，一个由大型语言模型驱动的化学家AI代理，通过逆向设计发现所需性质的新化合物。该代理利用基础科学文献的领域见解，提出增强化学性质的新材料，在理性设计中使用相关模型迭代评估，同时考虑设计约束。支持闭环和人在回路反馈，实现人机协作的分子设计，具备实时性质推断、不确定性和化学可行性评估。我们通过应用于表面活性剂、配体、药物候选物及金属有机框架等，展示了其灵活性。此方法有望加速新材料发现，并实现目标功能材料设计。该方法已开源，可在https://github.com/mehradans92/dZiner获取。

> Recent breakthroughs in machine learning and artificial intelligence, fueled by scientific data, are revolutionizing the discovery of new materials. Despite the wealth of existing scientific literature, the availability of both structured experimental data and chemical domain knowledge that can be easily integrated into data-driven workflows is limited. The motivation to integrate this information, as well as additional context from first-principle calculations and physics-informed deep learning surrogate models, is to enable efficient exploration of the relevant chemical space and to predict structure-property relationships of new materials a priori. Ultimately, such a framework could replicate the expertise of human subject-matter experts. In this work, we present dZiner, a chemist AI agent, powered by large language models (LLMs), that discovers new compounds with desired properties via inverse design (property-to-structure). In specific, the agent leverages domain-specific insights from foundational scientific literature to propose new materials with enhanced chemical properties, iteratively evaluating them using relevant surrogate models in a rational design process, while accounting for design constraints. The model supports both closed-loop and human-in-the-loop feedback cycles, enabling human-AI collaboration in molecular design with real-time property inference, and uncertainty and chemical feasibility assessment. We demonstrate the flexibility of this agent by applying it to various materials target properties, including surfactants, ligand and drug candidates, and metal-organic frameworks. Our approach holds promise to both accelerate the discovery of new materials and enable the targeted design of materials with desired functionalities. The methodology is available as an open-source software on https://github.com/mehradans92/dZiner.

[Arxiv](https://arxiv.org/abs/2410.03963)