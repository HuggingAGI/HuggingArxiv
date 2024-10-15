# 如何在大语言模型对齐中巧妙利用演示数据？让我们从自我模仿学习的角度一探究竟。

发布时间：2024年10月13日

`LLM理论` `人工智能` `机器学习`

> How to Leverage Demonstration Data in Alignment for Large Language Model? A Self-Imitation Learning Perspective

# 摘要

> 本文提出了一种创新的广义自我模仿学习 ($\textbf{GSIL}$) 框架，该框架能高效地将大型语言模型与离线数据对齐。通过引入密度比估计的代理目标，$\textbf{GSIL}$ 不仅简化了模仿学习过程，还避免了复杂的对抗训练，实现了对大型语言模型的高效微调。此外，$\textbf{GSIL}$ 通过广义凸函数参数化的离线损失，提供了一种与演示数据对齐的统一视角。实验结果显示，$\textbf{GSIL}$ 在编码、数学推理和指令跟随等多个挑战性基准测试中，均显著超越了现有方法。

> This paper introduces a novel generalized self-imitation learning ($\textbf{GSIL}$) framework, which effectively and efficiently aligns large language models with offline demonstration data. We develop $\textbf{GSIL}$ by deriving a surrogate objective of imitation learning with density ratio estimates, facilitating the use of self-generated data and optimizing the imitation learning objective with simple classification losses. $\textbf{GSIL}$ eliminates the need for complex adversarial training in standard imitation learning, achieving lightweight and efficient fine-tuning for large language models. In addition, $\textbf{GSIL}$ encompasses a family of offline losses parameterized by a general class of convex functions for density ratio estimation and enables a unified view for alignment with demonstration data. Extensive experiments show that $\textbf{GSIL}$ consistently and significantly outperforms baselines in many challenging benchmarks, such as coding (HuamnEval), mathematical reasoning (GSM8K) and instruction-following benchmark (MT-Bench).

[Arxiv](https://arxiv.org/abs/2410.10093)