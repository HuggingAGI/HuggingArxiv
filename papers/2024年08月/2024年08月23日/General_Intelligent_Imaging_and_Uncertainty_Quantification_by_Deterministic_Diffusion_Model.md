# 利用确定性扩散模型，我们实现了通用智能成像及不确定性量化。

发布时间：2024年08月23日

`LLM理论` `生命科学` `自动驾驶`

> General Intelligent Imaging and Uncertainty Quantification by Deterministic Diffusion Model

# 摘要

> 计算成像在多个领域如自动驾驶和生命科学中扮演关键角色，但传统方法计算量大且不具扩展性。深度学习虽擅长处理局部模式，却难以应对全局到局部的非局部模式。为此，我们创新性地提出了确定性扩散模型（DDM），一种采用渐进去噪策略的深度学习框架，以低成本实现通用计算成像。实验证明，DDM在重建非局部模式图像方面表现卓越，如多模光纤散斑和二次谐波强度模式，性能超越了现有顶尖算法。通过结合贝叶斯推理，我们为DDM构建了理论基础，并验证了其不确定性量化能力，确保了在高风险环境下的预测准确性。这一多功能框架有望提升并扩展现有深度学习成像技术的应用范围。

> Computational imaging is crucial in many disciplines from autonomous driving to life sciences. However, traditional model-driven and iterative methods consume large computational power and lack scalability for imaging. Deep learning (DL) is effective in processing local-to-local patterns, but it struggles with handling universal global-to-local (nonlocal) patterns under current frameworks. To bridge this gap, we propose a novel DL framework that employs a progressive denoising strategy, named the deterministic diffusion model (DDM), to facilitate general computational imaging at a low cost. We experimentally demonstrate the efficient and faithful image reconstruction capabilities of DDM from nonlocal patterns, such as speckles from multimode fiber and intensity patterns of second harmonic generation, surpassing the capability of previous state-of-the-art DL algorithms. By embedding Bayesian inference into DDM, we establish a theoretical framework and provide experimental proof of its uncertainty quantification. This advancement ensures the predictive reliability of DDM, avoiding misjudgment in high-stakes scenarios. This versatile and integrable DDM framework can readily extend and improve the efficacy of existing DL-based imaging applications.

[Arxiv](https://arxiv.org/abs/2408.13061)