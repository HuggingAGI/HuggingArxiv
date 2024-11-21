# 自我修复机器学习：一个适用于现实环境的自主适应框架

发布时间：2024年10月31日

`LLM应用` `机器学习` `数据处理`

> Self-Healing Machine Learning: A Framework for Autonomous Adaptation in Real-World Environments

# 摘要

> 在现实世界里，机器学习系统常常因基础数据生成过程（DGP）的分布变化，导致模型性能下滑。现有的应对方法，像概念漂移适应，受其原因不明的特性所限。这些方法从预先设定的一组动作中选择，默认模型性能下降的原因与应采取的动作无关，这就限制了它们选择恰当适应措施的能力。在本文中，我们提出了一种能克服这些局限的替代模式，叫做自愈机器学习（SHML）。和以往的方法不同，SHML 能自主诊断性能下降的原因，并给出基于诊断的纠正举措。我们把 SHML 构建成适应动作空间上的优化问题，以在变化的 DGP 下将预期风险最小化。我们为自愈系统引入了理论框架，并打造了一个智能自愈解决方案 H-LLM，它借助大型语言模型，通过推理 DGP 背后的结构进行自我诊断，通过提出和评估纠正措施来实现自我适应。在实验中，我们对 H-LLM 的不同组件进行分析，以明白其奏效的原因和时机，展现出自愈机器学习的潜力。

> Real-world machine learning systems often encounter model performance degradation due to distributional shifts in the underlying data generating process (DGP). Existing approaches to addressing shifts, such as concept drift adaptation, are limited by their reason-agnostic nature. By choosing from a pre-defined set of actions, such methods implicitly assume that the causes of model degradation are irrelevant to what actions should be taken, limiting their ability to select appropriate adaptations. In this paper, we propose an alternative paradigm to overcome these limitations, called self-healing machine learning (SHML). Contrary to previous approaches, SHML autonomously diagnoses the reason for degradation and proposes diagnosis-based corrective actions. We formalize SHML as an optimization problem over a space of adaptation actions to minimize the expected risk under the shifted DGP. We introduce a theoretical framework for self-healing systems and build an agentic self-healing solution H-LLM which uses large language models to perform self-diagnosis by reasoning about the structure underlying the DGP, and self-adaptation by proposing and evaluating corrective actions. Empirically, we analyze different components of H-LLM to understand why and when it works, demonstrating the potential of self-healing ML.

[Arxiv](https://arxiv.org/abs/2411.00186)