# 在线 RLHF 与神经参数化的全局收敛性探讨

发布时间：2024年10月20日

`LLM理论` `人工智能` `机器学习`

> On The Global Convergence Of Online RLHF With Neural Parametrization

# 摘要

> 人类反馈强化学习（RLHF）在使大型语言模型（LLM）与人类价值观对齐中的重要性不言而喻。RLHF 包括监督微调、奖励学习和策略学习三个阶段。尽管有多种方法对齐 LLM，但常面临分布偏移问题，源于奖励与策略学习阶段间的分布依赖性难以准确捕捉。这导致近似方法盛行，但理论与实践间的差距依然显著。解决这一差距需分析神经网络参数化设置中 AI 对齐算法的性能。双层公式虽有潜力，但受超梯度问题困扰，缺乏高效算法。我们采用 Kwon 等人（2024）的双层公式，并假设 \emph{弱梯度支配}，证明 RLHF 设置中的收敛性，获得 $ε^{-\frac{7}{2}}$ 的样本复杂度。主要贡献：（i）提出参数化设置中的 AI 对齐双层公式，并引入一阶方法解决；（ii）分析算法理论收敛率，推导最先进界限。据我们所知，这是首个为神经网络参数化设置中的 RLHF 框架建立收敛率界限和全局最优性的研究。

> The importance of Reinforcement Learning from Human Feedback (RLHF) in aligning large language models (LLMs) with human values cannot be overstated. RLHF is a three-stage process that includes supervised fine-tuning (SFT), reward learning, and policy learning. Although there are several offline and online approaches to aligning LLMs, they often suffer from distribution shift issues. These issues arise from the inability to accurately capture the distributional interdependence between the reward learning and policy learning stages. Consequently, this has led to various approximated approaches, but the theoretical insights and motivations remain largely limited to tabular settings, which do not hold in practice. This gap between theoretical insights and practical implementations is critical. It is challenging to address this gap as it requires analyzing the performance of AI alignment algorithms in neural network-parameterized settings. Although bi-level formulations have shown promise in addressing distribution shift issues, they suffer from the hyper-gradient problem, and current approaches lack efficient algorithms to solve this. In this work, we tackle these challenges employing the bi-level formulation laid out in Kwon et al. (2024) along with the assumption \emph{Weak Gradient Domination} to demonstrate convergence in an RLHF setup, obtaining a sample complexity of $ε^{-\frac{7}{2}}$ . Our key contributions are twofold: (i) We propose a bi-level formulation for AI alignment in parameterized settings and introduce a first-order approach to solve this problem. (ii) We analyze the theoretical convergence rates of the proposed algorithm and derive state-of-the-art bounds. To the best of our knowledge, this is the first work to establish convergence rate bounds and global optimality for the RLHF framework in neural network-parameterized settings.

[Arxiv](https://arxiv.org/abs/2410.15610)