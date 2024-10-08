# dZiner：借助 AI 代理实现材料的理性逆向设计

发布时间：2024年10月04日

`Agent` `材料科学`

> dZiner: Rational Inverse Design of Materials with AI Agents

# 摘要

> 机器学习与人工智能的最新进展，正借助科学数据的力量，彻底改变新材料的研究方式。尽管科学文献浩如烟海，但能轻松融入数据驱动流程的结构化实验数据和化学知识却寥寥无几。我们致力于整合这些信息，并引入第一性原理计算和物理驱动深度学习模型，以高效探索化学空间，预见新材料的特性。最终，我们的框架将能媲美人类专家的深厚知识。在此，我们推出dZiner——一位由大型语言模型驱动的化学家AI助手，它通过逆向设计，从所需性质出发，发现全新化合物。dZiner深入科学文献，汲取专业见解，提出性能卓越的新材料，并在理性设计中反复验证，确保符合设计规范。它还支持人机协同，实时推断材料特性，评估不确定性与可行性。我们已将dZiner应用于表面活性剂、配体、药物候选物及金属有机框架等多种材料，展现了其广泛适用性。这一创新方法不仅加速了新材料发现，更让定制化材料设计成为可能。dZiner现已开源，代码详见https://github.com/mehradans92/dZiner。

> Recent breakthroughs in machine learning and artificial intelligence, fueled by scientific data, are revolutionizing the discovery of new materials. Despite the wealth of existing scientific literature, the availability of both structured experimental data and chemical domain knowledge that can be easily integrated into data-driven workflows is limited. The motivation to integrate this information, as well as additional context from first-principle calculations and physics-informed deep learning surrogate models, is to enable efficient exploration of the relevant chemical space and to predict structure-property relationships of new materials a priori. Ultimately, such a framework could replicate the expertise of human subject-matter experts. In this work, we present dZiner, a chemist AI agent, powered by large language models (LLMs), that discovers new compounds with desired properties via inverse design (property-to-structure). In specific, the agent leverages domain-specific insights from foundational scientific literature to propose new materials with enhanced chemical properties, iteratively evaluating them using relevant surrogate models in a rational design process, while accounting for design constraints. The model supports both closed-loop and human-in-the-loop feedback cycles, enabling human-AI collaboration in molecular design with real-time property inference, and uncertainty and chemical feasibility assessment. We demonstrate the flexibility of this agent by applying it to various materials target properties, including surfactants, ligand and drug candidates, and metal-organic frameworks. Our approach holds promise to both accelerate the discovery of new materials and enable the targeted design of materials with desired functionalities. The methodology is available as an open-source software on https://github.com/mehradans92/dZiner.

[Arxiv](https://arxiv.org/abs/2410.03963)