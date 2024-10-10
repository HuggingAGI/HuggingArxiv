# 简单为王：重新审视 LLM 遗忘中的负偏好优化

发布时间：2024年10月09日

`LLM理论` `人工智能` `机器学习`

> Simplicity Prevails: Rethinking Negative Preference Optimization for LLM Unlearning

# 摘要

> 我们致力于解决 LLM 的遗忘难题，旨在在不重新训练的情况下，消除不必要的数据影响和模型能力，同时保留核心功能。尽管 LLM 遗忘的需求日益增长，但缺乏一个系统的优化框架。我们重新审视了前沿的 NPO 方法，发现其参考模型偏差问题，特别是在处理不同难度数据时，可能削弱其效果。为此，我们提出了 SimNPO，一个简单高效的遗忘优化框架，通过简化对参考模型的依赖，显著提升了遗忘效果。通过马尔可夫链混合物的深入分析，我们进一步揭示了 SimNPO 的优势。实验证明，SimNPO 在 TOFU 和 MUSE 等基准测试中表现优异，且能抵御重新学习攻击。代码已公开，详见 https://github.com/OPTML-Group/Unlearn-Simple。

> In this work, we address the problem of large language model (LLM) unlearning, aiming to remove unwanted data influences and associated model capabilities (e.g., copyrighted data or harmful content generation) while preserving essential model utilities, without the need for retraining from scratch. Despite the growing need for LLM unlearning, a principled optimization framework remains lacking. To this end, we revisit the state-of-the-art approach, negative preference optimization (NPO), and identify the issue of reference model bias, which could undermine NPO's effectiveness, particularly when unlearning forget data of varying difficulty. Given that, we propose a simple yet effective unlearning optimization framework, called SimNPO, showing that 'simplicity' in removing the reliance on a reference model (through the lens of simple preference optimization) benefits unlearning. We also provide deeper insights into SimNPO's advantages, supported by analysis using mixtures of Markov chains. Furthermore, we present extensive experiments validating SimNPO's superiority over existing unlearning baselines in benchmarks like TOFU and MUSE, and robustness against relearning attacks. Codes are available at https://github.com/OPTML-Group/Unlearn-Simple.

[Arxiv](https://arxiv.org/abs/2410.07163)