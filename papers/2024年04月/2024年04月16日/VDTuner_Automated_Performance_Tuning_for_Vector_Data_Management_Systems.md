# VDTuner：自动优化向量数据管理系统的性能

发布时间：2024年04月16日

`LLM理论` `信息检索` `机器学习`

> VDTuner: Automated Performance Tuning for Vector Data Management Systems

# 摘要

> 向量数据管理系统（VDMSs）是大型信息检索和机器学习系统，如大型语言模型的关键支撑。为了增强相似性搜索的效率与适应性，VDMS提供了众多可调节的索引与系统参数。但VDMS本身的特性使得自动性能调优面临重大挑战，现行的自动调优方法难以应对。本文提出了VDTuner——一个依托多目标贝叶斯优化的学习型VDMS自动性能调优框架。VDTuner无需先验知识，便能有效探索复杂的多维参数空间，同时在搜索速度与召回率间找到理想平衡，实现最优配置。经过大量评估验证，VDTuner相较于默认设置能显著提升VDMS的性能（搜索速度提升14.12%，召回率提升186.38%），并与现有顶尖基线相比，调优时间快达3.57倍。VDTuner还支持用户个性化偏好和成本敏感型优化目标的扩展。项目已上线，地址为：https://github.com/tiannuo-yang/VDTuner。

> Vector data management systems (VDMSs) have become an indispensable cornerstone in large-scale information retrieval and machine learning systems like large language models. To enhance the efficiency and flexibility of similarity search, VDMS exposes many tunable index parameters and system parameters for users to specify. However, due to the inherent characteristics of VDMS, automatic performance tuning for VDMS faces several critical challenges, which cannot be well addressed by the existing auto-tuning methods. In this paper, we introduce VDTuner, a learning-based automatic performance tuning framework for VDMS, leveraging multi-objective Bayesian optimization. VDTuner overcomes the challenges associated with VDMS by efficiently exploring a complex multi-dimensional parameter space without requiring any prior knowledge. Moreover, it is able to achieve a good balance between search speed and recall rate, delivering an optimal configuration. Extensive evaluations demonstrate that VDTuner can markedly improve VDMS performance (14.12% in search speed and 186.38% in recall rate) compared with default setting, and is more efficient compared with state-of-the-art baselines (up to 3.57 times faster in terms of tuning time). In addition, VDTuner is scalable to specific user preference and cost-aware optimization objective. VDTuner is available online at https://github.com/tiannuo-yang/VDTuner.

[Arxiv](https://arxiv.org/abs/2404.10413)